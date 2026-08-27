# AI Meeting Notes Assistant

Uploads an audio recording of a meeting, transcribes it with Whisper (`openai/whisper-medium`), cleans up financial/product terminology using an LLM pass (watsonx.ai), and generates structured meeting minutes and a task list — all through a Gradio web interface.

## Setup

```bash
pip install -r requirements.txt
```

## Run

```bash
python main.py
```

Opens a Gradio interface where you upload an audio file and receive generated meeting minutes plus a downloadable task list.

`sample-meeting.wav` is included as a sample input for testing.
