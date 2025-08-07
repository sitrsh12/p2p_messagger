# P2P Messenger - Direct Peer-to-Peer Communication

A secure Android messenger app that establishes direct device-to-device connections using various P2P strategies, eliminating the need for central servers.

## Key Features

### 🛠️ Core Functionality
- **Direct Device Connections**: Establish connections without intermediaries
- **Multiple Connection Strategies**:
  - Local network discovery
  - Public IP direct connection
  - NAT hole punching
- **Encrypted Connection Info**: Securely share device endpoints
- **Cross-Network Messaging**: Works on same network or over internet

### 🔒 Security
- AES-256 encrypted connection metadata
- Secure peer identity management
- Input sanitization against injection attacks
- Certificate pinning for public IP services
- Anti-tampering measures

### 📱 User Experience
- Modern Material Design 3 interface
- Real-time messaging with timestamps
- Connection status monitoring
- Detailed connection logs
- Copy/share connection info
- Message history persistence

### ⚙️ Technical Highlights
- UDP-based communication
- Multicast discovery protocol
- Automatic port management
- Network change detection
- Connection timeout handling
- Message delivery tracking

- DOWNLOAD APK FROM HERE: https://github.com/sitrsh12/p2p_messagger/raw/refs/heads/main/p2p-messenger.apk

## Getting Started

### Prerequisites
- Android 8.0 (Oreo) or higher
- Devices on same network for discovery
- Internet access for public IP detection

### Installation
1. Download the latest APK 
2. Enable "Install from unknown sources" in Android settings
3. Install the APK on your device
4. Step 1: Set Up Devices
5. Each device will automatically generate: Unique Peer ID (e.g. USR-4d8a175a)
6. On Device B, enter Device A's Peer ID
7. Tap "Connect"
8. Device A will receive connection request. Accept on Device A to establish connection
9. On Device A, tap "Copy Connection Info" Share the code with Device B (message, email, etc.)
10. Start Messaging
11. Type messages in the input field - Press send icon or Enter key - Messages appear in real-time - View message timestamps and sender info


