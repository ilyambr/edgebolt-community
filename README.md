# EdgeBolt Community Edition (v1.5)

Tampermonkey script for Edgenuity.

[Install Userscript](https://raw.githubusercontent.com/ilyambr/edgebolt-community/main/edgebolt.obfuscated.v1.5.community.txt)

Created by [@TallTacoTristan](https://github.com/TallTacoTristan), updated by [@ilyambr](https://github.com/ilyambr) and [@google-antigravity](https://github.com/google-antigravity)  
Script Discord: [https://discord.gg/edgebolt](https://discord.gg/6qJwkYSmrQ)

### Added
- Multi-AI provider support with auto-routing (Groq, Cerebras, OpenRouter)
- Audio question transcription using Whisper models for questions with audio files
- Replaced dead HotBot with direct background AI for journals and essays
- 1-2 paragraph limit on essays so it doesn't write massive walls of text
- Full prompt grabbing (expands collapsed questions like "Read More" instead of cutting off)
- In-GUI API key manager to add and remove keys easily
- Dark/grey theme redesign for the menu (for easy distinguishing between the original script and the community script)
- Auto-advance fixes for narration delays, quiz/exam start screens, and activities
- Faster asynchronous question database decryption (no more browser lag/freezing)
- Updated killswitch with community update screen

### Removed
- "do you?" black screen screamer / anti-dualbooting trap that broke the page
- Hallucinating answers on unsupported question types (drawings, drag-and-drop)
