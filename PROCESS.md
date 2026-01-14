# Adaptive Traffic Lights Project - Setup and Run Instructions

## Prerequisites
- **Python:** Version 3.8 or higher (download from https://www.python.org/downloads/)
- **Git:** For cloning the repository (download from https://git-scm.com/downloads)
- **Web Browser:** Chrome, Firefox, or Edge
- **Operating System:** Windows 10/11, Linux, or macOS
- **Hardware:** Minimum 4GB RAM recommended

## Quick Setup and Run

### 1. Clone the Repository
```
git clone https://github.com/your-username/Adaptive-Traffic-Lights-main.git
cd Adaptive-Traffic-Lights-main
```

### 2. Install Dependencies
```
pip install -r requirements.txt
```
**Note:** This installs Flask, TensorFlow, OpenCV, Pygame, and other required libraries. May take 5-10 minutes.

### 3. Run the Web Application
```
python web_app.py
```

### 4. Access the Application
- Open your web browser
- Navigate to `http://localhost:5000`
- The web interface will load with the backend simulation connected

## Alternative: Run Simulation Only
```
python simulation.py
```
This runs the traffic simulation without the web interface.

## Project Features
- Real-time traffic simulation with adaptive signal control
- Vehicle detection using YOLO computer vision
- Web dashboard for monitoring and analytics
- City insights and awareness campaigns

## Troubleshooting
- **Port 5000 in use:** Change port in `web_app.py` or stop other services using port 5000
- **Installation issues:** Ensure Python is added to PATH during installation
- **TensorFlow errors:** Try `pip install tensorflow==2.8.0` for compatibility
- **Camera not available:** Simulation works with sample data
- **Permission errors:** Run command prompt as Administrator

## Quick Start (Windows)
Use the included `run.bat` file by double-clicking it, or create one with:
```batch
pip install -r requirements.txt
python web_app.py
```

The project should run smoothly once dependencies are installed.
