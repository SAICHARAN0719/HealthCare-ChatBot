📚 Overview

In today's fast-paced world, chatbots are revolutionizing customer service across various industries. Whether it's answering questions, providing support, or even making recommendations, chatbots use artificial intelligence (AI) to interact with users.

In the healthcare industry, chatbots are becoming increasingly popular. Hospitals, clinics, and private healthcare providers use these bots to engage with patients online, helping them find the right specialists, book appointments, and get access to the correct treatments. With this Health Care Chat-Bot, we aim to extend these benefits by providing an AI-powered assistant that can guide you to the right diagnosis and recommend doctors based on your symptoms.

By leveraging machine learning and a decision tree classifier, the bot simulates the role of a general physician, helping users understand what might be wrong with them based on their symptoms.
💡 Key Features

    Registration & Login System: Secure user authentication with a simple sign-up and login process.
    Chatbot Interface: A GUI-based chatbot that interacts with users, asking questions about symptoms to diagnose potential health conditions.
    Disease Diagnosis: The bot uses a machine learning model (Decision Tree Classifier) to predict possible diseases based on user responses.
    Doctor Recommendations: Once a disease is diagnosed, the bot recommends an appropriate doctor and provides clickable links to their profiles.
    24/7 Healthcare Support: The chatbot works around the clock, offering support whenever needed.

🔧 Modules Used

This project relies on several Python modules to function correctly:

    tkinter - For creating the graphical user interface (GUI).
    os - To interact with the operating system and handle files.
    webbrowser - For opening links to doctor profiles and other external websites.
    numpy - For numerical computations.
    pandas - For handling and manipulating data.
    matplotlib - For data visualization (though it might not be used in the current version, it's included in case you want to visualize some data).

📥 Installation

To get started with the Health Care Chat-Bot, you'll need to install the required Python modules. Here's how you can do that:

    Open your command prompt or terminal.
    Install the necessary packages by typing the following commands:

pip install numpy
pip install pandas
pip install matplotlib

    Once the installation is complete, open your Python IDLE (or any other code editor you prefer) and run the following imports to verify the installation:

import numpy
import pandas
import matplotlib

If no errors appear, you're all set!

Finally, navigate to your project directory and run the file QuestionDiagnosisTkinter.py to start the chatbot.
🚀 How to Use

    Run the Program: Once the required packages are installed, run the file QuestionDiagnosisTkinter.py.
    Sign Up or Log In: Create a new account or log in with your existing credentials.
    Interact with the Chatbot: The chatbot will start by asking you a series of questions to diagnose your symptoms.
    Get Your Diagnosis: Based on your responses, the bot will suggest possible diseases and recommend doctors.
    Consult the Recommended Doctors: Click on the provided links to visit the doctors' profiles and book appointments if necessary.

