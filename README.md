# Animal-Intrusion-Detection-in-Farms-using-OpenCV
This project is aimed at detecting animal intrusion in farms using OpenCV. It tracks any moving objects in the camera's field of view and sends a notification with the pictures to the farm owner through WhatsApp. The system utilizes Selenium to automate WhatsApp Web login and message sending.

## Features
- **Movement Detection:** Detects any moving objects in the farm.
- **WhatsApp Notification:** Automatically sends pictures of detected objects to the farm owner.
- **Selenium Automation:** Uses Selenium for automating WhatsApp login and message sending.
- **Future Improvement:** Currently detects any moving objects, but can be further improved to detect only animals.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Animal-Intrusion-Detection-Farm.git
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
## Usage
1. Run the detection script:**
   ```bash
   python cc.py
   ```
2. **Login to WhatsApp Web using Selenium:** The script will open WhatsApp Web in a browser where the owner needs to log in.
3. **Monitor the farm:** The system will start detecting moving objects and send pictures to the farm owner via WhatsApp when an object is detected.

## Requirements
- Python 3.x
- OpenCV
- Selenium
- WhatsApp Web

## Future Improvements
Modify object detection to filter only animals using techniques like:
- Pre-trained animal detection models
- Object classification based on size and shape
- YOLO or TensorFlow object detection API

## Contributions
Feel free to open an issue or submit a pull request if you have any ideas or improvements.
