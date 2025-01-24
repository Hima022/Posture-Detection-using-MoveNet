# Posture-Detection-using-MoveNet
Posture detection plays a critical role in applications such as fitness tracking, ergonomic assessment, and rehabilitation. Traditional methods for posture evaluation often demand intricate hardware setups and specialized software, posing challenges for broad adoption. This project introduces MoveNet, a cutting-edge machine learning model designed to serve as the core of a real-time posture detection system. MoveNet efficiently estimates human poses using a single camera, identifying key boy landmarks with high precision. Tensor Flow Lite powers the system and leverages Python for real-time processing in machine learning applications, ensuring cross-platform compatibility without the need for specialized hardware. By providing accurate posture detection and feedback on body alignment, MoveNet demonstrates adaptability to a wide array of use cases, including fitness coaching, rehabilitation exercises, and ergonomic monitoring.
PROPOSED METHODOLOGY:
This project uses TensorFlow Lite and MoveNet Lightning to construct a real-time posture detection system. Using OpenCV, live video from a camera is captured, and each frame is preprocessed and resized before sending them into the MoveNet model. The model's rendering of important body landmarks on the live video feed shows the user's posture. The posture detection and visualization system is provided with accuracy by establishing linkages between body components based on a confidence threshold. The project is quite flexible since it makes effective use of TensorFlow Lite to allow real-time processing even on low-power devices. This posture recognition system can be utilized for a variety of tasks, such as fitness tracking, rehabilitation activities, and ergonomic assessments because it functions flawlessly across platforms.
PSEUDO CODE:
1. Bring in required libraries, such as Mediapipe, NumPy, and OpenCV.
2. Resize a picture or video frame before displaying it.
3. Set up the pose detector and sketching tools in Mediapipe.
4. Loop over live camera input or video frames:
5. Adjust the frame's size.
6. To find pose landmarks, use Mediapipe.
7. Draw the identified landmarks on a white background as well as the original frame.
8. Show both the blank image with pose landmarks and the original frame with landmarks.
9. When the video stops or a termination key is pushed, the loop will stop.
![image](https://github.com/user-attachments/assets/2ee30b47-ab20-424d-a7b9-d615e37771f6)

