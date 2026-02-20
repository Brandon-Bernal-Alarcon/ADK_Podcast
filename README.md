# ADK Podcast

Convert a PDF file or any custom topic into an **AI-generated podcast**, with configurable language, voice, and number of speakers.

## Author

Developed by **Bernal Alarcón Brandón Yahir** as part of an AI Challenge project.
e such as MIT if desired.


## What is this?

**ADK Podcast** is an intelligent agent built in **Google Colab** that allows you to:

- Convert a PDF document into a structured podcast
- Generate conversations with **1 or 2 speakers**
- Choose the output language (Spanish, English, French, Portuguese, etc.)
- Select male or female voices and adjust tone settings

The agent combines large language models and text-to-speech capabilities to generate structured dialogue and produce an audio podcast automatically.

## How to Use (Google Colab)

1. **Open in Google Colab**  
   Access the notebook here:  
   https://colab.research.google.com/drive/1-emHDdKBc183wrOSFA3JTPDe2BfYs1hr

2. **Upload Your PDF (Optional)**  
   - Upload your `.pdf` file to the Colab environment  
   - Copy the file path and paste it into the corresponding section of the notebook  

3. **Update Your API Key**  
   In the **API KEY** section, replace the placeholder with your own **GOOGLE API KEY**.

4. **Run the Notebook**  
   - Modify the prompt if needed  
   - Execute the cells in order  
   - The simplified execution mode is more intuitive and recommended for experimentation  


## Project Structure

The notebook is organized into the following sections:

- **Library and Module Imports**
- **Configuration and API Key Setup**
- **PDF Processing (if applicable)**
- **Dialogue Generation**
- **Audio Generation (Podcast Output)**


## Notes About Execution

The execution workflow is somewhat rudimentary due to notebook environment limitations.  

If deployed in a virtual environment (e.g., web-based ADK interface or full-stack app), minor structural adjustments would be required.

