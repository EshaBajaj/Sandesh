# Sandesh 
A secure, location-aware emergency message delivery concept.  
Inspired by wartime sandesha systems, built with minimal tech, maximal impact.



## Features (Planned)
- Send emergency messages with limited characters
- Store metadata like location, timestamp, sender ID
- Prepare for use in disaster, blackout, or low-signal zones



## Tech Stack
- Python (core)
- JSON for storing messages
- Future plan: Django / Flask for web interface//to convert it into real time app
- GitHub for version control


## Vision
To build resilient, reliable, and redundant military-grade communication systems using minimal resources.
The system is not dependent on real-time internet and simulates wartime resilience using lightweight architecture.

## How will it Work
 Event Trigger (enemy, ammo, SOS)
↓
 Pre-set coded messages (like A101: Ammo Low)
↓
Auto attach location (approx coordinates)
↓
Timestamp recorded
↓
Calculate NEAREST cantonment (from fixed DB)
↓
📨 Store message locally or trigger offline transmission