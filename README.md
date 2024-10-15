## To run the program on your local machine:

## Prerequisites
- [Node.js](https://nodejs.org/) (v14+)
- [FFmpeg](https://ffmpeg.org/download.html) installed and accessible in PATH
- OpenAI API Key ([get it here](https://platform.openai.com/))
- Microphone and speaker setup
- Macbook (This is my local machine. I'm not sure if it works fine on Windows)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/leslie0605/interview-platform-backend.git
   cd interview-platform-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create an .env file and add your OpenAI API key:
   ```bash
   OPENAI_API_KEY=your_openai_api_key_here
   ```
4. Upload your own resume to root folder and name it as "resume.pdf".
5. Start the app:
   ```bash
   node ttsChat.js 
   ```
