# GEMDAT test data

The test data are from a short simulation using VASP (5000 time steps).

Extract data using:

```bash
tar -C short_simulation -xjf short_simulation/vasprun.xml.bz2
```

## NPT (variable-lattice) data

`short_simulation_npt/vasprun_npt.xml.bz2` holds the first 200 ionic steps of a
Li6PS5Cl NPT run (`ISIF=3`, so the cell varies per frame). It is used to
regression-test variable-lattice handling (see GEMDAT issue #394).

Extract data using:

```bash
tar -C short_simulation_npt -xjf short_simulation_npt/vasprun_npt.xml.bz2
```
