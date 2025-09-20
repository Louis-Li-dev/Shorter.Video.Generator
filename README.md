# Overview
*This system is specifically designed for you to upload audio or audio and pdf files for AI-Generated Content*
[*Demo Link*](https://youtu.be/LEIIQ8Qtwdk)    

By taking advantage of this system, you can
- Generate sample presentation with AI-TTS-generated speech.
- Shorten the existing video for clarity.
# Installation

### Step 1: Clone the Repository

Clone the project repository from GitHub:

```bash
git clone https://github.com/Louis-Li-dev/Shorter.Video.Generator.git
```

---

### Step 2: Build Dependencies (Linux Only, Windows Users Can Skip This One)

For a newly created VM, run the setup script to install dependencies (including *ffmpeg* and virtual environments):

```bash
bash setup.sh
```

---

### Step 3: Install Dependencies

- **For CPU-only Machines:**

  ```bash
  pip install -r cpu_requirements.txt
  ```

- **For Machines with GPU Support:**

  ```bash
  pip install -r gpu_requirements.txt
  ```

---

### Step 4: Create a `.env` file in the root direcotry

- Go to your [**Google AI Studio**](https://aistudio.google.com/) and create your own API key.
- Set admin account number and password.
---
### Step 5: Run the Server

Start the server by running the `app.py` file located in the root directory.

```bash
python app.py
```

---



# Expected Result
<div align="center">
  
### Main Interface  
<img src="https://github.com/user-attachments/assets/28b20487-cdae-4cae-8879-c4ffc7f46ec0" alt="Main Interface" />

---

### Downloadable Files Interface  
<img src="https://github.com/user-attachments/assets/d0803902-53d2-4d21-aec6-7e4636c88567" alt="Downloadable Files Interface" />

---

### Admin Interface for File Management  
<img src="https://github.com/user-attachments/assets/b1976b20-aff8-47d8-b6b7-5840c8762aeb" alt="Admin Interface for File Management" />

</div>

---

# References
- Gemini (Gemini 2.0 Flash)

  - Google Cloud. (2023). Gemini 2.0 Flash: Next-Generation Language Model. Retrieved from [https://cloud.google.com/](https://aistudio.google.com/prompts/new_chat)

- Whisper
  - OpenAI. (2022). Whisper: A General-Purpose Speech Recognition Model. Retrieved from [https://github.com/openai/whisper](https://github.com/openai/whisper)
- Kokoro TTS (text to speech)
  - hexgrad/Kokoro-82M. Retrieved from [https://github.com/hexgrad/kokoro](https://github.com/hexgrad/kokoro)
    

