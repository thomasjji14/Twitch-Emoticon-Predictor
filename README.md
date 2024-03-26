This contains the repository for downloading the dataset, exploratory code analysis, and training the model for CS485 (applications for NLP) for the Fall 2023 semester.

The dataset consists of streams from the top streamers on Twitch, using the Twitch API and a downloader to extract audio and chat data from the stream archives. Whisper Timestamped is used to transcribe audio data into text, and then the transcribed text is matched to the chat data.

The model uses a BeRT fine-tuned model to classify the streamer's text to the most relevant emote.
