# Dice Rolling Simulator

## Description
The Dice Rolling Simulator is a simple Python project that uses Tkinter for the GUI and PIL for handling images. This application allows the user to simulate rolling a dice by clicking a button, displaying a random dice face each time.

## Algorithm Description
1. **Setup the Main Window**: Initialize the Tkinter root window with a specified size and title.
2. **Add Labels**: Add a label for displaying a welcome message.
3. **Load Images**: Load the dice face images and store them in a list.
4. **Display Initial Image**: Display an initial random dice face on the window.
5. **Define the Rolling Function**: Define a function to update the displayed dice face with a new random image when the button is clicked.
6. **Add Button**: Add a button that calls the rolling function when clicked.
7. **Run the Application**: Start the Tkinter main loop to keep the window open and responsive.

## How to Execute
1. install the visual studio code according to your system through https://code.visualstudio.com/download
2. install the python latest version from https://www.python.org/downloads/
3. Install the prerequisites/software’s required to execute the code
4. Save the script and ensure the dice images are in the correct directory as specified in the code.

## Issues Faced
- **Image Path Issues**: Ensuring the correct path for dice images was crucial. Absolute paths were used to avoid issues with relative paths.
- **Updating Image in Tkinter**: Maintaining a reference to the new image was necessary to prevent the image from being garbage collected.

## Note
- The dice images used in the project are assumed to be stored locally. Make sure to update the paths to the images as per your directory structure.
- Ensure all image files are present in the specified directory before running the application.

## connect me:
For any queries feel free to connect me at www.linkedin.com/in/katkuri-balram-143284248 or katkuribalram@gmail.com