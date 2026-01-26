# SecureChat: Serverless P2P messaging
SecureChat is a simple, browser-based messaging app designed for users who value complete privacy. It uses WebRTC (Web Real-Time Communication) to create a direct, encrypted connection between two browsers. This setup ensures that your data never goes through a central chat server.
## Key Features:
* True Peer-to-Peer (P2P): Messages are sent directly from one device to another. There is no middleman server processing your conversations.
* Zero Data Footprint: There are no databases, logs, or cloud storage. When you close your browser, your chat history disappears for good.
* QR-Based Handshake: You can connect securely by scanning a QR code or sharing encoded signaling string.
* End-to-End Encryption (E2EE): SecureChat uses WebRTC’s built-in DTLS and SRTP protocols for high-grade data encryption.
* Minimalist Aesthetic: The high-contrast, dark-mode interface is built with Tailwind CSS to give you a premium and focused experience.
* Fully Responsive: Seamlessly works on desktops, tablets, and mobile devices
## How to Start a Chat?
### Creating a Room:
1. Click on the Create Room button.
2. Enter Username (optional).
3. Send the provided QR code or the encoded string to your partner. (Using these dense QR codes can sometimes be buggy, so directly using the encoded string is more advisable)
4. After uploading that QR/encoded-string, your partner will get another QR code and a encoded-string, get it from your partner and just upload it.
5. Hit "Establish Connection" and a live end to end encrypted chat page will appear.
### Joining a Room
1. Click on the Join Room button.
2. Enter Username (optional)
3. Upload the QR/encoded-string provided by the host.
4. You will get an another QR code and a encoded string, share either of them with your host.
5. Once the host enters it, a live end to end encrypted connection will be established.
___
## The Web-App is live at [SecureChat](https://sercurechatbyharshit.netlify.app/)

