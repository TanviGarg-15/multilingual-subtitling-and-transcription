
# multilingual subtitling and transcription
A simple application that can perform following tasks-
* Transcript generation for audio file
* Subtitles creation for video ( presently supports only US english audio/video)
* Translation of transcripts or subtitles in any Indian language

### Technologies used
* Python 3.7
* FFmpeg to extract and process audio into a suitable format that can be recognized by speech recognition engine.
 It can be downloaded from https://ffmpeg.org/download.html.
* Pocketsphinx to recognize speech from the audio with its time level stamping. For more details see- 
https://github.com/cmusphinx/pocketsphinx

