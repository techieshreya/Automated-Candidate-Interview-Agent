# 🧠 Automated Candidate Interview Agent

An AI-powered interview screening tool that dynamically analyzes resumes and job descriptions to conduct intelligent, conversational interviews. Supports both text and voice-based modes for candidate interaction.


FULL CODE IS IN ZIP FILE 
---

## 🚀 Features

- 📄 **Resume + JD Analysis**: Extracts and compares key skills, experience, and qualifications.
- 💬 **Dynamic Question Generation**: Creates customized questions — technical, behavioral, situational.
- 🧠 **Conversational Flow**: Understands and responds to candidate input using LLMs.
- 🎤 **Voice Mode (Advanced)**: Enables voice conversation for higher interaction (via Web Speech API or Whisper).
- 📋 **Summary Generation**: Outputs structured evaluations based on responses and job fit.

---

## 🧱 Project Structure

```txt
.
├── app/                   # Main application routing and layout (Next.js App Router)
├── components/           # Reusable UI components (forms, interview chat, cards)
├── hooks/                # Custom React hooks (e.g., useSpeech, useChatFlow)
├── lib/                  # Utility functions (e.g., resume parser, JD analyzer)
├── public/               # Static assets
├── styles/               # Tailwind/global CSS files
├── next.config.mjs       # Next.js configuration
├── package.json          # Project metadata and dependencies
├── pnpm-lock.yaml        # Dependency lock file
├── postcss.config.mjs    # PostCSS config
├── tailwind.config.ts    # Tailwind CSS config
├── tsconfig.json         # TypeScript configuration
└── .gitignore            # Ignored files


```
---

## 🛠️ Tech Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, TailwindCSS
- **Backend**: Node.js (API routes), LangChain / OpenAI APIs
- **Voice Integration**: Web Speech API / Whisper
- **AI Models**: GPT (for question generation & summarization)

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/automated-interview-agent.git

# Navigate into the directory
cd automated-interview-agent

# Install dependencies
pnpm install

# Run the development server
pnpm dev
