# Love Function Generator
This is a Python program that generates a heart-shaped image using a mathematical function. The program uses the tkinter module to create a canvas and draw the heart.

## How to Run
To run the program, simply execute the run() function in the code. This will launch a full-screen window displaying the heart-shaped image.

## How it Works
The heart is generated using a mathematical function that takes a parameter t and returns the x and y coordinates of a point on the heart. The program then scatters points inside the heart and applies a jitter effect to create a more natural look. Finally, the program renders the heart on a canvas using the tkinter module.

## Customization
You can customize the size and angle of the heart by adjusting the shrink_ratio parameter in the heart_function function. You can also adjust the intensity of the scattering effect by changing the beta parameter in the scatter_inside function.

## License
This program is licensed under the MIT License. Feel free to use and modify the code as needed.