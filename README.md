# Inceptor
An RC, modular, fixed-wing, dual-motor, 3D-printable aircraft capable of several configurations. I want to be able to have a flight platform capable of hosting a diverse set of missions on a singular base unit with a selection of wings, tails, noses, and other components.

The purpose of Inceptor is to allow users to purchase or build a modular aircraft and customize components tailored to their needs. Inceptor: Base V1 provides users with the ability to have a core, functioning unit intended to demonstrate modular ability in swapping batteries, ESCs, Flight Computer programs, and motors. Later version upgrades will allow users to instead print out different wings, a different tail, a different nose, different payload bay size, etc.

*Note that in future upgrades, you will be able to have a choice between which of each section's variation you would like to have (e.g, a longer variation of LW and RW).*

# Assembly for Inceptor: Base V1
**Setup**

1. Print all necessary 3D files
2. Purchase and/or obtain BOM and necessary tools (optionally heated insert tool)
3. Cut music wire into 2 sections of 180mm and 2 sections of 100mm
4. Cut carbon fiber tube into 2 sections of 450mm and 2 sections of 550mm

**VTail**

1. Insert servos into appropiate positions and run wire into hole of VT-Block
2. Ensure servos are in neutral position and connect servo horns
3. Connect VT-L-Ruddervator and VT-R-Ruddervator to appropriate servo
4. Insert 100mm music wire sections into Ruddervators
5. Apply glue to long, flat side of VT-L and VT-R (part that touches VT-Block)
6. Slide VT-L and VT-R onto the music wire and attach to VT-Block, referencing the CAD
7. Slide both 550mm carbon fiber longerons onto VT-Block
8. Connect servo wire extensions on both sides

Result should look like this (wires not included):
<img width="466" height="391" alt="image" src="https://github.com/user-attachments/assets/cd213c5e-9595-4a29-83c2-205412492d1d" />

**Wings**
1. Slide the far ends of each wing onto an indivudal 450mm carbon tube
2. Slide on the wing sections meant to go in front of each aileron, attach with glue
3. Insert a 180mm music wire section onto the far end wing pieces
4. Insert servos into appropriae positions and run wires into rectangular section of each wing
5. Ensure servos are in neutral position and connect servo horns
6. Connect ailerons to each servo horn
7. Attach servos' wing sections to currently assembled wing with glue, ensure aileron has music wire running through it
8. Apply heated inserts to motor blocks, use grub screws to attach motors
9. Slide motor blocks onto respective carbon spars, attach with glue and ensure wires run through to rectangular section
10. Connect servo and motor wire extensions on both sides
11. Result for left wing (so far) should look like this (wires not included):
    <img width="1033" height="498" alt="image" src="https://github.com/user-attachments/assets/e9457524-a85e-43ba-8d25-5d7fb9c05969" />
    
12. Slide remaining sections and attach with glue, referencing the CAD and keeping wires available

Result for right wing should look like this (wires not included):
<img width="629" height="475" alt="image" src="https://github.com/user-attachments/assets/dba6b49e-8ddb-4950-9a19-e7215a210fc7" />

**Fuselage**
1. Apply heated inserts to all respective holes on both wing attachments, starting from the inside
2. Slide on Payload Section Back to VT-Block, Payload Section Front, and Section 3, attach all to each other with glue
3. Holding Core Section Front, Wing Rod Stops, and Battery Tray in their positions relative to one another, referencing the CAD, slide onto the rest of the fuselage
4. Insert Arduino Mount's Bottom to its Top, and attach this assembly to the battery
5. Place battery in Battery Tray and secure with velcro straps
6. Add RX to Arduino Mount, and, optionally, add an Arduino
7. Screw Section 3 and Core Section Front onto Wing Attachment, ensure assembly looks like this so far (wires not included):
   <img width="843" height="583" alt="image" src="https://github.com/user-attachments/assets/bf8358c9-70a4-4e66-84c0-d1249da2b956" />

8. Fit Nose Cone Adapter onto longerons and ensure snap fit cantilevers are in Wing Attachments, referencing CAD
9. Fit Nose Cone onto longerons, attach to Nose Cone Adapter with glue
10. Connect both motor wire extensions to ESCs, connect ESCs to battery's XT60 via a Y-harness
11. Connect all servo wires to correct channel on RX, reference the Wiring Diagram
12. Fully slide wings onto each Wing Attachment and into Wing Rod Stops
13. Snap on Core Section Bottom, referencing the CAD, and attach with glue
14. Snap on Core Section Top

Result should look like this (wires and RX not included, Core Section Top made transparent):
<img width="929" height="627" alt="image" src="https://github.com/user-attachments/assets/781f6baf-affe-43c9-902a-42eab8350f19" />

# Wiring
**Diagram:** <img width="855" height="558" alt="image" src="https://github.com/user-attachments/assets/018e4de9-997e-4d02-bbc4-b9b28847db1a" />

Connect the servo extensions to all 4 servos. Connect the Female to Male 3-Phase Wire extensions to both motors' wires and to ESCs. Connect XT60 Y-Harness to ESCs and Battery. Disactivate BEC from Left Wing's ESC via disconnecting live wire, connect Right Wing ESC's signal wires to Left Wing ESC's via a Y-harness and connect to Channel 3. Connect VTail's left servo extension to Channel 4 and the right one to Channel 2. Connect Right Wing's servo wires to Left Wing's via connecting their extensions via Y-Harness and connecting to Channel 1. Set TX up for VTail configuration, and ensure all control surfaces and throttle work as intended, if not, simply reverse wire connection.

*Note: A detailed video tutorial will be provided once and while I assemble my own Inceptor prototype, along with values for Center of Gravity, weight, and other performance characteristics*

# OnShape CAD:
**Link:** https://cad.onshape.com/documents/1e6ea4fb9d6a4182b08372fd/w/82ca669ecb5636d0f431f821/e/5a5b780a35879ddb0144018a?renderMode=0&uiState=69f1591a146152ce74d726e6

**Images** 

Top View: <img width="941" height="600" alt="image" src="https://github.com/user-attachments/assets/30a2cfb8-7c38-446f-9880-bdd3b44b3f8a" />

Right View: <img width="954" height="371" alt="image" src="https://github.com/user-attachments/assets/fef3a605-e038-4eb2-82ff-ac0444460d72" />

Front View: <img width="931" height="215" alt="image" src="https://github.com/user-attachments/assets/b41a1d1a-3486-476f-b218-0a7ee6e24e0c" />

Isometric View: <img width="741" height="479" alt="image" src="https://github.com/user-attachments/assets/1d34c4f0-ad38-493c-aeb9-f3b31e9dfe04" />

# BOM (Inceptor: Base V1)
**Link:**
[BOM.csv](https://github.com/user-attachments/files/27289383/BOM.csv)


**Components, Total Price, and Quantity to Obtain**

CW A2212 Motor---------------$10.99-1

CCW A2212 Motor--------------$10.99-1

4S Battery-----------------------$26.99-1

Arduino (Optional)-------------$27.99-1

MG90S Servo--------------------$9.98-4

CC/CCW 9045 Propellers--------$2.99--1       

40A ESC w/ BEC-----------------$25.98-2

8x6mm 1m CF Tube-------------$16.72-2

M3x5 Heated Insert--------------$1.60-16

M3x10 Phillips Pan Head Screw-$0.56-8

M3x10 Grub Screw---------------$0.72-8

Epoxy Resin Glue and Hardener-$6.78-1

FlySky FSi6/iA6 TX/RX------------$49.99-1

1.5mm Music Wire----------------$4.59-1

Servo Wire Y-Harness------------$3.58-2

500mm Servo Wire Extensions---$0.99-4

Battery Velcro Strap---------------$0.99-1

**Total Upper-End (exclusive of shipping + taxes): *$209.21***

# Zine Page
<img width="2820" height="4000" alt="INCEPTOR (5 83 x 8 27 in)" src="https://github.com/user-attachments/assets/bbd102a0-8df9-41b3-8e6e-55d3327dcf19" />


*Real pictures and videos coming soon, for your convenience!!!*
