# Color Generator Web Application

This Flask server-based web application generates hexadecimal color codes based on an input prompt using OpenAI completion. The generated colors are displayed in a div element, with the screen divided into sections based on the number of colors found.

## Description

The Color Generator Web Application allows you to effortlessly create beautiful color combinations. Simply enter a prompt in the input field, and the application will generate a set of colors with their corresponding hexadecimal codes. The number of colors generated is determined by the predefined prompt, providing a range of visually appealing options.

Once the colors and their codes appear on the screen, you can easily copy them to your clipboard with a single click. This makes it convenient to use the generated colors in your design projects, web development, or any other creative endeavors.

![wapalette](https://github.com/agiwunderlich/ColorPaletteProject/assets/35004717/fbf7603d-2353-427c-ab36-3f45dc65514d)

## Prerequisites!


- Python 3.6 or higher
- OpenAI API Key


## Usage

Follow the instructions below to run the web application on your local machine:

1. Ensure that Python is installed on your computer. Visit the official Python website (https://www.python.org/) to download and install the latest stable version for your operating system.

2. Clone this repository to your local machine or download the source code files.

3. Open your command prompt or terminal, and navigate to the project directory.

4. Create and activate a virtual environment (recommended) by running the following commands:

   - On Windows:

     ```
     python -m venv venv
     venv\Scripts\activate
     ```

   - On macOS/Linux:
     ```
     python3 -m venv venv
     source venv/bin/activate
     ```

5. Install the required dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

6. Create a file named `.env` in the project root directory and add the following line:
   OPENAI_API_KEY=your-api-key
   Replace `your-api-key` with your actual OpenAI API Key.
   
   Please note that the OpenAI API Key is required to use the application. 
   If you don't have an API Key yet, you can obtain one from the OpenAI website (https://openai.com) by creating an account and generating an API Key.
   
7. Run the Flask application by executing the following command:

   ```
   flask run
   ```

7. Open your web browser and navigate to the provided URL (usually `http://127.0.0.1:5000` or `http://localhost:5000`) to access the web application.

## Example

Here's an example of how the application works:

1. Enter a prompt in the input field (e.g., "Wes Anderson movie color palette" or "Monet's Water Lilies").

2. Click the "Generate" button.

3. The application will generate the specified number of hexadecimal color codes based on the input prompt and display them in a div element.

4. The screen will be divided into sections, with each section representing a color.

5. Click on a color code to copy it to your clipboard and use it in your projects.

Feel free to explore the application and have fun generating different color combinations!
