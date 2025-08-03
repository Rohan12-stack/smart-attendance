# Face Recognition Based Attendance System
![Project Screenshot](SAS.jpeg)
Rohan.B  1RVU22BSC082  
Gunashree.R  1RVU22BSC032

This project is a face recognition-based Smart Attendance System developed using Python and OpenCV. Initially, the system registers a user by capturing their facial image and associating it with their name. During subsequent logins, it automatically detects and recognizes the face using pre-trained models, then logs the attendance data into an Excel sheet with the timestamp. The project eliminates the need for manual attendance, ensuring greater accuracy and efficiency, especially useful in academic or office environments. It demonstrates proficiency in computer vision, facial recognition techniques, and real-time data logging.

## Installation

1. Clone the repository to your local machine. ``` git clone: https://rohan12-stack.github.io/smart-attendance/ ```
2. Install the required packages using ```pip install -r requirements.txt```.

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.





