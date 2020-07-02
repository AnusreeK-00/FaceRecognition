# FaceRecognition
Built using dlib's state-of-the-art face recognition built with deep learning. The model has an accuracy of 99.38% on the Labeled Faces in the Wild benchmark.  This also provides a simple face_recognition command line tool that lets you do face recognition on a folder of images from the command line!<br>
<h4>Steps:</h4> <br>
pip install cmake<br>
pip install face_recognition<br>
pip install numpy<br>
pip install dlib<br>
pip install opencv-python<br><br>

Create a folder called known_people (make sure this is in the same directory as recognize_face.py).<br>
Now we can add pictures of people we wish to identify by saving an image of their face in the known_people folder. Make sure the person is facing forwards and is the only person in the photograph (crop if necessary). We name each file as the person’s name, as we wish it to appear on screen. In this case, only the .jpg files will be used.<br>

<h4> To run the program:</h4>
Run the recognize_face.py file in the terminal or cmd using appropriate commands.
