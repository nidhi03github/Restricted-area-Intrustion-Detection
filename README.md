# Restricted-area-Intrustion-Detection
Detect if anyone is near a restricted working space and trigger an alarm.
To monitor the Restricted area add vedio of location to be monitored in place of sample lunch vedio.
The process will create its own dataset of faces detected . The dataset so obtained is then used for training the model. Whenever a new face is detected the process rings alarm and generate in vedio runtime names of identified faces.
The system use vedio from internet and names of actors present in vedio.The company can provide vedio of its restricted area.
the files to be run in following order
1)recognize_face_vedio.py
2)encoding_faces.py
3)recognize_faces_images
4)serach_bing_api.py
5)recognize_faces_vedio_file.py
