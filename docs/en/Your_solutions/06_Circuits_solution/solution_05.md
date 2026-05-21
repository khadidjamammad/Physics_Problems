# 5. Kirchhoff's Laws

Given:

- R1 = 20 Ω
- R2 = 10 Ω
- Internal resistances rw = 1 Ω
- E1 = 4.5 V
- E2 = 9 V

We use Kirchhoff’s Voltage Law (KVL).

---

## Step 1: Define Currents

Let:

- I1 = current in the left loop
- I2 = current through R2
- I3 = current in the right loop

At the junction:

I2 = I3 - I1

---

## Step 2: Left Loop Equation

Using KVL:

E1 - I1(R1 + rw) - I2R2 = 0

Substitute values:

4.5 - I1(20 + 1) - 10I2 = 0

4.5 - 21I1 - 10I2 = 0

Equation (1):

21I1 + 10I2 = 4.5

---

## Step 3: Right Loop Equation

Using KVL:

E2 - I3(rw) - I2R2 = 0

9 - I3(1) - 10I2 = 0

Equation (2):

I3 + 10I2 = 9

---

## Step 4: Junction Rule

I2 = I3 - I1

Equation (3):

I3 = I1 + I2

---

## Step 5: Solve Equations

Substitute Equation (3) into Equation (2):

(I1 + I2) + 10I2 = 9

I1 + 11I2 = 9

Now solve with Equation (1):

21I1 + 10I2 = 4.5

From:

I1 = 9 - 11I2

Substitute:

21(9 - 11I2) + 10I2 = 4.5

189 - 231I2 + 10I2 = 4.5

189 - 221I2 = 4.5

221I2 = 184.5

I2 ≈ 0.835 A

Now find I1:

I1 = 9 - 11(0.835)

I1 ≈ -0.185 A

Now find I3:

I3 = I1 + I2

I3 ≈ 0.650 A

---

# Final Answers

- I1 ≈ -0.185 A
- I2 ≈ 0.835 A
- I3 ≈ 0.650 A

(The negative sign means I1 flows opposite to the assumed direction.)
