---
# Silicon
---

## 1. Bulk properties
| Method        | Band gap (eV) | Lattice constants (Å) |
| :-----------: |:-------------:|:---------------------:|
| PBE           | 0.61          |     5.47              |
| HSE06         | 1.16          |     5.43              | 
| Experimental  | 1.12          |     5.43              |

## 2. Dielectric tensor
$$
T = I + E
$$
### 2.1. Ionic contribution
$$
I =
\begin{bmatrix}
0 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{bmatrix}
$$
### 2.1. Electronic contribution
$$
E =
\begin{bmatrix}
12.99 & 0 & 0 \\
0 & 12.99 & 0 \\
0 & 0 & 12.99
\end{bmatrix}
$$

## 3. Point defects
### 3.1. T center 
#### 3.1.1. Formation energy diagram
![Alt text](https://github.com/JosephPVera/Silicon/blob/main/Point_defects/T-center/HSE06/formation-energy/energy_A-1.png)
#### 3.1.2. Kohn-Sham states for $T_0$ center
| Defect     | Charge | Magnetization ($\mu_{B}$) | Spin state |
| :--------: |:------:|:-------------------------:| :---------:|
| T          | 0      |        1                  |     1/2    |

![Alt text](https://github.com/JosephPVera/Silicon/blob/main/Point_defects/T-center/HSE06/T_0/kohn-sham-states-2.png)

#### 3.1.3. Localized states in Spind down 
![Alt text](https://github.com/JosephPVera/Silicon/blob/main/Point_defects/T-center/HSE06/T_0/Spin_down-kpoint_1.png)

#### 3.1.4. Kohn-Sham states for $T_0$ center: Excited state
| Defect     | Charge | Magnetization ($\mu_{B}$) | Spin state |
| :--------: |:------:|:-------------------------:| :---------:|
| T          | 0      |        1                  |     1/2    |

![Alt text](https://github.com/JosephPVera/Silicon/blob/main/ZPL/T_0/HSE06/Excited_state/kohn-sham-states.png)

### 3.2. G center 
#### 3.2.1. Formation energy diagram
#### 3.1.2. Kohn-Sham states for $G_0$ center
| Defect     | Charge | Magnetization ($\mu_{B}$) | Spin state |
| :--------: |:------:|:-------------------------:| :---------:|
| G          | 0      |        0                  |     0      |

![Alt text](https://github.com/JosephPVera/Silicon/blob/main/Point_defects/G_center/HSE06/G_0/kohn-sham-states-2.png)

#### 3.2.3. Localized states in Spind up 
![Alt text](https://github.com/JosephPVera/Silicon/blob/main/Point_defects/G_center/HSE06/G_0/Spin_up-kpoint_1-no.png)

#### 3.2.4. Localized states in Spind down 
![Alt text](https://github.com/JosephPVera/Silicon/blob/main/Point_defects/G_center/HSE06/G_0/Spin_down-kpoint_1-no.png)

#### 3.2.5. Kohn-Sham states for $T_0$ center: Excited state
| Defect     | Charge | Magnetization ($\mu_{B}$) | Spin state |
| :--------: |:------:|:-------------------------:| :---------:|
| G          | 0      |        0                  |     0      |
##### Spin up
![Alt text](https://github.com/JosephPVera/Silicon/blob/main/ZPL/G_0/HSE06/Excited_state_up/kohn-sham-states-2.png)
##### Spin down
![Alt text](https://github.com/JosephPVera/Silicon/blob/main/ZPL/G_0/HSE06/Excited_state_down/kohn-sham-states-2.png)

## 4. Zero Phonon line (ZPL) for point defects in silicon

### 1. T center
| Method        | ZPL (eV)      | $\lambda$ (nm)        |
| :-----------: |:-------------:|:---------------------:|
| PBE           | 0.367         |  3382                 |
| HSE06         | 0.881         |  1408                 | 

### 2. G center
| Method        | ZPL (eV) - Spin up | $\lambda$ (nm) - Spin up | ZPL (eV) - Spin down | $\lambda$ (nm) - Spin down | 
| :-----------: |:------------------:|:------------------------:|:--------------------:|:--------------------------:|
| PBE           | 0.355              |  3496                    | 0.355                |       3496                 |
| HSE06         | 0.765              |  1622                    | 0.765                |       1622                 | 
