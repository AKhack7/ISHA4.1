# ISHA4.1

##  1 Introduction
I.S.H.A. is a versatile, AI-powered personal desktop assistant designed to streamline tasks and enhance productivity on Windows computers. Built with Python, it supports both voice and text-based commands, making it accessible via a user-friendly graphical interface or microphone input. Leveraging technologies like speech recognition, text-to speech, and web automation, I.S.H.A. can perform a wide range of tasks, from opening applications to fetching real-time information. This document outlines the capabilities of I.S.H.A. and its applications in computer-based work, making it an ideal tool for both personal and professional environments.

## 2 Capabilities of I.S.H.A.
I.S.H.A. offers a comprehensive set of features, categorized below for clarity:

##  2.1 System Control and Navigation

> **Open System Settings:** Access various Windows settings, such as display, sound, notifications, power, storage, and more, using commands like "open display setting" or "open privacy setting." 

>**File Management:** Launch File Explorer ("open file explorer") or navigate to the Downloads folder ("open download") for quick file access.

> **System Actions:** Lock the screen ("lock screen"), minimize all windows ("minimize"), or open the Run command dialog ("open run command") with simple voice or text inputs.
 
>**Shutdown and Restart:** Shutdown("shutdown") or restart ("restart") the computer instantly, enhancing user control over system operations. 

## 2.2 Application Management 

> **LaunchApplications:** Open variety of Windows applications, including Calculator ("open calculator"), Notepad ("open notepad"), Microsoft Edge ("open edge"), Paint ("open paint"), and others listed in the assistant’s app dictionary. 

> **Productivity Tools:** Start Microsoft Office applications like Word ("open ms word"), Excel ("open excel"), PowerPoint ("open power point"), and OneNote ("open onenote") for seamless workflow integration.  

> **Gaming and Entertainment:** Launch the Xbox app ("open xbox") or Windows Game Bar ("open game bar") for gaming-related tasks. 

##  2.3 Web-Based Interactions 

> **Browser Navigation:** Open websites like Google ("open google"), YouTube ("open youtube"), Instagram ("open instagram"), LinkedIn ("open linkedin"), and others with a single command. 

> **Web Searches:** Perform searches on Google or YouTube by prompting the user for a query (e.g., "What do you want to search?" after "open google"), supporting both voice and text inputs. 

> **Social Media Automation:** Log into Instagram ("instagram login") using Selenium for automated browser interactions, or send WhatsApp messages ("open whatsapp") with specified phone numbers and messages. 

> **Content Downloading:** Access Pixabay for downloading pictures ("download pic ture") or a dedicated site for Instagram reel downloads ("download instagram reel").

## 2.5 Media Control 

> **Time and Date:** Retrieve the current time ("what is the time") or date ("what is the date") with formatted outputs. 

> **Weather Updates:** Fetch real-time weather information for any city ("weather") using an online API, with offline caching for recent queries. 

> **Mathematical Calculations:** Solve mathematical expressions ("solve 2 + 2") or launch the Calculator app ("open calculator") for complex computations. 

> **AI-Powered Queries:** Answer complex questions ("explain quantum computing") by querying the Google Gemini API, providing detailed responses when online. 

## 2.6 User Interaction

> **Greetings and Responses:** Respond to greetings like "hello" or "good morning" with friendly replies, and answer queries about its identity ("what is your name"). 

> **Clipboard and Text Management:** Open clipboard history ("open clipboard") or select all text ("select all") for efficient text handling. 

> **Interactive GUI:** Display a list of available settings ("about all setting") or apps ("open apps") in popup windows for easy navigation. 

### 3 Applications in Computer-Based Work 

## I.S.H.A. significantly enhances computer-based workflows by providing a unified interface for managing tasks. Its key contributions include: 

>**Time Efficiency:** Automates repetitive tasks like opening applications, navigating settings, or performing web searches, reducing manual effort. 

>**Multimodal Interaction:** Supports both voice and text inputs, making it accessible for users with different preferences or hardware limitations (e.g., no microphone). 

>**System Management:** Simplifies access to Windows settings and system controls, ideal for IT professionals or users managing complex configurations. 

> **Productivity Boost:** Integrates with Microsoft Office and other tools, enabling quick document creation, data analysis, or presentation preparation. 

> **Entertainment and Communication:** Facilitates media playback, social media interactions, and messaging, making it a versatile tool for both work and leisure. 

> **Fallback Mechanisms:** Operates offline for local tasks (e.g., opening File Explorer or playing local music) and provides cached responses (e.g., weather) when internet is unavailable.

### 4 Conclusion 
## I.S.H.A. is a powerful tool that combines voice and text command capabilities to streamline computer-based tasks. Whether you’re managing system settings, launching applications, browsing the web, or retrieving information, I.S.H.A. offers a seamless and efficient experience. Its ability to handle both online and offline tasks, coupled with its user-friendly interface, makes it an invaluable companion for students, professionals, and anyone looking to enhance their productivity on a Windows computer. 

# For more information or to explore its features, interact with I.S.H.A. via its GUI or voice commands, and experience the future of desktop automation.

### 5 System Requirements
## To run Isha Assistant effectively, ensure your system meets the following minimum and recommended specifications. These are based on the Python environment and libraries used in the code, which support basic to advanced features like voice recognition, text-to-speech, and web automation.

## 5.1 Hardware Requirements

> **Processor:** Dual-core processor (e.g., Intel Core i3 or equivalent) at 2 GHz or higher. Recommended: Quad-core (e.g., Intel Core i5 or better) for smoother performance with voice processing and multitasking.

> **RAM:** 4 GB minimum. Recommended: 8 GB or more, especially for handling AI queries, media playback, or running alongside other applications.

> **Storage:** At least 500 MB of free space for Python installation, libraries, and logs. Recommended: 10 GB or more for general use, including downloaded content or media files.

> **Microphone and Speaker:** Required for voice input (speech recognition) and output (text-to-speech). If unavailable, the assistant falls back to text-based input/output via the GUI—no voice features will work without them. A standard built-in or external microphone/speaker suffices; no high-end hardware is needed.
> **Graphics:** Integrated graphics (e.g., Intel HD Graphics) are sufficient. No dedicated GPU is required unless using advanced OpenCV features for camera streaming.

> **Internet Connection:** Required for online features like Gemini API queries, web searches, weather updates, YouTube playback, and social media automation. Offline mode supports local tasks (e.g., opening apps, file management, math calculations).


## 5.2 Software Requirements
> **Operating System:** Windows 10 or later (64-bit recommended). The code uses Windows-specific protocols (e.g., ms-settings: URIs) and libraries like pyttsx3 (SAPI5 engine), which are fully supported on Windows 10/11. Not compatible with Windows 7/8 or non-Windows OS without modifications.

> **Python Version:** Python 3.8 or later (tested up to 3.12). Download and install from the official Python website (python.org). Ensure "Add Python to PATH" is selected during installation.

> **Google Chrome browser:** Required for Selenium-based automation (e.g., Instagram login). The code uses webdriver_manager to auto-download ChromeDriver.

> **Google Gemini API Key:**  Optional but required for AI-powered queries (e.g., "explain..."). Obtain a free key from Google's AI Studio (aistudio.google.com/app/apikey) and set it as an environment variable (GEMINI_API_KEY) using a .env file or system settings.
