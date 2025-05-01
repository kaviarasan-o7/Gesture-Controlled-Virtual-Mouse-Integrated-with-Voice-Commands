# Gesture-Controlled-Virtual-Mouse-Integrated-with-Voice-Commands  
A machine learning project that allows users to control a system or laptop via hand gestures and voice commands, eliminating the need for physical input devices like a keyboard or mouse. The tool uses state-of-the-art computer vision algorithms and machine learning models to enable gesture-based interaction.

## **Features**  
- Control the system's cursor using hand gestures, such as moving, clicking, and scrolling.  
- Integrates voice commands for additional system control.  
- Supports interaction with applications via predefined gestures and voice commands.  
- Built with a focus on providing a hygienic, touch-free computing environment.

## **Technologies Used**  
- **Python**: For algorithm implementation and control logic.  
- **OpenCV**: For image processing and hand detection.  
- **MediaPipe**: For accurate hand landmark detection.  
- **PyAutoGUI**: For simulating mouse and keyboard events.  
- **pycaw**: For controlling system volume through voice commands.  
- **screen_brightness_control**: For controlling screen brightness via gestures and voice.  

## **Setup Instructions** 
1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/xenon-19/Gesture-Controlled-Virtual-Mouse.git  
   ```  
   *(For detailed information on cloning, visit [GitHub Documentation](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository))*  

2. **Create and activate the virtual environment:**  
   ```bash  
   conda create --name gest python=3.8.5  
   conda activate gest  
   ```  

3. **Install dependencies:**  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Install additional packages:**  
   ```bash  
   conda install PyAudio  
   conda install pywin32  
   ```  

5. **Navigate to the project directory:**  
   ```bash  
   cd path_to_repository/Gesture-Controlled-Virtual-Mouse/src  
   ```  

6. **Run the Application:**  
   - **For Voice Assistant + Gesture Recognition:**  
     ```bash  
     python Proton.py  
     ```  
     *(Enable Gesture Recognition using the voice command: "Proton Launch Gesture Recognition")*  

   - **For Gesture Recognition Only (Without Voice Assistant):**  
     - Uncomment the last 2 lines of code in the `Gesture_Controller.py` file.  
     - Then run:  
     ```bash  
     python Gesture_Controller.py  
     ```  
