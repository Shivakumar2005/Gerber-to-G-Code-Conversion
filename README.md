# Gerber-to-G-Code-Conversion
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output
# G Code
### Engraving G Code

%
( CopperCAM - 29/07/2019 / ISO-Mill Output )

( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 21:05 )

( Workpiece dimensions: 79.807 x 67.427 x 1 mm )

G21 G40 G54

G80 G90 G94

( Tool #1 "Basic Engraver" / Diameter 3.17 mm )

T1 M06

M03 S12000

M07

G00 X-2.324 Y2.994

G00 Z0

G01 F60 Z-0.2

G01 F600 X-2.008

G01 X-1.52 Y2.506

G01 X-1.52 Y1.816

G01 X-2.008 Y1.328

G01 X-2.697

G01 X-3.185 Y1.816

G01 Y2.506

G01 X-2.697 Y2.994

G01 X-2.584

G01 Y24.325

G01 X-2.641

G01 X-3.048 Y24.733

G01 Y25.309

G01 X-2.641 Y25.717

G01 X-2.064

G01 X-1.657 Y25.309

G01 Y24.733

G01 X-2.064 Y24.325

G01 X-2.324

G01 Y2.994

G00 Z2

G00 X-4.763

G00 Z0

G01 F60 Z-0.2

G01 F600 X-4.548

G01 X-4.06 Y2.506

G01 Y1.816

G01 X-4.548 Y1.328

G01 X-5.237

G01 X-5.725 Y1.816

G01 X-5.725 Y2.506

G01 X-5.237 Y2.994

G01 X-5.022

G01 Y24.325

G01 X-5.181

G01 X-5.588 Y24.733

G01 Y25.309

G01 X-5.181 Y25.717

G01 X-4.604

G01 X-4.197 Y25.309

G01 Y24.733

G01 X-4.604 Y24.325

G01 X-4.763

G01 Y2.994

G00 Z2

G00 X-23.66

G00 Z0

G01 F60 Z-0.2

G01 F600 X-23.598

G01 X-23.11 Y2.506

G01 Y1.816

G01 X-23.598 Y1.328

G01 X-24.287

G01 X-24.775 Y1.816

G01 Y2.506

G01 X-24.287 Y2.994

G01 X-23.92

G01 Y24.335

G01 X-24.074

G01 X-24.481 Y24.742

G01 Y25.319

G01 X-24.074 Y25.726

G01 X-23.497

G01 X-23.09 Y25.319

G01 Y24.742

G01 X-23.497 Y24.335

G01 X-23.66

G01 Y2.994

G00 Z2

G00 X-26.425

G00 Z0

G01 F60 Z-0.2

G01 F600 X-26.138

G01 X-25.65 Y2.506

G01 Y1.816

G01 X-26.138 Y1.328

G01 X-26.827

G01 X-27.315 Y1.816

G01 Y2.506

G01 X-26.827 Y2.994

G01 X-26.787

G01 X-32.632 Y8.838

G01 X-32.932 Y8.539

G01 X-34.003

G01 X-34.761 Y9.296

G01 Y10.367

G01 X-34.003 Y11.125

G01 X-32.932 Y11.125

G01 X-32.658 Y10.851

G01 X-26.663 Y16.845

G01 Y24.325

G01 X-26.771

G01 X-27.178 Y24.733

G01 Y25.309

G01 X-26.771 Y25.717

G01 X-26.194

G01 X-25.787 Y25.309

G01 Y24.733

G01 X-26.194 Y24.325

G01 X-26.403

G01 Y16.791

G01 X-26.406 Y16.766

G01 X-26.413 Y16.742

G01 X-26.425 Y16.719

G01 X-26.441 Y16.7

G01 X-32.474 Y10.667

G01 X-32.174 Y10.367

G01 Y9.296

G01 X-32.449 Y9.022

G01 X-26.441 Y3.015

G01 X-26.425 Y2.995

G01 X-26.425 Y2.994

G00 Z2

G00 X-3.048 Y27.742

G00 Z0

G01 F60 Z-0.2

G01 F600 Y27.849

G01 X-2.641 Y28.257

G01 X-2.064

G01 X-1.657 Y27.849

G01 Y27.273

G01 X-2.064 Y26.865

G01 X-2.641

G01 X-3.048 Y27.273

G01 Y27.482

G01 X-4.197

G01 Y27.273

G01 X-4.604 Y26.865

G01 X-5.181

G01 X-5.588 Y27.273

G01 Y27.482

G01 X-23.404

G01 Y27.263

G01 X-23.811 Y26.856

G01 X-24.388

G01 X-24.795 Y27.263

G01 Y27.482

G01 X-25.787

G01 Y27.273

G01 X-26.194 Y26.865

G01 X-26.403

G01 Y26.24

G01 X-26.406 Y26.215

G01 X-26.413 Y26.19

G01 X-26.425 Y26.168

G01 X-26.441 Y26.148

G01 X-33.261 Y19.328

G01 Y18.643

G01 X-32.932

G01 X-32.174 Y17.886

G01 Y16.814

G01 X-32.932 Y16.057

G01 X-34.003

G01 X-34.761 Y16.814

G01 Y17.886

G01 X-34.003 Y18.643

G01 X-33.521

G01 Y19.382

G01 X-33.519 Y19.407

G01 X-33.511 Y19.432

G01 X-33.499 Y19.454

G01 X-33.483 Y19.474

G01 X-26.663 Y26.294

G01 Y26.865

G01 X-26.771

G01 X-27.178 Y27.273

G01 Y27.849

G01 X-26.771 Y28.257

G01 X-26.194

G01 X-25.787 Y27.849

G01 Y27.742

G01 X-24.795

G01 Y27.839

G01 X-24.388 Y28.247

G01 X-23.811

G01 X-23.404 Y27.839

G01 Y27.742

G01 X-5.588

G01 Y27.849

G01 X-5.181 Y28.257

G01 X-4.604

G01 X-4.197 Y27.849

G01 Y27.742

G01 X-3.048

G00 Z2

M09

M05

M02

%




### Drill G Code


%

( CopperCAM - 29/07/2019 / ISO-Mill Output )

( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 21:04 )

( Workpiece dimensions: 79.807 x 67.427 x 1 mm )

G21 G40 G54

G80 G90 G94

( Tool #4 "Basic Drill" / Diameter 1 mm )

T4 M06

M03 S12000

M07

G00 X-2.352 Y25.021

G00 Z0

G01 F60 Z-1

G00 Z2

G00 Y27.561

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-4.892

G00 Z0

G01 F60 Z-1

G00 Z2

G00 Y25.021

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-23.785 Y25.031

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-24.099 Y27.551

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-26.482 Y27.561

G00 Z0

G01 F60 Z-1

G00 Z2

G00 Y25.021

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-33.467 Y17.35

G00 Z0

G01 F60 Z-1

G00 Z2

G00 Y9.832

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-26.482 Y2.161

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-23.942

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-4.892

G00 Z0

G01 F60 Z-1

G00 Z2

G00 X-2.352

G00 Z0

G01 F60 Z-1

G00 Z2

M09

M05

M02

%



### Cutting G Code

%

( CopperCAM - 29/07/2019 / ISO-Mill Output )

( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 21:07 )

( Workpiece dimensions: 79.807 x 67.427 x 1 mm )

G21 G40 G54

G80 G90 G94

( Tool #2 "Basic Cutter" / Diameter 3 mm )

T2 M06

M03 S12000

M07

G00 X2.377 Y-3.239

G00 Z0

G01 F60 Z-1

G01 F300 X-75.223

G01 Y61.981

G01 X2.377

G01 Y-3.239

G00 Z2

M09

M05

M02

%





# Result

Thus the Gerber File into G-Code using Copper CAM.
