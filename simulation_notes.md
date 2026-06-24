# Simulation Notes

## Solver

Ansys Lumerical FDTD Solutions

---

## Geometry

The device consists of:

- TiO₂ nanobar pair
- α-MoO₃ gap fill
- SiO₂ substrate

Nominal dimensions:

| Parameter | Value |
|------------|---------|
| Width (W) | 120 nm |
| Length (L) | 450 nm |
| Height (H) | 250 nm |
| Gap (g) | 60 nm |
| Period (P) | 600 nm |

---

## Boundary Conditions

| Direction | Boundary |
|------------|------------|
| X | Periodic |
| Y | Periodic |
| Z | PML |

---

## Excitation

Normal-incidence broadband plane wave.

Polarizations:

- TE (0°)
- TM (90°)

---

## Wavelength Range

750–1050 nm

---

## Analyte Sweep

Background refractive index:

```text
1.00
1.01
1.02
1.03
1.04
1.05
```

---

## Notes

The repository currently contains only the simulation models used in the study.

Analysis scripts, fitting routines, processed datasets, and publication figures will be released after publication of the manuscript.
