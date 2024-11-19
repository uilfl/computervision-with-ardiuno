# How to Run This Project

## Prerequisites

- Python 3.9

### libraries :

- cvzone
- pyfirmata2
- mediapipe
- handdetector

## Steps to Run

1. **Activate the Virtual Environment**

   ```bash
   source arduino_env/bin/activate
   ```

2. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Project**
   ```bash
   python new.py
   ```

Make sure you have Python 3.9 installed and set up before running these commands.

## Using Arduino with Standard Firmata

1. **Upload Standard Firmata to Arduino**

   - Open the Arduino IDE.
   - Go to `File` > `Examples` > `Firmata` > `StandardFirmata`.
   - Select your Arduino board and port from the `Tools` menu.
   - Click the upload button to upload the Standard Firmata sketch to your Arduino board.

2. **Connect Arduino to Your Project**

   Ensure your Arduino is connected to your computer via USB. The project will communicate with the Arduino using the pyfirmata2 library.

3. **Run the Project with Arduino**

   ```bash
   python new.py
   ```

Your Arduino should now be ready to interact with the project.
