Charcha-Club

Charcha-Club(Charcha = discussion; sounds community-oriented, like a friendly circle)is a seamless, peer-to-peer video conferencing solution built using modern web technologies like WebRTC, Socket.io, and Node.js. It offers real-time communication with minimal latency, perfect for video calls, voice chats, and soon-to-come text messaging, making it a robust platform for virtual meetings.

Getting Started
Run npm ci
cd src
Start the server using node server.js or npm start
Features
-Toggle Video: Start or stop your video stream during calls. -Audio Control: Mute or unmute your microphone with ease. -Text Chat (Under Development): Send messages in real time while on a call.

ScreenShots
![Screenshot 2025-06-04 183252](https://github.com/user-attachments/assets/3a505c1a-c951-4e64-b0d6-c5e921aed2e8)
![Screenshot 2025-06-04 183311](https://github.com/user-attachments/assets/bd1894cb-27d4-4e07-8bee-d88797f14912)


Demo:
Try the demo at: (https://baat-cheet-1pgl.onrender.com/)

Note
To enable ICE servers, you can create a free account on Xirsys and replace the current ICE server configuration in src/public/app.js. The demo may not work across different networks as the default ICE servers have been removed. However, it should work on the same network without ICE servers.

Alternative
For best performance, it is recommended to use ICE servers from Xirsys. You can sign up for a free account at Xirsys. Alternatively, Google or Twilio ICE servers can also be used. The demo should function well on the same network without ICE servers.
