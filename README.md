# Structure of files and folders
vehicle_counting_and_speed_track/input
vehicle_counting_and_speed_track/output
vehicle_counting_and_speed_track/YOLO
vehicle_counting_and_speed_track/main.py
vehicle_counting_and_speed_track/sort.py

# note
| coco.names | yolov3.cfg | yolov3.weights | need to be inside YOLO folder
 
# to run the code follow this
python main.py -input 'path/input' -output 'path/output' -yolo 'path/YOLO'
# if the command didn't work use this
python main.py -i 'path/input' -o 'path/output' -y 'path/YOLO'
