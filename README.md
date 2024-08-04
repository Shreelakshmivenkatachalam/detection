Introduction
This project focuses on detecting vehicles in images and videos using Python.<br> The main objective is to accurately identify and count the number of vehicles present in the given media.<br> This can be useful in various applications such as traffic monitoring, congestion analysis, and automated toll systems.<br>

Features<br>
Vehicle detection in images and videos<br>
Pre-trained model for quick setup<br>
Customizable parameters for detection<br>
Detailed results including bounding boxes and counts<br>
Installation<br>
Clone the repository:<br>


git clone https://github.com/Shreelakshmivenkatachalam/detection.git<br>
cd detection<br>
Create a virtual environment and activate it:<br>

python -m venv venv<br>
source venv/bin/activate   # On Windows: venv\Scripts\activate<br>
Install the required packages:<br>

pip install -r requirements.txt<br>
Usage<br>
To detect vehicles in an image:<br>

python detect_vehicles_image.py --input /path/to/your/image.jpg --output /path/to/save/output.jpg<br>
To detect vehicles in a video:<br>

python detect_vehicles_video.py --input /path/to/your/video.mp4 --output /path/to/save/output.mp4<br>
Adjust detection parameters:<br>
You can customize various parameters such as confidence threshold, model configuration, and more in the respective scripts.<br>
Results<br>
Example results of vehicle detection in images and videos can be found in the examples directory. These include detected vehicles with bounding boxes and counts.<br>
