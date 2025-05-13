🎙️ LiveToText
LiveToText is a simple Python notebook application that captures live audio from your microphone and converts it into text using the SpeechRecognition library and the Google Web Speech API.

🛠 Features
Record live audio from your microphone

Save the recording as a .wav file

Convert recorded audio to text using speech recognition

Supports customizable duration, sample rate, and chunk size

📦 Requirements
Install the required Python packages using:

bash
Copy
Edit
pip install pyaudio speechrecognition
⚠️ Note: PyAudio installation may require additional system dependencies, especially on non-Windows systems.

🚀 How It Works
The script records audio for a specified duration.

The audio is saved as a .wav file.

The audio file is passed to the Google Web Speech API for transcription.

The transcribed text is printed to the console.

📂 File Structure
LiveToText.ipynb - Jupyter Notebook containing the full code for recording and transcription.

🧪 Example Output
css
Copy
Edit
Recording for 5 seconds...
Recording finished.
Audio saved to output.wav
Processing audio...
Transcribed Text:
Hello, how are you today?
In some cases, if the audio is unclear or there's too much background noise, you might see:

scss
Copy
Edit
Transcribed Text:
Speech not recognized.
✅ Usage
Run the notebook cells in order inside Jupyter or VS Code. Adjust the record_duration variable as needed.

🔒 Privacy Note
The transcription uses Google's Web Speech API, so your audio is sent to Google's servers. Avoid sending sensitive information via voice input.

📜 License
This project is open-source and available under the MIT License.

Let me know if you'd like a badge-based header or to convert this into a standalone Python script as well. # Audio-to-text
