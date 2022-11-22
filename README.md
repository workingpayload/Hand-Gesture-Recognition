# Hand-Gesture-Recognition
College mini project.
We perform Hand Gesture Recognition, making use of Google's Mediapipe framework in python, without any physical aid being affixed to hands.
MediaPipe offers customizable ML solutions. Mediapipe Hands is a hand and finger tracking solution. It works by deducing 21 3D landmarks of a hand. For which the pipeline consists of two modules: a palm detection model after that a hand landmark model. The palm detector achieves an average precision of 95.7%. The hand detector performs keypoint localization of all 21 hand-knuckle coordinates in the detected hand regions provided by palm detector employing regression.
We capture live video feed from camera using opencv library then pass it to Mediapipe that returns the landmarks' details. Afterwards we operate on those landmarks to implement several trivial use cases. By computing relative positioning, distance among landmarks, linear alignment we implement virtual mouse, finger counter, volume controller, rock-paper-scissors game. The required GUI is brought about using opencv.

![Tracking](https://user-images.githubusercontent.com/48465143/203244043-af4e9f5a-74bb-4c3f-94f9-edcf9e1887f4.png)
