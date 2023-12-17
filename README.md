# SRT to Plain Text

This is a basic utility that converts `.srt` files to plain text script files.

## Usage

You'll need [Node](https://nodejs.org/en) version 18 or later.

To run the demo files:

```sh
# Run the demo script on an example file using auto-captions from YouTube
node ./demo.mjs examples/youtube-automatic-subtitles.srt
# Run the demo script on an example file generated with OpenAI Whisper
node ./demo.mjs examples/openai-whisper-subtitles.srt
```

After running the above commands from the root of this project, output files should be written to an `output` folder at the root of this project.
