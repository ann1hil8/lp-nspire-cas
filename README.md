# LP-Nspire: Advanced Laplace Transform Library

A robust TI-Basic library for the TI-Nspire CX II CAS, designed for Computer Engineering (CPE) and Electrical Engineering (EEE) coursework. This tool extends the native CAS capabilities to handle complex symbolic transforms, shifting theorems, and step-by-step inverse decompositions.

## 🚀 Features
- **Forward & Inverse Transforms:** High-stability symbolic processing.
- **First Shifting Theorem:** Full support for $e^{at}$ modulation.
- **t-Multiplication Rule:** Recursive differentiation for $t^n \cdot f(t)$ forms.
- **Dirac Delta Support:** Handles improper rational functions (Numerator_degree $\ge$ Denominator_degree) with impulse, doublet, and triplet outputs.
- **Step-by-Step Analysis:** `ilapsteps` provides pole multiplicity, partial fraction decomposition, and division forms for manual verification.
- **Transfer Function Optimization:** Automatic common denominator grouping for control systems applications.

## 🛠️ Public Functions
| Command | Usage |
| :--- | :--- |
| `lp\laplace(f, t, s)` | Computes $F(s)$ from $f(t)$. |
| `lp\ilaplace(F, s, t)` | Computes $f(t)$ from $F(s)$. |
| `lp\ilapsteps(F, s, t)` | Shows full work/decomposition for $F(s)$. |
| `lp\lapsteps(f, t, s)` | Shows branching logic for forward transforms. |
| `lp\decomplist(F, s)` | Returns a list of Partial Fraction terms. |
| `lp\polemultsmat(F, s)` | Returns a table of poles and their multiplicities. |

## 📦 Installation
1. Download the `lp.tns` file.
2. Transfer to Handheld:
   - Web (Easiest): Connect your calculator via USB and use [TI-Nspire Connect](https://nspireconnect.ti.com/nsc/).
   - Desktop: Use the TI-Nspire Computer Link or Student Software.
3. Place the file in the `MyLib` folder.
4. Press `Doc` > `7:Settings & Status` > `1:Refresh Libraries`.
5. Access the functions via the `lp\` prefix or the Library (Tab 6) in the Catalog.

## ⚠️ Requirements
- TI-Nspire CX CAS or CX II CAS (Hardware or Software)
- Document Setting: **Real** or **Rectangular Complex** (Recommended)

---
*Developed for Engineering Applications by Ryan Huston.*
