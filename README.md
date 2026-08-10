# Atlas Cargo Airplane

Atlas is a custom scratch-built radio-controlled (RC) cargo airplane designed using foamboard, a twin-motor setup, and modular electronic systems. This repository contains the complete Bill of Materials (BOM), design files, electrical layout, and step-by-step build documentation.

<!-- INSERT IMAGE 1 HERE: Place a hero photo of the fully assembled plane or a 3D CAD render of the airframe here -->

> **Project Goal:** Build a reliable, high-payload foamboard cargo plane under a strict budget ceiling of $600 USD (SAR 2,250).

---

## About The Project

Since I was young, I've always loved airplanes! Over the last couple of years, I really wanted to build my own RC plane, but I lacked the motivation and funding to bring it to life. Getting the opportunity to build Atlas makes this project an incredible journey, and it's going to be very fun to construct, test, and fly.

---

## Progress So Far

🟢 **Project Scoping & Design:** Defined payload goals, twin-motor configuration, and channel requirements.  
🟢 **Bill of Materials (BOM):** Selected all 20 hardware items, tools, and electronics within the $600 USD budget ceiling.  
🟢 **Repository Setup:** Created GitHub project structure, documentation, and CSV tracking files.  
🔴 **Verification & Funding:** Finalizing verification approval to secure project grant funds.  
🔴 **Templates & CAD:** Generating 1:1 scale printable 2D foamboard templates.  
🔴 **Airframe Build:** Cutting foamboard and assembling the fuselage, wing spar, and control surfaces.  
🔴 **Electronics & Maiden Flight:** Installing power system, servos, camera, and completing first test flight.  

---

## Technical Specifications

| Feature | Specification |
| :--- | :--- |
| **Airframe Material** | 5mm Foamboard & Bamboo Reinforcements |
| **Control Channels** | 10 Channels (FlySky i6X + iA10B Receiver) |
| **Power System** | Twin Brushless Motors + ESCs |
| **Flight Battery** | 3S LiPo System |
| **Onboard Camera** | SQ11 1080p HD Action Cam (MicroSD Recording) |
| **Special Features** | Retractable Landing Gear & Payload Parachute Drop |

---

## Bill of Materials (BOM)

The full component list and budget breakdown are tracked below.

| Item Name | Quantity | Price (SAR) | Price (USD) |
| :--- | :--- | :--- | :--- |
| Foam Board | 10 Sheets | 360.00 | $97.20 |
| Skewer | 100 Pc | 4.50 | $1.22 |
| Steel Pushrods | 10 | 98.00 | $26.46 |
| Control Horns / Clevises | 20 Pc | 57.00 | $15.39 |
| Motor Pack with ESCs | 2 Sets | 126.00 | $34.02 |
| Controller / Receiver Pack | 1 (i6X + iA10B) | 361.00 | $97.47 |
| Servos | 10 Pack | 75.00 | $20.25 |
| Battery | 2 Pcs | 269.00 | $72.63 |
| Battery Charger | 1 | 112.00 | $30.24 |
| Landing Gear Base | 3 | 57.00 | $15.39 |
| Wheels Pack | 1 | 78.00 | $21.06 |
| Servo Extension Cables | 1 Pack | 59.00 | $15.93 |
| Parachute | 1 | 97.00 | $26.19 |
| Glue Gun + Sticks | 1 | 49.00 | $13.23 |
| Craft Knife | 1 | 45.00 | $12.15 |
| Soldering Iron Kit | 1 | 106.00 | $28.62 |
| Velcro Tape | 1 | 42.00 | $11.34 |
| Hobby Tape | 1 | 28.00 | $7.56 |
| SQ11 Mini Camera | 1 | 42.00 | $11.34 |
| MicroSD Card | 1 | 89.00 | $24.03 |
| **TOTAL** | **20 Items** | **SAR 2,154.50** | **$581.72** |

*Note: Component links are available in the repository's `BOM.csv` file.*

---

## Build Breakdown & Layout

### 1. Airframe Construction
The airframe is built from cut foamboard templates reinforced with bamboo skewers along high-stress spars and the fuselage keel. 

<!-- INSERT IMAGE 2 HERE: Place a photo of your printed 2D templates taped together or foam pieces cut out on the workbench -->

### 2. Avionics & Wiring Layout
Control surfaces are actuated by 9g servos connected via steel pushrods and clevises. The FlySky iA10B receiver manages flight controls, retractable gear, and the parachute release servo.

<!-- INSERT IMAGE 3 HERE: Place an electrical wiring diagram or top-down photo showing ESC, receiver, and servo wiring inside the fuselage -->

### 3. Onboard Recording
Flight footage is captured onboard via an SQ11 1080p mini action camera mounted in the nose section, recording directly to a high-speed MicroSD card.

<!-- INSERT IMAGE 4 HERE: Place a close-up photo of the camera mount or landing gear mechanism -->

---

## Repository Structure

```text
├── README.md             # Project documentation
├── BOM.csv               # Complete Bill of Materials with purchase links
├── plans/                # Printable 2D template files (PDF / DXF)
└── media/                # Build photos, schematics, and flight footage
