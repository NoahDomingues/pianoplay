# PianoPlay

Web-based application to extract piano notes from MP3 files
  
Available at: https://noahdomingues.github.io/pianofy/
  
The application is based on Web Audio API (JavaScript).
  
#### Interface
- Upload MP3 files via drag and drop to make your playlist
- A sample playlist is also provided
- Click on a song to play it
- Use the slider to control the volume of the original song and pianofied voice.
- Keep the slider fully towards the original to use the application as a normal music player

#### Major limitations
- Trade-off between detection of low pitch and high pitch notes due to varying frequency gap
- Multiple tracks in song with changing relative order of amplitude
- High FFT size will improve low-frequency note detection, but increase processing

**Note**: It is recommended to use Chrome or a modern Chromium-based browser to run the application.
