# Gather — Video Conferencing Platform UI

A React meeting-room interface with local camera/microphone preview, participant layout, room code copy, chat panel and meeting controls.

## Features
- Responsive video meeting layout
- Request local camera/microphone permission with `getUserMedia`
- Toggle local audio/video tracks
- Participant list and room identifier
- Local meeting chat panel
- Copy room code

## Tech
React, JavaScript, Vite, CSS, browser MediaDevices API and Lucide icons.

## Run
```bash
npm install
npm run dev
```

## Important scope note
This is a frontend meeting-room prototype. The participant tiles and room chat are demo UI only. It does not yet connect multiple browsers or stream media to other participants. Real multi-user WebRTC requires a signaling service (for example Socket.IO), STUN/TURN configuration and peer-connection handling. Camera access generally requires localhost or HTTPS and browser permission.
