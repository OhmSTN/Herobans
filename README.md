<!DOCTYPE html>
<html>
<head>
    <title>SITTINON REUNGVISED</title>
    <style>
        .title-bar {
        	border-radius: 19px;
            background-color: #0078D7; /* Blue title bar background color (macOS-like) */
            color: white; /* Title bar text color */
            padding: 8px;
            -webkit-app-region: drag; /* Make the title bar draggable */
            display: flex;
            justify-content: space-between;
            align-items: center;
             box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        .title {
            font-size: 18px;
            font-weight: bold;
            margin: 0;
            padding: 0;
            align-items: center;
        }
        .window-controls {
            display: flex;
            gap: 5px;
        }
        .window-control {
            width: 16px;
            height: 16px;
            background-color: #FF5F56; /* Close button color (red) */
            border-radius: 50%;
            cursor: pointer;
            -webkit-app-region: no-drag; /* Prevent dragging for window controls */
            
        }
        .window-control.minimize {
            background-color: #FFBD2E; /* Minimize button color (yellow) */
        }
        .window-control.expand {
            background-color: #28C940; /* Expand button color (green) */
        }
        .command-code {
            background-color: #333; /* Dark command code background color */
            color: #00ff00; /* Bright green font color */
            font-family: 'Pixel', sans-serif; /* 8-bit pixel font */
            padding: 720px;/* Dark command code background color *//* Dark command code background color *//* Dark command code background color */
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.6);
            white-space: pre;
            position: relative;
            
        }
        .typing-symbol {
            position: absolute;
            top: 3%;
            left: 0;
            transform: translateY(-50%);
            width: 8px;
            height: 16px;
            background-color: #00ff00; /* Bright green typing symbol color */
            animation: blink 1s step-start 0s infinite;
        }
        @keyframes blink {
            50% {
                background-color: transparent;
            }
        }
        .user-form {
            background-color: #333; /* Dark form background color */
            color: #00ff00; /* Bright green font color */
            font-family: 'Pixel', sans-serif; /* 8-bit pixel font */
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .form-label {
            font-size: 16px;
            display: block;
            margin-bottom: 10px;
        }
        .form-input {
            font-size: 14px;
            padding: 5px;
            width: 100%;
            margin-bottom: 15px;
        }
        .form-button {
            background-color: #FF5F56; /* Red button color */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
    <style type="text/css" media="screen">
        @font-face {
            font-family: 'Pixel';
            src: url('pixel-font.woff2') format('woff2');
        }
    </style>
    <script>
        function closeWindow() {
            window.close();
        }

        function minimizeWindow() {
            // Minimize the window (you can implement this functionality if needed).
        }

        function expandWindow() {
            // Maximize or restore the window (you can implement this functionality if needed).
        }
    </script>
</head>
<body>
    <div class="title-bar">
      <h1 class="title"></h1> 
        <div class="window-controls">
            <div class="window-control" onclick="minimizeWindow()"></div>
            <div class="window-control expand" onclick="expandWindow()"></div>
            <div class="window-control" onclick="closeWindow()"></div>
        </div>
    </div>
    <div class="command-code">
        <style>
            img {
              border-radius: 30%;
            }
            </style>
        <pre><div class="typing-symbol">   <img src="https://media.licdn.com/dms/image/D5635AQH2OvnnETWWBQ/profile-framedphoto-shrink_200_200/0/1696081877077?e=1699430400&v=beta&t=08jNRFMdZsVEnoPbguggfD3Q6qSB9K3HT9FB7tW6YH4" width="150" > </br></br>    SITTINON REUNGVISED [OHM]</br>
    AUTOMATION ENGINEER & SOFTWARE ENGINEER 
    Pathum Thani, Pathum Thani, Thailand
     
    Education : Bachelor of Engineering (Instrument & Automation Engineering)
                King Mongkut's University of Technology North Bangkok

    --------------------------------------------------------------------------------------------------------           
    
    Personal skills 
     
    [ PLC & HMI ]
     - MISUBISHI | Fx-series , Q-series , R-series , L-series , Fx5-Series , A-Series | Level = Advance
     - Allen-Bradley , Rockwell Automation | Level = Intermediate
     - Omron | Level = Intermediate
    - Delta | Level = Intermediate
    [ Microcontroller & Embedded computing]
     - Arduino IDE (All device programming by Arduino IDE) | Level = Advance
     - Micropython | Level = Intermediate
     - RasberryPI | Level = Intermediate
    [ Programming ]
    - C# , Vb.net | Level = Intermediate
    - HTML + PHP | Level = Intermediate
    - SQLi , MySQL , ManiaDB | Level = Intermediate
    - Python | Level = Intermediate
    - Script programming | Level = Intermediate   
    
    --------------------------------------------------------------------------------------------------------

    Past Projects   

    [ Electrical diagram & PLC Programming ] 
    - Robot vision inspection
    - Servo press , Hydraulic press machine 
    - Leak tester machine 
    - IC Welding machine 
    - Electronic parts assembly line 
    - Pick & Place parts machine , Auto loader parts machine
    - Robot loader parts , assembly parts 
    - Camera inspection machine
    - Nut-runner , Screw tightening, Feeder 
    - Dross cart transfer 
    - Autoload CNC , Deburring Machine
    - Clamp connector machine 
    - Terminal welding machine
    - Conveyor Loader buffer for robot
    - Palletizer machine pick & place
    - Autoloader for injection mold 
    - Performance tester machine 
    - Datalogging system for assembly line
    - O-ring Assembly machine
    - Automatic Matherial selector control system 

    [ Special automation device ]
    - IAI Robo cylinder , Smc electric cylinder
    - Robot 6-Axis , Scara , Cobot | (Denso,Universal Robot) 
    - Linear servo motor (magnet drive) , Servo motor , Stepping
    - Servo press , Nut-runner , Elec screw driver ,Feeder (DDK,Desoulter,Nitto,IAI)
    - Laser marking (Panasonic,Keyence)
    - Camera inspection (Keyence , Cognex , Omron)
    - Spot welding controller & Welding checker (Amada)
    - Electronic parts tester (Hikoki,Mitutoyo) 
    - Air Leak tester (Cosmo)
    - Linear gauge transducer (Keyence)
    - Oil apply controller

    [ Software computer programming ] 
    - IOT Gateway (Controller to Microsoft share point)
    - Inspection viewer (PLC Communication with PC)
    - PCB Reverse to circuit (convert PCB picture to EAGLE file for edit)
    - Motor DC Control application 
    - Control panel for plant control
    - Business website (PHP responsive site) 
    - Parts manage system (PHP + Sql)
    - Invoice system (PHP + Sql)
    - DJ Live sound effect (Vb.NET) 

    [ PCB Design ]
    - Motor DC Driver Dual Mosfet 48V 
    - Amplifier for sensor thru-beam 
    - Level controller
    - Smart watts-hours meter
       
        </pre>
    </div>
    </div>
  
</body>
</html>
