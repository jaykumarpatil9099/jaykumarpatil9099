# Jaykumar Patil

**Vehicle Dynamics & Simulation Engineer** · M.Sc. Interdisciplinary Engineering (Automotive), Hochschule Trier · Trier, Germany

I build and validate vehicle simulation tools: lap-time simulators, multi-DoF vehicle models and tyre models, correlated against telemetry. My current focus is hybrid powertrains. My Master's thesis covers modelling, energy management and component sizing for a hydrogen-fuelled rotary range extender in a series-hybrid EV.

**Open to full-time roles in Germany from March 2027**: vehicle dynamics, simulation, race engineering, hybrid/EV powertrain.

[![CV](https://img.shields.io/badge/CV-PDF-red)](cv/CV.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jaykumar--patil-0A66C2?logo=linkedin)](https://www.linkedin.com/in/jaykumar-patil)
[![Email](https://img.shields.io/badge/Email-jaykumarpatil9099%40gmail.com-grey?logo=gmail)](mailto:jaykumarpatil9099@gmail.com)

---

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[GT3 Lap Time Simulator](https://github.com/jaykumarpatil9099/gt3-lap-time-simulator)** · [live page](https://jaykumarpatil9099.github.io/gt3-lap-time-simulator/) | Quasi-steady-state lap simulator for the Mercedes-AMG GT3 at the Nürburgring 24h, calibrated against iRacing telemetry. Fidelity ladder from point mass up to Pacejka MF 5.2 with combined slip; calibrated v05 hits **+0.04 %** vs the reference lap. Pure-MATLAB `.ibt` parser, sector-RMS calibration sweep, sensitivity tornado. A charter regression test in CI keeps the lap within ±1 %. | MATLAB · CI |
| **[Vehicle Dynamics Models](https://github.com/jaykumarpatil9099/vehicle-dynamics-models-matlab-simulink)** | Simulink toolkit from quarter-car to 14-DoF full vehicle, plus bicycle, longitudinal drive/brake and a Pacejka library. Every model is smoke-tested in CI. | Simulink · CI |
| **[14-DoF Full-Vehicle Model](https://github.com/jaykumarpatil9099/vd-14dof-full-vehicle-matlab-simulink)** | Standalone 14-DoF ride + handling model: body, unsprung masses, wheel spin, 8-speed drivetrain, brakes, ARBs and per-axle Pacejka tyres. Frequency-domain results within ~2 % of hand calculations. | Simulink · CI |
| **[Pacejka Magic Formula](https://github.com/jaykumarpatil9099/pacejka-tyre-model)** | Load-sensitive Magic Formula tyre model in **MATLAB and Python**. Both versions are tested against the same reference values in CI. | MATLAB · Python · uv |
| **[Ackermann Steering Analysis](https://github.com/jaykumarpatil9099/ackermann-steering-analysis)** | Pure, parallel and anti-Ackermann geometry: slip angles, tyre forces, wheelbase sensitivity. | MATLAB · CI |
| **[Tyre–Rim Explicit FEM](https://github.com/jaykumarpatil9099/tyre-rim-fem-ansys)** | Explicit-dynamics bump impact on a multi-material wheel assembly (hyperelastic tyre, elastic-plastic rim). | ANSYS |

Most MATLAB repos have an **Open in MATLAB Online** button, so you can run them in the browser with a free MathWorks account.

---

## Now

**Master's thesis** · Advanced Innovation Engineering (AIE), UK, remote · 09/2026 – 03/2027
Series-hybrid electric powertrain with a hydrogen-fuelled rotary (Wankel) range extender: system modelling, energy-management strategy and component sizing.

## Experience

**Powertrain & Electronics Head, Redline Racing (Supra SAEINDIA Formula Student)** · Pune, India · 11/2021 – 05/2022
Drivetrain design and validation, including semi-automatic paddle-shift actuation. Integrated and calibrated sensors (RPM, boost, lambda, IAT) for real-time telemetry. Wrote MATLAB lap-data processing to correlate vehicle response with driver feedback for setup work.

**Engineering Change Intern, Mahindra & Mahindra** · Nashik, India · 11/2021 – 05/2022
CATIA V5 component design with GD&T. ANSYS FEM for load paths and fatigue-prone regions, which improved structural durability by 15 %.

## Education

**M.Sc. Interdisciplinary Engineering (Automotive)** · Hochschule Trier · 10/2023 – 03/2027 (expected)
Vehicle Dynamics · Powertrain Systems · FEA · Mechatronics

**B.Sc. Mechanical Engineering** · JSPM Pune · 07/2019 – 05/2022

---

## Toolbox

**Simulation:** MATLAB · Simulink · ANSYS Mechanical / Explicit / Fluent · OpenFOAM
**Vehicle dynamics:** Lap-time simulation · multi-body vehicle models · Pacejka MF 5.2 · suspension kinematics · FFT / modal analysis
**Telemetry:** Cosworth PI Toolbox · MoTeC · iRacing `.ibt` parsing
**CAD:** CATIA V5 · SolidWorks · Siemens NX · Creo
**Software practice:** Git · GitHub Actions CI · MATLAB build tool + unit tests · Python (NumPy, pytest, uv, ruff)

## Certificates

[ANSYS training](cv/certificates/ansys.pdf) · [SAE Formula Student](cv/certificates/sae_formula_student.pdf) · [SAE India membership](cv/certificates/sae_india_membership.pdf) · [Mahindra & Mahindra internship](cv/certificates/mahindra_internship.pdf)

---

Off the clock I sim-race (LMU, iRacing). I treat it as a test bench for setup work, telemetry analysis and race strategy.
