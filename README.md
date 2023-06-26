# Transcribot: Automated Audio Transcription

Welcome to Transcribot, a powerful Python script that leverages the cutting-edge AssemblyAI API to provide seamless and accurate automated audio transcription. With Transcribot, you can effortlessly transcribe audio files into text, saving you valuable time and effort.

## Prerequisites

To harness the full potential of Transcribot, ensure that you have the following prerequisites:

- Python 3.x
- The `requests` library
- An API key from AssemblyAI. If you don't have one yet, visit [AssemblyAI](https://www.assemblyai.com/) to obtain your API key.

## Setup

Follow these steps to set up Transcribot and get started:

1. Clone this repository to your local machine or download the files to a desired directory.

2. Install the essential `requests` library by executing the following command in your terminal:

   ```bash
   pip install requests
   ```

3. Place your audio file in the project directory. For your convenience, a sample audio file named `testing.wav` is already provided.

4. Open the `api_secrets.py` file and replace the placeholder `"API"` with your actual AssemblyAI API key.

## Usage

Transcribot is straightforward to use. Simply follow these instructions:

1. Open the `Main.py` file.

2. Add your audio file to the same repository and run the script below. You can also test it with the given "testing.wav" audio file

3. Run the script by executing the following command in your terminal:

   ```bash
   python Main.py FileName
   ```

4. Transcribot will seamlessly upload your audio file to AssemblyAI and patiently await the completion of the transcription process.

5. Once the transcription is successfully completed, it will be automatically saved to a text file with the same name as the audio file, but with the `.txt` extension.

6. Take a moment to marvel at the generated text file, which encapsulates the brilliance of Transcribot's accurate transcription capabilities.

## Additional Notes

- The `poll` function diligently monitors the status of the transcription job, ensuring timely completion. It periodically checks for updates every 30 seconds, guaranteeing efficiency and reliability.

- In the event of an error during transcription, Transcribot will promptly display the error message, enabling swift troubleshooting and resolution.

- Feel free to customize and adapt the script according to your specific requirements or incorporate it into your own projects. Transcribot is versatile and can be seamlessly integrated into various applications.
