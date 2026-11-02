1 Install libraries
start lm-studio and name the model you want to use. limit the context window to 10k
name the model you want to use here in the program
LOCAL_API_URL ="http://localhost:1234/v1/chat/completions"
MODEL_NAME = "google/gemma-4-26b-a4b"
run
if there is no mic
find you headset run the mic_test program no 4 this will list the mics available.
you may need to change this area of the program. on one computer i did need to change the values on another i did not.
def listen_for_command():
    recognizer = sr.Recognizer()

    device_index = 2
    sample_rate = 44100
    channels = 1
    chunk = 1024
    record_seconds = 5

    p = pyaudio.PyAudio()
    stream = None
press microphone
voice commands are very limited. for longer questions type it in.
hit enter depending on how much memory you have it can take anywhere from 30 seconds to a couple of minutes before a responce
comes back. hearing the llm is much better than reading the reply.
good luck
