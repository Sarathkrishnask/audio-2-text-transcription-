Audio to Text Transcript with Speaker Diarization 🎙️📝
This project processes long audio files (e.g. `.mp3`) into clean, speaker-separated transcripts using a combination of audio enhancement, speaker diarization, and transcription via OpenAI's Whisper model.
🔍 Features
•	🎧 Converts `.mp3` audio to `.wav` format
•	✂️ Splits audio into smaller, manageable chunks
•	🔊 Enhances audio quality
•	🧠 Transcribes using OpenAI's Whisper (medium model)
•	🗣️ Identifies individual speakers (speaker diarization)
•	🕒 Outputs timestamps with who spoke what
•	📄 Saves results as readable documents (e.g. `.txt`, `.docx`)
🚀 Try It in Google Colab
You can run the whole pipeline in Colab with zero setup. Just upload your audio file and follow the cells.
Notebook	Description	Open in Colab
🔊 Main Transcription Pipeline	Full audio to speaker transcript	https://colab.research.google.com/drive/1-LiE4CSCVA6RGOCvQkMK_TL9SvkyG7gW#scrollTo=yuXIr36FCoEW
🎯 Alternate Transcriber	Alternative transcription pipeline	https://colab.research.google.com/drive/1u5aL_21tkqKm-WoUnu9ZblQ0EWFfQdtq
📹 Zoom Meeting Transcriber	Extracts speaker transcript from Zoom recordings	https://colab.research.google.com/drive/1zEHYisMz_PK-gevJGtifmYD_StMe3iRT
🧱 Libraries & Tools Used
•	whisper (OpenAI transcription)
•	pydub, soundfile (audio handling)
•	pyannote.audio, simple_diarizer (speaker diarization)
•	matplotlib (visualizations)
•	torch, numpy, pandas
📦 How to Use
1.	Open any Colab link above.
2.	Upload your `.mp3` audio file to Colab.
3.	Provide the file path in the notebook input cell.
4.	Run all cells (Shift + Enter).
5.	Receive:
 - A plotted waveform with speaker labels.
 - A text-based transcript with timestamps.
📸 Sample Output
 
 
📝 Transcript Sample
[00:00:00] Speaker 1: Hi Lucy, nice to meet you. So I understand that you were referred here by your GP...
[00:00:10] Speaker 0: Yes, that's right. I've been feeling quite down lately...
✍️ Author
Built by SARATHKUMAR R
