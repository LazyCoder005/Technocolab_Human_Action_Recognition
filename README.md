# Technocolab_Human_Action_Recognition


Human activity recognition, or HAR for short, is a broad field of study concerned with identifying
the specific movement or action of a person based on sensor data.

Movements are often typical activities performed indoors, such as walking, talking, standing, and sitting. 
They may also be more focused activities such as those types of activities performed in a kitchen or on a factory floor.

The sensor data may be remotely recorded, such as video, radar, or other wireless methods.
Alternately, data may be recorded directly on the subject such as by carrying custom hardware or smart phones that have accelerometers and gyroscopes.

We will discover the problem of human activity recognition and the deep learning methods that are achieving state-of-the-art performance on this problem.

  - Activity recognition is the problem of predicting the movement of a person, often indoors, based on sensor data, such as an accelerometer in a smartphone.
  - Streams of sensor data are often split into subs-sequences called windows, and each window is associated with a broader activity, called a sliding window approach.

  - Convolutional neural networks and long short-term memory networks, and perhaps both together, are best suited to learning features from raw sensor data and predicting the       associated movement

### Download APK From here : https://drive.google.com/file/d/19DA17kL2Zs11xNyYkrR5jTcRLIlkrh0z/view?usp=sharing

## About Dataset: 

We are using Kinetics Dataset and Classifying the type of activities amongst 11 categories:

- Breakdancing
- Calligraphy
- Celebrating 
- Claypotterymaking
- Climbingarope
- Cookingoncampfire
- Eatingicecream
- Golfdriving
- Pushup
- Raisingeyebrows
- Ridingscooter

## MODEL STRUCTURE

 ![model_structure_plot](https://github.com/LazyCoder005/Technocolab_Human_Action_Recognition/blob/main/Model_arc.png)
 
 
 ## DEPLOYMENT 🍎

The project was deployed using an android studio. where the designed model was uploaded in other to predict the human actions either by uploading an image/video or real time video detection.
![image](https://user-images.githubusercontent.com/72225471/139593109-4d459a74-b54e-4c0e-a03e-035025f024fb.png)

