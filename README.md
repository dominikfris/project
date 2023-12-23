# Python square detection script
#### Video Demo: https://www.youtube.com/watch?v=V8zIDu9oE3A
#### Description: 
This Python script uses OpenCV for real-time square detection with camera. 
It defines functions to find and draw squares based on edge detection and contour analysis. The find_squares function filters squares by area, and draw_squares outlines them, changing color and providing a notification if exactly three squares are detected. The script includes a Tkinter GUI for user input on starting a simulation.
The main loop captures video frames, performs square detection, and displays results until the user presses 'q'. The optional Tkinter window asks the user if they want to start the simulation. The script showcases a simple computer vision application with interactive elements for square detection in real-time.
