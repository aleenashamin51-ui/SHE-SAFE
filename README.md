<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# SHE SAFE 🎯

## Basic Details

### Team Name: CTRL+EXPERIENCE

### Team Members
- Member 1: ALEENA R SHAMIN - MAR BASELIOS COLLEGE OF ENGINEERING AND TECHNOLOGY
- Member 2: DIYA A - MAR BASELIOS COLLEGE OF ENGINEERING AND TECHNOLOGY

### Hosted Project Link
https://mug-fun-69135483.figma.site/


### Project Description
[WEBSITE FOR WOMEN SAFETY AND OTHER SAFETY RELATED ISSUES.USING AI INTEGRATED WEB

### The Problem statement
WOMEN FACE SAFETY ISSUES WHICH REQUIRE IMMEDIATE RESPONSE AND ACTION INSTEAD OF WAITING FOR A LONG CALL

### The Solution
OUR WEBSITE INTEGRATES AI ALSO AND PROVIDES SENSOR AND DETECTION FOR PREVEVNTION

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: [e.g.,HTML]
- Frameworks used: [e.g., React, Django, Spring Boot]
- Libraries used: [e.g., axios, pandas, JUnit]
- Tools used: [e.g., VS Code, Git, Docker]

**For Hardware:**
- Main components: [List main components]
- Specifications: [Technical specifications]
- Tools required: [List tools needed]

---

## Features

List the key features of your project:
- Feature 1: ALERT PAGE:FOR RISK ALERTS
- FEATURE 2:DEFENCE MODE:AI INTEGRATED TOOLS
- SMART MAP:FOR LOW RISK AREAS
- ANALYTICS:GRAPH AND PLOTS BASED ON SAFETY ISSUES

---

## Implementation

### For Software:

#### Installation
```bash
[Installation commands - e.g., npm install, pip install -r requirements.txt]
```

#### Run
```bash
[Run commands - e.g., npm start, python app.py]
```

### For Hardware:

#### Components Required
[List all components needed with specifications]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/1e33beb7-dff4-41ef-8c05-cb6f92bb9034" />
ALERT PAGE:Based on crimes,alerts r provided for each area with percentage.


![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/37923684-ae19-4a32-9d0c-b5828a848280" />
smart map
for showing least risky areas and fastest distances for convenience and time


![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/594a5a32-5e54-484c-8a63-0b56a4e1deb4" />
ai integrated defense mode tools

#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`
https://mug-fun-69135483.figma.site/smart-map

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>SheSafe Dashboard</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
:root{
  --primary:#5E17EB;
  --safe:#10B981;
  --alert:#FF4D4D;
  --accent:#14B8A6;
  --bg:#F8F9FB;
  --glass: rgba(255,255,255,0.6);
}

*{margin:0;padding:0;box-sizing:border-box;font-family:'Inter',sans-serif;}
body{background:var(--bg);display:flex;min-height:100vh;color:#111;}

.sidebar{
  width:240px;
  background:linear-gradient(180deg,#5E17EB,#7B3FF2);
  color:white;
  padding:32px 16px;
  display:flex;
  flex-direction:column;
  gap:24px;
}

.sidebar h2{font-weight:700;}
.nav-item{
  padding:12px 16px;
  border-radius:16px;
  cursor:pointer;
  transition:0.3s;
}
.nav-item:hover{
  background:rgba(255,255,255,0.15);
}

.main{
  flex:1;
  padding:32px;
}

.glass{
  background:var(--glass);
  backdrop-filter:blur(20px);
  border-radius:24px;
  padding:24px;
  box-shadow:0 8px 32px rgba(0,0,0,0.08);
}

.header{
  display:flex;
  justify-content:space-between;
  margin-bottom:24px;
}

.risk-meter{
  width:200px;
  height:200px;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:24px;
  font-weight:700;
  background:conic-gradient(
    #10B981 0% 30%,
    #FFC107 30% 60%,
    #FF4D4D 60% 100%
  );
  margin:24px auto;
}

.risk-inner{
  width:150px;
  height:150px;
  background:white;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
}

.sos-btn{
  display:block;
  margin:32px auto;
  padding:16px 40px;
  border-radius:50px;
  border:none;
  font-size:18px;
  font-weight:600;
  color:white;
  background:linear-gradient(135deg,#FF4D4D,#FF7A7A);
  box-shadow:0 0 30px rgba(255,77,77,0.6);
  cursor:pointer;
  transition:0.3s;
}
.sos-btn:hover{
  transform:scale(1.05);
}

.map-placeholder{
  height:300px;
  border-radius:24px;
  background:linear-gradient(135deg,#d9d9d9,#c4c4c4);
  margin-bottom:24px;
}

.route-card{
  padding:16px;
  border-radius:16px;
  margin-bottom:16px;
  display:flex;
  justify-content:space-between;
}

.safe-route{background:#E6F9F1;}
.fast-route{background:#FFF4E5;}

.defense-mode{
  background:#111;
  color:white;
  min-height:100vh;
  padding:32px;
}

.toggle-card{
  padding:16px;
  border-radius:16px;
  margin-bottom:16px;
  background:#1E1E1E;
  display:flex;
  justify-content:space-between;
}

.badge{
  background:#FF4D4D;
  padding:4px 12px;
  border-radius:20px;
  font-size:12px;
}

/* Mobile */

.mobile-nav{
  display:none;
}

@media(max-width:768px){

.sidebar{display:none;}

.mobile-nav{
  position:fixed;
  bottom:0;
  left:0;
  width:100%;
  background:white;
  display:flex;
  justify-content:space-around;
  padding:12px;
  border-top-left-radius:24px;
  border-top-right-radius:24px;
  box-shadow:0 -4px 20px rgba(0,0,0,0.1);
}

.floating-sos{
  position:fixed;
  bottom:40px;
  left:50%;
  transform:translateX(-50%);
  width:70px;
  height:70px;
  border-radius:50%;
  background:linear-gradient(135deg,#FF4D4D,#FF7A7A);
  display:flex;
  align-items:center;
  justify-content:center;
  color:white;
  font-size:24px;
  box-shadow:0 0 25px rgba(255,77,77,0.7);
}

}

</style>
</head>
<body>

<div class="sidebar">
  <h2>SheSafe</h2>
  <div class="nav-item">Home</div>
  <div class="nav-item">Smart Map</div>
  <div class="nav-item">Defense Mode</div>
  <div class="nav-item">Community</div>
  <div class="nav-item">Insights</div>
</div>

<div class="main">

  <div class="header">
    <div>
      <h1>Good Evening</h1>
      <p>📍 Kochi, Kerala</p>
    </div>
  </div>

  <div class="glass">
    <div class="risk-meter">
      <div class="risk-inner">48</div>
    </div>
    <p style="text-align:center;font-weight:500;">
      Area Risk: Moderate – 48/100
    </p>

    <div class="glass" style="margin-top:24px;">
      <h4>Why?</h4>
      <ul style="margin-top:12px;line-height:1.8;">
        <li>Low lighting</li>
        <li>Late hour</li>
        <li>Low crowd density</li>
      </ul>
    </div>

    <button class="sos-btn">SOS Emergency</button>
  </div>

  <br><br>

  <div class="glass">
    <h2>Smart Map</h2>
    <div class="map-placeholder"></div>

    <div style="margin-bottom:16px;">
      <button>Safe Route</button>
      <button>Fast Route</button>
      <button>Women Safe Zones</button>
    </div>

    <div class="route-card safe-route">
      <div>Safest – Risk 22%</div>
      <div>14 mins</div>
    </div>

    <div class="route-card fast-route">
      <div>Fastest – Risk 48%</div>
      <div>9 mins</div>
    </div>
  </div>

  <br><br>

  <div class="defense-mode">
    <h2>Defense Mode</h2>

    <div class="toggle-card">
      <span>Anti-Stalker Mode</span>
      <span class="badge">Protection Active</span>
    </div>

    <div class="toggle-card">
      <span>Stealth SOS</span>
    </div>

    <div class="toggle-card">
      <span>Fake Call Generator</span>
    </div>

    <div class="toggle-card">
      <span>Auto Evidence Recording</span>
    </div>

    <div class="toggle-card">
      <span>Voice AI Detection</span>
    </div>

  </div>

</div>

<div class="mobile-nav">
  <div>Home</div>
  <div>Map</div>
  <div>Defense</div>
  <div>Community</div>
  <div>Insights</div>
</div>

<div class="floating-sos">SOS</div>

</body>
</html>
[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
