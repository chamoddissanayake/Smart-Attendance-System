
# Smart Attendance System

The Smart Attendance project utilizes computer vision and facial recognition to automate attendance tracking. By capturing real-time video feed, it identifies individuals from a preloaded database of images. When a match is found, the system marks their attendance in a CSV file, recording the time and date. This efficient approach reduces manual attendance processes, enhances accuracy, and provides a modern solution for educational institutions and workplaces seeking to streamline attendance management.

## Run Locally

Clone the project

```bash
  git clone https://github.com/chamoddissanayake/Smart-Attendance-System.git
```

Install dependencies

```bash
  pip install -r requirements.txt
```

If your device have more than single camera provide the relevant camera id in here
```bash
cap = cv2.VideoCapture(0)
```

Start the Application

```bash
  python AttendanceProject.py
```


## Tech Stack

**Programming Language:** Python

**Libraries:**

* OpenCV: For image processing and video capture.
* NumPy: For numerical operations and array handling.
* face_recognition: For facial recognition and encoding.

**File Handling:** CSV for attendance logging.

**Hardware:** Webcam for capturing real-time video.