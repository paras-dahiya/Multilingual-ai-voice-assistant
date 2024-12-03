# Multilingual-AI-Voice-Assistant

This Multilingual AI Voice Assistant is a Python-based application designed to enhance accessibility and user interaction across diverse linguistic backgrounds. The system processes voice inputs in multiple languages and provides outputs in both text and speech formats, leveraging cutting-edge speech technologies.

The assistant features robust speech recognition to transcribe spoken input into text, ensuring accurate language detection and interpretation. This text is then processed by the Gemini model, enabling accurate comprehension and context-aware responses. The system generates replies that are converted back into speech using high-quality text-to-speech synthesis, ensuring a seamless and interactive user experience.

This assistant supports a wide range of languages, making it a versatile tool for global applications, including customer service, educational platforms, and personal assistance. Its multilingual capabilities bridge communication gaps, fostering better accessibility and inclusivity. The project demonstrates innovation in integrating speech processing with state-of-the-art AI models, highlighting efficiency, accuracy, and adaptability.

Built entirely in Python, the project integrates various libraries and APIs for speech processing, natural language understanding, and synthesis. This Python foundation ensures flexibility, scalability, and ease of customization for various applications. The assistant's multilingual capabilities make it ideal for global use cases such as customer service, education, smart homes, and healthcare.

By combining sophisticated speech processing with the generative power of the Google Gemini model, this project bridges communication gaps and fosters inclusivity.

# Demo
![Demo](https://github.com/paras-dahiya/Multilingual-ai-voice-assistant/blob/master/demo/Screenshot%202024-12-03%20215614.png)

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: [https://github.com/](https://github.com/paras-dahiya/Multilingual-ai-voice-assistant)
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s
