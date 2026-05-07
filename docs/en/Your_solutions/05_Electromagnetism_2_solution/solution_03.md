## 3. Biot-Savart Law

**Problem Statement:** A small segment of a line wire of length $0.1 \text{ m}$ carries a current of $3 \text{ A}$. The segment is located at a distance of $0.2 \text{ m}$ from a point $P$. Calculate the magnetic field at point $P$ due to this current segment (assume the segment is perpendicular to the line connecting it to point $P$).

### Given Data:
* **Length of segment ($dl$):** $0.1 \text{ m}$
* **Current ($I$):** $3 \text{ A}$
* **Distance ($r$):** $0.2 \text{ m}$
* **Angle ($\theta$):** $90^\circ$ (perpendicular)
* **Permeability constant ($\frac{\mu_0}{4\pi}$):** $10^{-7} \text{ T}\cdot\text{m/A}$

### Theory:
The **Biot-Savart Law** for a small current element is given by:
$$dB = \frac{\mu_0}{4\pi} \frac{I \cdot dl \cdot \sin\theta}{r^2}$$

Since the segment is perpendicular to the point, $\sin(90^\circ) = 1$.

### Calculation:
Substitute the values into the formula:
$$B = (10^{-7}) \times \frac{3 \times 0.1 \times 1}{(0.2)^2}$$

1. Calculate the numerator: $3 \times 0.1 = 0.3$
2. Calculate the denominator: $(0.2)^2 = 0.04$
3. Divide:
$$B = 10^{-7} \times \frac{0.3}{0.04}$$
$$B = 10^{-7} \times 7.5$$

### Final Answer:
The magnetic field at point $P$ is **$7.5 \times 10^{-7} \text{ T}$**.
