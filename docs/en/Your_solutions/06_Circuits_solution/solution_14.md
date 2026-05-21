# 14. RLC Circuit

For a series RLC circuit, Kirchhoff’s Voltage Law gives:

V = L(dI/dt) + RI + (1/C)∫I dt

Since current is related to charge by:

I = dQ/dt

Substitute into the equation:

V = L(d²Q/dt²) + R(dQ/dt) + (1/C)Q

Rearranging:

L(d²Q/dt²) + R(dQ/dt) + (1/C)Q = V(t)

---

## Comparison with a Damped Harmonic Oscillator

The differential equation for a damped harmonic oscillator is:

m(d²x/dt²) + b(dx/dt) + kx = F(t)

Comparing the two equations:

| Electrical Quantity | Mechanical Analogy |
|---|---|
| Inductance L | Mass m |
| Resistance R | Damping coefficient b |
| 1/C | Spring constant k |
| Charge Q | Displacement x |
| Voltage V | Applied force F |

---

# Final Answer

The governing equation for a series RLC circuit is:

L(d²Q/dt²) + R(dQ/dt) + (1/C)Q = V(t)

It is mathematically analogous to the damped harmonic oscillator equation:

m(d²x/dt²) + b(dx/dt) + kx = F(t)
