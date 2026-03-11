
## Repository Structure
```
.
├── public/                 # Frontend web application files
│   ├── index.html          # Main application entry point
│   └── src/                # Frontend source code
│       ├── lib/            # Core frontend libraries
│       │   ├── play/       # Audio playback components
│       │   └── util/       # Utility functions and managers
│       ├── main.js         # Main application logic
│       └── style.css       # Application styling
├── src/                    # TypeScript source files
│   ├── client.ts           # AWS Bedrock client implementation
│   ├── server.ts           # Express server implementation
│   └── types.ts            # TypeScript type definitions
└── tsconfig.json           # TypeScript configuration
```

## Usage Instructions
### Prerequisites
- Node.js (v14 or higher)
- AWS Account with Bedrock access
- AWS CLI configured with appropriate credentials
- Modern web browser with WebAudio API support



### Installation
1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Install dependencies:
```bash
npm install
```

3. Configure AWS credentials (recommended via `.env`):
```bash
cp .env.example .env
```

4. Run dev server 
```bash
npm run dev
```


2. Open your browser:
```
http://localhost:3000
```

3. Grant microphone permissions when prompted.