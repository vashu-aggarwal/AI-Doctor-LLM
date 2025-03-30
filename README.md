# 🏥 Smart Medical AI Chatbot (Vision & Voice)

An advanced AI-powered Medical Chatbot that understands both **images and voice**, acting as a **personalized AI Doctor assistant**. Built using **open-source AI models**, this chatbot enables seamless **medical consultations** with multimodal capabilities.

## 🚀 Features
- **Vision & Text Understanding** – Powered by **Meta Llama3 Vision 90B** for exceptional image and text analysis.
- **Speech-to-Text** – Utilizes **OpenAI Whisper** for accurate voice transcription.
- **Natural & Conversational** – Engages in intelligent medical discussions using advanced **LLMs**.
- **Accessible & Efficient** – A lightweight, user-friendly interface built with **Gradio**.

---

# 📌 Project Setup Guide
This guide provides step-by-step instructions to set up your project environment, including the installation of **FFmpeg** and **PortAudio** across macOS, Linux, and Windows, as well as setting up a **Python virtual environment** using Pipenv, pip, or Conda.

## 📜 Table of Contents
1. [Installing FFmpeg and PortAudio](#installing-ffmpeg-and-portaudio)
   - macOS
   - Linux
   - Windows
2. [Setting Up a Python Virtual Environment](#setting-up-a-python-virtual-environment)
   - Using Pipenv
   - Using pip and venv
   - Using Conda
3. [Running the Application](#running-the-application)
4. [Project Phases and Python Commands](#project-phases-and-python-commands)

---

## 🛠️ Installing FFmpeg and PortAudio
### macOS
#### Install Homebrew (if not already installed):
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
#### Install FFmpeg and PortAudio:
```sh
brew install ffmpeg portaudio
```

### Linux
For Debian-based distributions (e.g., Ubuntu):
#### Update the package list:
```sh
sudo apt update
```
#### Install FFmpeg and PortAudio:
```sh
sudo apt install ffmpeg portaudio19-dev
```

### Windows
#### Download and Set Up FFmpeg:
1. Visit the official [FFmpeg download page](https://ffmpeg.org/download.html).
2. Navigate to the Windows builds section and download the latest **static build**.
3. Extract the downloaded ZIP file to a folder (e.g., `C:\ffmpeg`).
4. Add the `bin` directory to your system's **PATH**:
   - Search for **"Environment Variables"** in the Start menu.
   - Click on **"Edit the system environment variables"**.
   - In the **System Properties** window, click on **"Environment Variables"**.
   - Under **"System variables"**, select the **"Path"** variable and click **"Edit"**.
   - Click **"New"** and add the path to the bin directory (e.g., `C:\ffmpeg\bin`).
   - Click **"OK"** to apply the changes.

#### Install PortAudio:
1. Download the PortAudio binaries from the official [PortAudio website](http://www.portaudio.com/download.html).
2. Follow the installation instructions provided on the website.

---

## 🏗️ Setting Up a Python Virtual Environment

### Using Pipenv
#### Install Pipenv (if not already installed):
```sh
pip install pipenv
```
#### Install Dependencies with Pipenv:
```sh
pipenv install
```
#### Activate the Virtual Environment:
```sh
pipenv shell
```

### Using pip and venv
#### Create a Virtual Environment:
```sh
python -m venv venv
```
#### Activate the Virtual Environment:
- **macOS/Linux:**
  ```sh
  source venv/bin/activate
  ```
- **Windows:**
  ```sh
  venv\Scripts\activate
  ```
#### Install Dependencies:
```sh
pip install -r requirements.txt
```

### Using Conda
#### Create a Conda Environment:
```sh
conda create --name myenv python=3.11
```
#### Activate the Conda Environment:
```sh
conda activate myenv
```
#### Install Dependencies:
```sh
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Once all dependencies are installed and the environment is set up, you can run the different project phases using the following commands:

### **Project Phases and Python Commands**
#### **Phase 1: Brain of the Doctor**
```sh
python brain_of_the_doctor.py
```
#### **Phase 2: Voice of the Patient**
```sh
python voice_of_the_patient.py
```
#### **Phase 3: Voice of the Doctor**
```sh
python voice_of_the_doctor.py
```
#### **Phase 4: Setup Gradio UI**
```sh
python gradio_app.py
```

---

### 🌟 Contributing
Feel free to **fork** this repository, submit **issues**, and create **pull requests** to improve the chatbot! 

### 📜 License
This project is open-source and available under the **MIT License**.

🔗 **Follow and star this repository for updates!** 🚀
