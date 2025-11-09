# voice-playgrounds

Audio transcription using OpenAI's GPT-4o transcription API.


## Usage

The notebook includes two transcription methods:

**Basic transcription** - Returns plain text output

**Diarized transcription** - Identifies different speakers and returns structured JSON with timestamps

Place audio files in the `data/` folder. Transcriptions are saved to `output/`.

## Models

- `gpt-4o-transcribe` - Standard transcription
- `gpt-4o-transcribe-diarize` - Speaker diarization with timestamps

