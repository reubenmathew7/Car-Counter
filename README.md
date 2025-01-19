 To run this project, ensure you have Python installed and the required libraries. Install the dependencies using the requirements.txt file provided in the repository.

Why I Built This Project
The primary motivation behind this project was to learn and implement object detection techniques using state-of-the-art tools like YOLOv8. 
As someone passionate about robotics and automation, I recognize the importance of object detection in enabling machines to perceive and interact with their environment.

Goals:
Skill Development: To gain hands-on experience with computer vision, object detection, and tracking algorithms.
Future Applications: To prepare myself for future projects in robotics, such as autonomous vehicles, robotic arms, or smart surveillance systems.
Understanding Real-World Challenges: To explore how object detection models perform in real-world scenarios like traffic monitoring and learn how to optimize them for better accuracy and efficiency.
This project represents an important step in my journey toward mastering robotics and AI technologies. By building this system, I have not only improved my 
technical skills but also gained insights into practical challenges like handling noisy data, optimizing performance, and integrating multiple algorithms. 

What This Project Does

This project is a vehicle counter and tracker that detects vehicles in a video feed, tracks their movement, and counts them as they cross a predefined line. It uses YOLOv8 for object detection and the SORT algorithm for tracking.
Features:
Detects vehicles such as cars, trucks, buses, and motorbikes.
Tracks each vehicle across frames.
Counts vehicles passing a specific line on the road.
Displays bounding boxes, unique IDs, and the count of vehicles on the video feed.

How It Works

Input Video: The program processes either a live camera feed or a pre-recorded video file.
Mask Application: A mask image is applied to focus on the region of interest.
Object Detection: YOLOv8 detects objects in each frame of the video.
Tracking: The SORT algorithm assigns unique IDs to detected objects and tracks them across frames.
Counting Logic: Vehicles crossing a predefined line are counted, ensuring no duplicates.

Results
The program outputs:
A live video feed with:
Bounding boxes around detected vehicles.
Unique IDs assigned to each tracked vehicle.
A displayed count of vehicles that have crossed the line.

Credits
This project was inspired by and built with the help of this YouTube video https://www.youtube.com/watch?v=WgPbbWmnXJ8&t. 
The course provided valuable insights into using YOLOv8 for object detection and tracking, which I adapted and extended to create this vehicle counter.
