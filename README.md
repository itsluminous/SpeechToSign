# Speech-to-Sign-Language-Translator

<b>Instructions</b>

    1. Install blender 2.79.
    2. Set Path variable for python distribution present inside blender (\Your installation directory\Blender Foundation\Blender\2.79\python\bin). Install pip for this python distribution from here and set path variable also.
    3. Install and setup ffmpeg from here.
    4. Install python dependecies using pip: pyaudio, google-cloud-speech, google-cloud-language etc.
    5. Congifure API Key for google cloud services. You might have to create a new project and enable google speech and language api in googlecloud console, then create and download a json credential file and set "json_key_file" in startup.py to the path to json credential file.
    6. Run .blend file inside model folder.

<b>Additional</b>

    1. Use python 3.5.3 so that code is compatible with blender 2.79.
    2. ffmpeg required for converting wav to flac. Install ffmpeg first and add it to environment variables else errors will occur.
    3. .raw & .flac are the only audio file accepted for text transalation by the API.
    4. Works correctly for first time in game engine after that errors occur, don't know why.
    
<b>Pip commands</b>

    pip install PyAudio
    pip install google-cloud-speech
    pip install google-cloud-language
