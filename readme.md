# TransLangg

Creates transcription of media files, whether audio or video.

### Run the script

Follow these steps to activate the GPU:
- Open the .ipynb file in Google Colab
- In the menu bar at top: `Runtime > Change runtime type > Hardware accelerator: GPU`
- To run the script: `Runtime > Restart and run all`

### Choosing GPU over CPU

- With GPU, transcription speed increases significantly in comparison to CPU.

### Install necessary API libraries

- pip install package: downloads the dependencies for 'package'

### Upload files to Google Drive

- Allow Google Colab access to your drive to read files for transcription
- Access your google drive at https://drive.google.com/drive/my-drive
- Open the folder at "Colab Notebooks/translangg/input"
- Upload the media files (videos and audios) to be transcribed

### Transcribing the uploaded media files

- Enter the language for transcription and hit enter
- In the demo video, we have transcribed 2 mp3 and 1 mp4 files in "English" language.
- Wait till all files are transcribed
- Check the transcribed files in Google Drive Folder at "Colab Notebooks/translangg/output"
- Alternately, you can check the transcribed files in zip package downloaded.