# QuantumBotCore

QuantumBotCore is a project designed to manage user sessions, add messages, and log events using Firebase Cloud Functions. 
## Setup

### Prerequisites
- Node.js and npm installed
- Firebase CLI installed
- Firebase project created

### Installation Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/lingyundai/quantum-bot-core.git
    cd quantum-bot-core
    ```

2. Install dependencies:
    ```bash
    cd functions
    npm install
    ```

## Deployment

Deploy the functions to Firebase:
```bash
firebase deploy --only functions
Usage Guidelines
To start using QuantumBotCore, navigate to the deployed functions endpoint.
Use the provided API to manage user sessions, add messages, and log events.
