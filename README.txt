# Mind Wars Online (prototype)

## What is included
- Mobile-friendly Japanese interface
- 3-player room creation and join codes
- Peer-to-peer room communication using Trystero's public torrent/WebRTC signaling
- Secret action locking and round resolution
- Attack, defense, charge, steal, heal, HP/energy/points, eliminations, win conditions

## How to try it
1. Upload `index.html` to a static hosting service that serves HTTPS.
2. Open the published HTTPS URL on all three phones.
3. One player creates a room and shares the displayed code.
4. The other two players enter the same code and join.

## Important prototype note
This is an experimental peer-to-peer prototype, not a production-hardened game server. WebRTC connectivity can depend on network settings, and a host disconnect can interrupt the room. Secret choices are intended to be sent only to the host and revealed after resolution, but this prototype should be play-tested before relying on it for a tournament.
