## Change

### Type Replace

![Flow](./img/type-judgement-flow.png)


### Compare

| prm | frc(cvff/cff91) | lammps | note |
| :-----:   | :-----:  | :-----:  | :-----:  |
| `BONDS` | `#quadratic_bond` / `#quartic_bond` | `bondtypes` (Bond Coeffs) | type:2 parameter:2/4 |
| `ANGLES` | `#quadratic_angle` / `#quartic_angle` | `angletypes` (Angle Coeffs) | type:3 parameter:2/4 |
| `DIHEDRALS` | `#torsion_1` / `#torsion_3` | `dihedraltypes` (Dihedral Coeffs) | type:4 parameter:3/6 |
| `IMPROPER` | `#out_of_plane`/`#wilson_out_of_plane` | `ooptypes` (Improper Coeffs) | type:4 parameter:2/3 |


