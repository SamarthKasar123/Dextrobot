Dextrobot :  A Simple Voice AI Bot with Web Speech API and Node.js

This is how this web app works:

  Using the Web Speech API’s SpeechRecognition interface to listen your voice from a microphone

  Send your message to API.ai (the natural language processing platform) as a text string

  Once the AI from the API.ai returns the reply text back, use the SpeechSynthesis interface to give it a synthetic voice.

Try It on Your Own Server
Rename the .env.local to .env and fill the env vars:

APIAI_TOKEN=
APIAI_SESSION_ID=some_unique_session_id
