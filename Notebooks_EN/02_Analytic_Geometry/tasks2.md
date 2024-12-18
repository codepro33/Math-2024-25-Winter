
![alt text](image-35.png)
--------------
To prove that:

$$
\frac{d}{dx} \left( \ln(\sin(x)) \right) = \cot(x)
$$

### **Step-by-Step Proof**

1. **Apply the chain rule**:

The derivative of the natural logarithm, $\ln(u)$, is:

$$
\frac{d}{dx} \ln(u) = \frac{1}{u} \cdot \frac{du}{dx}
$$

Here, $u = \sin(x)$. So:

$$
\frac{d}{dx} \left( \ln(\sin(x)) \right) = \frac{1}{\sin(x)} \cdot \frac{d}{dx}(\sin(x))
$$

2. **Differentiate $\sin(x)$**:

The derivative of $\sin(x)$ with respect to $x$ is:

$$
\frac{d}{dx}(\sin(x)) = \cos(x)
$$

Substitute this result into the equation:

$$
\frac{d}{dx} \left( \ln(\sin(x)) \right) = \frac{1}{\sin(x)} \cdot \cos(x)
$$

3. **Simplify the expression**:

Simplify the fraction:

$$
\frac{\cos(x)}{\sin(x)} = \cot(x)
$$

4. **Final result**:

Thus, we have:

$$
\frac{d}{dx} \left( \ln(\sin(x)) \right) = \cot(x)
$$

### **Conclusion**:

The proof is complete!
----------------
To verify that for \( f(x) = \cos(x) \), the second derivative satisfies:

$$
f''(x) = -f(x)
$$

---

![alt text](image-36.png)

### **Step-by-Step Proof**

1. **Define the function**:

We are given:

$$
f(x) = \cos(x)
$$

2. **First derivative \( f'(x) \):**

The derivative of \( \cos(x) \) with respect to \( x \) is:

$$
f'(x) = -\sin(x)
$$

3. **Second derivative \( f''(x) \):**

Differentiate \( f'(x) = -\sin(x) \) again:

$$
f''(x) = -\frac{d}{dx}(\sin(x))
$$

The derivative of \( \sin(x) \) is \( \cos(x) \), so:

$$
f''(x) = -\cos(x)
$$

4. **Compare with \( -f(x) \):**

Recall that \( f(x) = \cos(x) \). Therefore:

$$
-f(x) = -\cos(x)
$$

Thus, we have:

$$
f''(x) = -f(x)
$$

---

### **Conclusion**:

We have verified that:

$$
f''(x) = -f(x)
$$
-------------------------------

![alt text](image-37.png)


### **Using de l'Hospital's Rule, find the improper limits**

---

#### **1. $\lim_{x\to0}\frac{\sin(x)}{x}$**

- **Step 1**: Identify the indeterminate form. As $x\to0$, $\sin(x)\to0$ and $x\to0$. The limit is of the form $\frac{0}{0}$.

- **Step 2**: Differentiate the numerator and denominator. Derivative of $\sin(x)$ is $\cos(x)$, and derivative of $x$ is $1$.

- **Step 3**: Apply L'Hospital's Rule: $\lim_{x\to0}\frac{\sin(x)}{x}=\lim_{x\to0}\frac{\cos(x)}{1}$.

- **Step 4**: Evaluate the limit. Since $\cos(0)=1$, the result is $\lim_{x\to0}\frac{\sin(x)}{x}=1$.

---

#### **2. $\lim_{x\to\infty}\frac{\ln(x)}{x}$**

- **Step 1**: Identify the indeterminate form. As $x\to\infty$, $\ln(x)\to\infty$ and $x\to\infty$. The limit is of the form $\frac{\infty}{\infty}$.

- **Step 2**: Differentiate the numerator and denominator. Derivative of $\ln(x)$ is $\frac{1}{x}$, and derivative of $x$ is $1$.

- **Step 3**: Apply L'Hospital's Rule: $\lim_{x\to\infty}\frac{\ln(x)}{x}=\lim_{x\to\infty}\frac{\frac{1}{x}}{1}$.

- **Step 4**: Simplify and evaluate the limit. Since $\frac{\frac{1}{x}}{1}=\frac{1}{x}$ and $\frac{1}{x}\to0$ as $x\to\infty$, the result is $\lim_{x\to\infty}\frac{\ln(x)}{x}=0$.

---

#### **3. $\lim_{x\to\infty}\frac{\exp(x)}{x}$**

- **Step 1**: Identify the indeterminate form. As $x\to\infty$, $\exp(x)\to\infty$ and $x\to\infty$. The limit is of the form $\frac{\infty}{\infty}$.

- **Step 2**: Differentiate the numerator and denominator. Derivative of $\exp(x)$ is $\exp(x)$, and derivative of $x$ is $1$.

- **Step 3**: Apply L'Hospital's Rule: $\lim_{x\to\infty}\frac{\exp(x)}{x}=\lim_{x\to\infty}\frac{\exp(x)}{1}$.

- **Step 4**: Evaluate the limit. As $x\to\infty$, $\exp(x)\to\infty$, so the result is $\lim_{x\to\infty}\frac{\exp(x)}{x}=\infty$.

---

### **Final Answers**

1. $\lim_{x\to0}\frac{\sin(x)}{x}=1$  
2. $\lim_{x\to\infty}\frac{\ln(x)}{x}=0$  
3. $\lim_{x\to\infty}\frac{\exp(x)}{x}=\infty$

---------------------------------------------------------------------------

![alt text](image-38.png)


The position of the particle is given by:  
$x(t)=3t^2-6t+1$

We need to find:  
1. The velocity $V(t)=x'(t)$  
2. The acceleration $a(t)=x''(t)$  
3. The values of $V(t)$ and $a(t)$ at $t=2$.

---

### **Step 1: Find the velocity $V(t)$**
The velocity is the first derivative of $x(t)$ with respect to $t$:  
$V(t)=x'(t)=\frac{d}{dt}(3t^2-6t+1)$

Differentiating term by term:  
$V(t)=6t-6$

---

### **Step 2: Find the acceleration $a(t)$**
The acceleration is the derivative of the velocity, which is the second derivative of $x(t)$:  
$a(t)=x''(t)=\frac{d}{dt}(V(t))=\frac{d}{dt}(6t-6)$

Differentiating:  
$a(t)=6$

---

### **Step 3: Evaluate at $t=2$**
1. **Velocity at $t=2$:**  
   Substitute $t=2$ into $V(t)=6t-6$:  
   $V(2)=6(2)-6=12-6=6$

2. **Acceleration at $t=2$:**  
   The acceleration is constant, so:  
   $a(2)=6$

---

### **Final Answers**
- Velocity at $t=2$: $V(2)=6$  
- Acceleration at $t=2$: $a(2)=6$


To solve for the number of units $u$ that maximize the profit for the given profit function:

$$P(u)=-2u^2+50u-300$$

---

### **Step 1: Differentiate the profit function**
To find the maximum, take the first derivative of $P(u)$ with respect to $u$:

$$P'(u)=\frac{d}{du}(-2u^2+50u-300)$$

Differentiate term by term:

$$P'(u)=-4u+50$$

---

EXTREMUM

![alt text](image-40.png)

### **Step 2: Set the derivative equal to zero**
To find the critical point, set $P'(u)=0$ and solve for $u$:

$$-4u+50=0$$

Rearranging gives:

$$4u=50$$

Solve for $u$:

$$u=\frac{50}{4}=12.5$$

---

### **Step 3: Verify it is a maximum**
To confirm that $u=12.5$ is a maximum, check the second derivative of $P(u)$:

$$P''(u)=\frac{d}{du}(-4u+50)$$

The second derivative is:

$$P''(u)=-4$$

Since $P''(u)=-4<0$, the profit function is concave down, meaning $u=12.5$ gives a maximum.

---

### **Final Answer**
The number of units that maximize profit is:

$$u=12.5$$

![alt text](image-41.png)

To solve this problem, where we need to enclose the **largest possible rectangular area** with a string of length 10 meters, we follow these steps:






---

### **Step 1: Define the problem**
The string forms the perimeter of a rectangle. Let:  
- $l$ = length of the rectangle  
- $w$ = width of the rectangle  

The perimeter of the rectangle is given by:  
$$P=2l+2w$$

We are told the total perimeter is 10 meters, so:  
$$2l+2w=10\quad\text{or equivalently}\quad l+w=5$$

We need to **maximize the area** $A$ of the rectangle, which is given by:  
$$A=l\cdot w$$

---

### **Step 2: Express $w$ in terms of $l$**
From the perimeter equation $l+w=5$, solve for $w$:  
$$w=5-l$$

---

### **Step 3: Write the area in terms of $l$**
Substitute $w=5-l$ into the area equation $A=l\cdot w$:  
$$A=l\cdot(5-l)$$

Simplify:  
$$A=5l-l^2$$

---

### **Step 4: Maximize the area**
To maximize $A=5l-l^2$, take the derivative of $A$ with respect to $l$ and set it equal to zero:  
$$A'(l)=\frac{d}{dl}(5l-l^2)$$

Differentiate term by term:  
$$A'(l)=5-2l$$

Set $A'(l)=0$ to find the critical point:  
$$5-2l=0$$

Solve for $l$:  
$$l=\frac{5}{2}=2.5$$

---

### **Step 5: Find $w$ and verify the maximum**
From $w=5-l$, substitute $l=2.5$:  
$$w=5-2.5=2.5$$

Thus, the rectangle is a square with dimensions $l=2.5$ and $w=2.5$.

To confirm it's a maximum, note that the second derivative of $A$ is:  
$$A''(l)=\frac{d}{dl}(-2l)=-2$$

Since $A''(l)<0$, the critical point $l=2.5$ gives a maximum area.

---

### **Final Answer**
The dimensions of the rectangle that enclose the largest possible area are:  
$$l=2.5\,\text{meters},\,w=2.5\,\text{meters}$$









![alt text](image-42.png)

To find the extremum of the given function $f(x)=x^2+3x-5$, we proceed as follows:

---

### **Step 1: Differentiate the function**
The extremum occurs where the derivative of $f(x)$ is equal to zero. Differentiate $f(x)$ with respect to $x$:  
$$f'(x)=\frac{d}{dx}(x^2+3x-5)$$

Differentiate term by term:  
$$f'(x)=2x+3$$

---

### **Step 2: Set the derivative equal to zero**
To find the critical point, set $f'(x)=0$:  
$$2x+3=0$$

Solve for $x$:  
$$x=-\frac{3}{2}$$

---

### **Step 3: Verify the extremum**
To determine whether the critical point is a minimum or maximum, take the second derivative of $f(x)$:  
$$f''(x)=\frac{d}{dx}(2x+3)=2$$

Since $f''(x)=2>0$, the function is concave up, meaning the critical point at $x=-\frac{3}{2}$ is a **minimum**.

---

### **Step 4: Find the value of the extremum**
Substitute $x=-\frac{3}{2}$ into the original function $f(x)$:  
$$f\left(-\frac{3}{2}\right)=\left(-\frac{3}{2}\right)^2+3\left(-\frac{3}{2}\right)-5$$

Simplify step by step:  
$$f\left(-\frac{3}{2}\right)=\frac{9}{4}-\frac{9}{2}-5$$

Convert terms to have a common denominator:  
$$f\left(-\frac{3}{2}\right)=\frac{9}{4}-\frac{18}{4}-\frac{20}{4}$$

Combine the terms:  
$$f\left(-\frac{3}{2}\right)=\frac{9-18-20}{4}=\frac{-29}{4}$$

---

### **Final Answer**
The extremum occurs at $x=-\frac{3}{2}$, and the minimum value of the function is:  
$$f\left(-\frac{3}{2}\right)=-\frac{29}{4}$$







![alt text](image-43.png)


To find the extremum of the function $f(x)=\frac{x^2+2x+1}{x-1}$, follow these steps:

---

### **Step 1: Differentiate the function**
To find the critical points, we first take the derivative of $f(x)$ using the **quotient rule**. The quotient rule states:  
$$f'(x)=\frac{u'v-u v'}{v^2}$$

Here:  
- $u=x^2+2x+1$ (numerator)  
- $v=x-1$ (denominator)  

First, differentiate $u$ and $v$:  
- $u'=\frac{d}{dx}(x^2+2x+1)=2x+2$  
- $v'=\frac{d}{dx}(x-1)=1$  

Now, apply the quotient rule:  
$$f'(x)=\frac{(2x+2)(x-1)-(x^2+2x+1)(1)}{(x-1)^2}$$

---

### **Step 2: Simplify the derivative**
Simplify the numerator step by step:

1. Expand $(2x+2)(x-1)$:  
$$(2x+2)(x-1)=2x^2-2x+2x-2=2x^2-2$$

2. Combine with the second term $(x^2+2x+1)(1)$:  
$$\text{Numerator}=(2x^2-2)-(x^2+2x+1)$$  

Simplify the terms:  
$$\text{Numerator}=2x^2-2-x^2-2x-1=x^2-2x-3$$

Thus, the derivative is:  
$$f'(x)=\frac{x^2-2x-3}{(x-1)^2}$$

---

### **Step 3: Set the derivative equal to zero**
To find the critical points, set $f'(x)=0$. The derivative is zero when the numerator is zero:  
$$x^2-2x-3=0$$

Factorize the quadratic equation:  
$$x^2-2x-3=(x-3)(x+1)=0$$

Solve for $x$:  
$$x=3\quad\text{or}\quad x=-1$$

---

### **Step 4: Check for critical points and domain restrictions**
The denominator $(x-1)^2\neq0$, so $x=1$ is a point of discontinuity. Hence, $x=1$ is not part of the domain.

The critical points are $x=3$ and $x=-1$.

---

### **Step 5: Determine the nature of the critical points**
To check whether the critical points are maxima, minima, or neither, analyze the sign of $f'(x)$ around $x=3$ and $x=-1$:

1. **For $x=3$:**
   - Pick values around $x=3$ (e.g., $x=2.5$ and $x=3.5$).  
   - Evaluate the sign of $f'(x)$.

2. **For $x=-1$:**
   - Pick values around $x=-1$ (e.g., $x=-1.5$ and $x=-0.5$).  
   - Evaluate the sign of $f'(x)$.

---

### **Final Answer**
The function has critical points at $x=3$ and $x=-1$. Verify the nature of these points using the behavior of the derivative or the second derivative test.





![alt text](image-44.png)



To find the **Taylor series expansion** of $f(x)=\cos(x)$ around $x=0$ up to the 4th degree, follow these steps:

---

### **Step 1: Formula for the Taylor series**
The Taylor series of a function $f(x)$ around $x=0$ (Maclaurin series) is given by:  
$$f(x)=f(0)+\frac{f'(0)}{1!}x+\frac{f''(0)}{2!}x^2+\frac{f'''(0)}{3!}x^3+\frac{f^{(4)}(0)}{4!}x^4+\dots$$

We calculate the derivatives of $\cos(x)$, evaluate them at $x=0$, and include terms up to degree 4.

---

### **Step 2: Derivatives of $\cos(x)$**

1. **First derivative:**  
$$f'(x)=-\sin(x),\quad f'(0)=-\sin(0)=0$$

2. **Second derivative:**  
$$f''(x)=-\cos(x),\quad f''(0)=-\cos(0)=-1$$

3. **Third derivative:**  
$$f'''(x)=\sin(x),\quad f'''(0)=\sin(0)=0$$

4. **Fourth derivative:**  
$$f^{(4)}(x)=\cos(x),\quad f^{(4)}(0)=\cos(0)=1$$

---

### **Step 3: Substitute into the Taylor series**

Now substitute the values of $f(0)$, $f'(0)$, $f''(0)$, $f'''(0)$, and $f^{(4)}(0)$ into the Taylor series formula:

$$f(x)=f(0)+\frac{f'(0)}{1!}x+\frac{f''(0)}{2!}x^2+\frac{f'''(0)}{3!}x^3+\frac{f^{(4)}(0)}{4!}x^4$$

Substitute the values:  
- $f(0)=1$  
- $f'(0)=0$  
- $f''(0)=-1$  
- $f'''(0)=0$  
- $f^{(4)}(0)=1$

$$f(x)=1+0\cdot x+\frac{-1}{2!}x^2+0\cdot x^3+\frac{1}{4!}x^4$$

Simplify the terms:  
$$f(x)=1-\frac{x^2}{2}+\frac{x^4}{24}$$

---

### **Final Answer**
The Taylor series expansion of $\cos(x)$ around $x=0$ up to the 4th degree is:  
$$\cos(x)\approx 1-\frac{x^2}{2}+\frac{x^4}{24}$$
