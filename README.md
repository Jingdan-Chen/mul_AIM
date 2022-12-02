# mul_AIM

---

## Main purpose

---

mul_AIM is used to fix the problem that we often feel confused to do AIM with midpoints in a huge molecule justifying the correct point according to atom groups to explain the chemical meaning.

To find the midpoint corresponding to the atom pair, we use vector dot multiplication to find the midpoints on the straight line of the two atoms.

## File to prepare

---

These two files should be prepared in the working dir and they should be placed in exactly the same way (This program is not responsible to align the molecule)

1. cps.xyz (cps.xyz obtained from Multiwfn "2-3-0")
2. mol.xyz (formal .xyz file of the molecule)

## Input arguments

---

### Find1 Mode

1. the atom pair
2. threshold value to find the corresponding point (0~-1, -0.9 by default)

### Find2 Mode

!!! Aiming to pose appropriate algorithm to post all the "considerable" points in the right order with the right threshold.

## Output

---

### Find1 Mode

The information of points satisfying the threshold