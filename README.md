# Face-Detective
Have you ever wondered what happens outside your front door when you are out at work or in your room? Did your creepy neighbor steal your last amazon package, or the delivery guy never showed up? Is your ex-girlfriend stalking you? Is the government spying on you? At some point in our living, we have all asked this question. Wouldn’t it be great if something notified us of all the happening when we are not in front of the front door? Well, this project is all about making your own face detective giving you all information of the happening. On a very high level, this project will take live video as an input which is passed through a face detection and face identification algorithm that uses neural network to process the face and send text notification when a face is not identified.

The setup of the project will have a Logitech webcam mounted on top of two motors put together with the help of metal holders. The motors will be able to move up to a range of 180 degrees; one will move the camera horizontally and another vertically. Given the cameras wide range of 180 degrees, the setup will let the camera have a range of 270 degrees. Initially, the camera will move horizontally scanning the video for faces. The movement will only stop when a face is detected. When the face is detected, it is then passed through a neural network with back propagation property which was trained to identify the face in the frame. If the face is identified, then a check is performed on the user. If the face is one of the targets, the detective will take the face as a nonuser i.e. a text alert with a picture of the face will be sent to the user. Additionally, the face will be tracked with the help of motors, now horizontally and vertically, until the face goes out of range. It will only recognize one face.

Further, the user will also be able to add new friendly faces to the system. The user will be allowed to upload pictures and the training of the neural network to identify the face will be automated. The adding of the faces is also automated now with automated picture taking script to take 100 face pictures. The identified face will be recognized later by the system. A new feature to target the user is provided to target a known user who is already recognized by the system.
