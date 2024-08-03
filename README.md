# Generative-AI-for-Speech-to-Text-and-Summarization-of-Women-s-Right-to-Vote-Speech: This project leverages generative AI technologies to convert speech from a WAV audio file into text and subsequently summarize the content. The project specifically focuses on a speech about women's right to vote, aiming to create a concise and accurate summary of the original speech.

Key Components:

Speech to Text Conversion:
Tool Used: Python's SpeechRecognition library.
Process: The project starts with a WAV audio file containing a speech on women's right to vote. The SpeechRecognition library is used to process the audio and convert the spoken words into text. This step involves capturing audio data, recognizing the speech patterns, and transcribing the audio content into textual form.

Text Summarization:
Tool Used: Hugging Face's transformers library with the T5 model.
Process: Once the speech is converted to text, the next step is summarizing this text. The T5 model, a state-of-the-art text summarization model from the transformers library, is employed for this task. The model is fine-tuned to generate concise summaries while retaining the key points and essence of the original speech.

Workflow:
Audio Input: A WAV file containing a speech on women's right to vote is used as the input.
Speech Recognition:
The WAV file is processed using the SpeechRecognition library.
The audio content is transcribed into text.
Text Summarization:
The transcribed text is fed into the T5 model.
The model generates a summary of the speech, highlighting the main points and important information.

Results:
Transcription: The original speech is accurately transcribed into text, capturing all the spoken words.
Summary: The T5 model produces a summarized version of the transcribed text, providing a concise and coherent summary of the speech on women's right to vote.

Applications
This project can be applied in various fields such as educational tools, archival of historical speeches, and creating accessible content for individuals with hearing impairments.
It demonstrates the potential of combining speech recognition and text summarization technologies to process and distill information from spoken content.

Conclusion:
The project successfully integrates speech-to-text conversion and text summarization technologies to transform a speech on women's right to vote into a summarized textual format. This showcases the power of generative AI in enhancing accessibility and understanding of spoken content.
