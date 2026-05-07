## 6. EM Wave Analysis

**Problem Statement:** An electromagnetic wave has its electric field component described by:
$$E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m}$$

### 1. Direction of Propagation
The argument of the sine function is $(kx - \omega t)$. Since the $x$ and $t$ terms have opposite signs, the wave is traveling in the **positive $x$ direction** ($+x$).

### 2. Wavelength ($\lambda$)
* From the equation, the wave number **$k = 10^7 \text{ rad/m}$**.
* **Formula:** $\lambda = \frac{2\pi}{k}$
* **Calculation:** $\lambda = \frac{2\pi}{10^7}$
* **Result:** $\lambda \approx 6.28 \times 10^{-7} \text{ m}$ (or **$628 \text{ nm}$**)

### 3. Angular Frequency ($\omega$)
* In a vacuum, $\omega = c \cdot k$, where $c \approx 3 \times 10^8 \text{ m/s}$.
* **Calculation:** $\omega = (3 \times 10^8) \times 10^7$
* **Result:** $\omega = 3 \times 10^{15} \text{ rad/s}$

### 4. Equation for the Magnetic Field Component ($B$)
* **Amplitude ($B_0$):** $B_0 = \frac{E_0}{c} = \frac{100}{3 \times 10^8} = 3.33 \times 10^{-7} \text{ T}$
* **Direction:** Since $E$ is in the $y$-direction and propagation is in the $x$-direction, $B$ must be in the **$z$-direction**.
* **Equation:**
$$B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T}$$
