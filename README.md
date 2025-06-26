Omani Voice-based AI Therapist (Demo)
Welcome to the demo for the Voice-based AI Therapist. This project is an interactive, browser-based web application designed to provide mental health support through AI-powered conversation.

Project Overview
Objective: To provide a voice-based interface that listens and responds to the user in Arabic (Omani dialect).

Technology: The application uses the browser's built-in speech recognition, connects to OpenAI's gpt-4o model to analyze the user's speech and generate intelligent responses, and then uses the browser's speech synthesis to voice those responses.

Architecture: The entire application is self-contained in a single index.html file and requires no complex backend server setup.

Prerequisites for Running the Application
To run this application successfully, please ensure the following are available on your computer:

A modern web browser: Google Chrome or Mozilla Firefox is highly recommended.

Python: This is used to run a simple local web server. Most modern operating systems (macOS and Linux) come with Python pre-installed. For Windows users, it can be downloaded for free from python.org. To check if it's installed, open a Terminal or Command Prompt and type python --version.

Detailed Steps to Run the Application
Please follow these steps carefully to ensure the application runs correctly.

Step 1: Download the Project Files
Navigate to the project's GitHub page.

Click the green < > Code button.

Select "Download ZIP" from the dropdown menu.

Once the download is complete, unzip the file to a suitable location on your computer (e.g., your Desktop).

Step 2: Start the Local Server
This step is essential because browsers have security restrictions that prevent local files from accessing the microphone directly.

Open the Terminal application (on Mac/Linux) or Command Prompt (on Windows).

Use the cd command to navigate into the unzipped folder. For example:

# Example for a Windows user
cd C:\Users\YourUser\Desktop\omani-therapist-voice-demo

# Example for a Mac user
cd /Users/YourUser/Desktop/omani-therapist-voice-demo

Once you are inside the correct folder (the one containing index.html), run the following command:

python -m http.server 8000

Do not close the terminal window. Leave it running in the background.

Step 3: Open and Test the Application
Open your Google Chrome or Firefox browser.

In the address bar, type the following URL and press Enter:

http://localhost:8000

(Very Important Step) A notification will appear at the top of the browser asking for permission to use your microphone. You must click "Allow". If you deny this permission, the application will not be able to hear you.

Once you grant permission, the button in the application will become clickable.

The application is now ready to use. You can click the "Press and Talk" button to start a conversation.
