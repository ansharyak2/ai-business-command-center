AI BUSINESS COMMAND CENTER — VOICE PWA

Backend URL already configured:
https://script.google.com/macros/s/AKfycbx9vfkUVtGAGoh5hqeOQocoRAjgW2ELHHnRlIYWtrY4BomqgQBMcvAGwBaofOju8lSG/exec

SETUP:
1. Create a NEW PUBLIC GitHub repository named: ai-business-command-center
2. Upload index.html, manifest.json and sw.js to the repository root.
3. Open Settings -> Pages.
4. Build and deployment -> Deploy from a branch.
5. Branch: main, folder: / (root), Save.
6. Open the generated HTTPS Pages URL.
7. Allow microphone.
8. Test a command.

IMPORTANT:
- Do NOT put the Gemini API key in this frontend.
- Gemini key remains in Apps Script Script Properties.
- Existing Apps Script backend remains the source of truth.
- If the command reaches the Sheet but browser reports CORS, tell me the exact error; we will make one small backend response adjustment.
