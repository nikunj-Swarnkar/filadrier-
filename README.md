# FILADRIER  
### *A DIY Filament Dryer for Better 3D Prints*

<p align="center">
  <img src="banner.png" alt="FILADRIER Banner" width="100%">
</p>

---

## Overview

**FilaDrier** is a DIY filament dryer designed to keep 3D printer filament dry and protected from moisture.

Wet filament can ruin print quality and lead to issues such as:

- Stringing  
- Popping or crackling sounds while printing  
- Weak layer adhesion  
- Brittle or weak prints  
- Poor surface finish  

FilaDrier helps reduce these problems by circulating air through a **silica gel filtration system** inside a sealed enclosure to maintain lower humidity levels.

This project is designed to be:

- Budget-friendly  
- Easy to build  
- Compact  
- Print-direct compatible  

---

## Features

- Airtight dry box design  
- Dual fan air circulation system  
- Silica gel moisture absorption  
- PTFE filament routing system  
- Direct print-from-box support  
- Temperature & humidity monitoring  
- Quiet operation using laptop fans  
- DIY and customizable

---

## Bill of Materials (BOM)

| # | Component | Purpose | Qty | Price | Subtotal | Link |
|---|---|---|---:|---:|---:|---|
| 1 | Micro USB Cable | Power connection | 1 | ₹106 / $1.06 | ₹106 / $1.06 | [link](https://www.amazon.in/gp/product/B09MNFNNVZ/ref=ox_sc_act_title_11?smid=A1WYWER0W24N8S&psc=1) |
| 2 | HP Laptop Cooling Fan (4-Pin) | Air circulation | 2 | ₹299 / $2.99 | ₹598 / $5.98 | [link](https://www.amazon.in/Witamy-15-ACXXX-15-AFXXX-15-BSXXX-813946-001/dp/B09LM8K62Z/) |
| 3 | Airtight Storage Containers | Main dryer enclosure | 2 | ₹637 / $6.37 | ₹1,274 / $12.74 | [link](https://www.amazon.in/gp/product/B0FR484TLT?smid=AXOGFIT0PZZ7G&psc=1) |
| 4 | PC4-M6 Pneumatic Connector | Filament pass-through | 2 | ₹251 / $2.51 | ₹251 / $2.51 | [link](https://www.amazon.in/gp/product/B0CKBTVZ9T?smid=AAJQ3K54TZ6MM&th=1) |
| 5 | PTFE Tube (4mm OD, 2mm ID) | Filament guide path | 1 | ₹599 / $5.99 | ₹599 / $5.99 | [link](https://www.amazon.in/Time-3D-Tetra-Fluoro-Ethulene/dp/B0CKBSZFP6/) |
| 6 | M3 Screws & Nuts Assortment | Assembly / Mounting | 1 Kit | ₹434 / $4.34 | ₹434 / $4.34 | [link](https://www.amazon.in/Phillips-Screws-pieces-Stainless-Assorted/dp/B0H21GVDZ6/) |
| 7 | Ball Bearings (608ZZ, 8×22×7 mm) | Rotating base | 1 Pack | ₹289 / $2.89 | ₹289 / $2.89 | [link](https://www.amazon.in/gp/product/B0D5H72295?smid=A1V350QXQFOZZS&th=1) |
| 8 | Breadboard and Wires | Wiring connections and testing | 1 Pack | ₹179 / $1.79 | ₹179 / $1.79 | [link](https://www.amazon.in/ePro-Labs-KIT-0010-Breadboard-Pieces/dp/B01BLJGS7M/) |
| 9 | SPDT Mini Toggle Switch | ON/OFF control | 1 Pack | ₹220 / $2.20 | ₹220 / $2.20 | [link](https://www.amazon.in/gp/product/B09WDKT8DK?smid=AJ6SIZC8YQDZX&psc=1) |
| 10 | Silica Gel Beads (Blue) | Moisture absorption | 1 Pack | ₹340 / $3.40 | ₹340 / $3.40 | [link](https://www.amazon.in/gp/product/B0D96715G3?smid=AB1WHZOSLF8K&th=1) |
| 11 | Mini LCD Temperature/Humidity Meter | Temperature & humidity monitoring | 1 | ₹180 / $1.80 | ₹180 / $1.80 | [link](https://www.amazon.in/Temperature-Thermo-Hygrometer-Hygrometer-Greenhouse-Enclosure/dp/B0FJRRJ6P8/) |
| | **Total** | | | | **₹4,470 / $44.70** | |


---

## Required 3D Prints

Print the following models before assembly.

### 1. Dry Box,get roller from here 

https://makerworld.com/en/models/39426-dyna-dry-box-filament-box-4l#profileId-38638
by [@Dynarun](https://makerworld.com/en/@Dynarun)

### 2. Compact PTFE Socket

https://makerworld.com/en/models/16294-compact-fitting-socket-for-dry-box#profileId-26865
by [@TrocheHole](https://makerworld.com/en/@TrocheHole)
or one can get the one from above one too 

### 3. External Air Dryer Parts

Print the external air dryer files included with this project.

---

## Tools Required

You may need:

- Soldering iron  
- Wire stripper  
- Drill or rotary tool  
- Hot glue or screws (optional)  
- Small screwdriver set  

---

# Assembly Guide

---

## Step 1: Print & Order Parts

Print all required 3D files and order all parts from the BOM.

Before assembly, make sure you have:

- Printed parts  
- Fans  
- Switch  
- Silica gel  
- PTFE fittings and tube  
- Hygrometer  
- USB cable

---

## Step 2: Assemble the Rotary Base

Assemble the rotary spool holder/base.

Make sure:

- The spool rotates smoothly  
- There is minimal friction  
- Filament can unwind properly

This helps prevent feeding issues during printing.

---

## Step 3: Install Components Inside the Box

Place the following inside the container:

### Inside the box:
- Rotary spool holder  
- Hygrometer / temperature-humidity meter

Position the hygrometer somewhere visible for easy monitoring.

---

## Step 4: Add PTFE Tube Openings

Create **3 holes** in the wall of the container wherever preferred.

Install the **PC4-M6 pneumatic fittings**.

These will act as filament routing ports.


Insert the PTFE tube through the fittings.

---

## Step 5: Add Airflow Holes

Create:

- **1 intake hole**
- **1 exhaust hole**

for the external air dryer.

Suggested airflow direction:

```text
Outside Air
      ↓
Intake Fan
      ↓
Silica Gel Chamber
      ↓
Air Filter
      ↓
Exhaust Fan
      ↓
Dry Box Interior
```

This allows moisture to be absorbed before air enters the enclosure.

---

## Step 6: Assemble the Air Dryer Module

Mount the system to the wall of the container in this order:

```text
Intake Fan → Silica Gel → Filter → Exhaust Fan
```

### Airflow explanation

**Fan 1 (Intake Fan)**  
Pulls air into the drying chamber.

**Silica Gel Chamber**  
Removes moisture from incoming air.

**Filter**  
Prevents dust or silica particles from entering the enclosure.

**Fan 2 (Exhaust Fan)**  
Pushes dried air into circulation.

Mount everything securely to avoid rattling.

Rubber dampers can be used to reduce vibration.

---

## Fan Wiring


<img src="sechmatic.png" alt="schematic" width="100%">

Your HP laptop fans use 4 wires:

Only connect:

- **Red**
- **Black**

The other two wires are unnecessary for this build.

---

### Important:
Do **NOT** connect the fans in series.

Both fans must receive the full **5V** supply.

---

## USB Power Setup

Take a Micro USB cable and strip it.

Inside you will usually find:

```text
Red   = +5V
Black = GND
White = Ignore
Green = Ignore
```

Connect:

```text
USB Red   → Fan Red wires
USB Black → Fan Black wires
```

Then connect the USB cable to:

- USB adapter  
- Power bank  
- Computer USB port

A **5V 2A adapter** is recommended.

---

## Using Silica Gel

Add silica gel beads to the drying chamber.

Recommended:

- Keep silica separate from filament  
- Use mesh or compartments  
- Replace or regenerate silica when saturated

Blue silica typically changes color when moisture is absorbed.

---

## How to Use

1. Place filament spool inside the box  
2. Feed filament through PTFE tube  
3. Turn ON the switch  
4. Monitor humidity using the hygrometer  
5. Print directly from the enclosure

For best results:

- Keep the box sealed  
- Avoid opening frequently  
- Regenerate silica regularly

---
## Renders 

![image](https://cdn.hackclub.com/019f8fb4-8f3b-795a-a671-5d77656756e1/4iL_Cereal_Container_Assy%20(1).png)
<img width="648" height="572" alt="image" src="https://github.com/user-attachments/assets/c71893e3-5b88-4088-9cb1-33a16bf244f9" />
<img width="613" height="572" alt="Screenshot 2026-08-15 144632" src="https://github.com/user-attachments/assets/42f71071-ba06-4211-9581-268f80b09762" />

---

## Contributing

Feel free to improve, remix, or modify this project.

Pull requests and ideas are welcome.

---

## License

This is an open-source DIY project.

Feel free to modify and share.

---

<p align="center">
Made for better prints and dryer filament.
</p>

