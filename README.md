🏐 AVP Video Tracking
AVP Video Tracking is a Python-based application designed to track volleyball players on the court during gameplay. Inspired by the groundbreaking work being done by BallTime AI, this project leverages machine learning and computer vision to analyze and visualize players' positions in real time.

What It Does
AVP Video Tracking processes video footage of volleyball games to detect and track players' movements on the court. The application uses YOLOv8 to identify players and analyze their positioning during gameplay.

Key features include:

Player Detection: Identifies players within the video and tracks their movements.
Court Tracking: Determines whether players are on the near or far side of the volleyball court.
Mini-Court Visualization: Mirrors player positions on a smaller, simplified court for visual analysis.
How to Use It
Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/AVP-Video-Tracking.git
cd AVP-Video-Tracking
Install Dependencies
bash
Copy code
pip install -r requirements.txt
Run the Python Script
bash
Copy code
python volleyball_tracker.py
Analyze Player Movements
Provide a video file of a volleyball match, and the AI will detect and track players on the court, generating an output video that showcases the player tracking.

Demo Video
Check out this demo video to see the app in action.

(Insert video link or embed here)

Medium Article
COMING SOON!

Repository Contents
volleyball_tracker.py: The main application script.
requirements.txt: Dependencies needed to run the app.
