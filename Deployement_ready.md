✅ 🔥 MASTER DEPLOYMENT PROMPT (Use This)






You are a senior backend engineer preparing an already working project for production deployment.

STRICT RULES:

DO NOT change business logic or core functionality

DO NOT refactor working code unless absolutely necessary for deployment

DO NOT introduce new features

ONLY make minimal, safe, deployment-focused changes

Your task is to make the project fully deployment-ready.

Perform the following steps carefully:

Environment & Dependencies

Generate a clean requirements.txt with pinned versions

Remove unused dependencies

Ensure compatibility of all libraries

Project Structure (do NOT break imports)

Organize into standard structure if missing:
app/, routes/, services/, models/, utils/

Ensure imports still work correctly

Entry Point

Ensure a clear main entry file (main.py or app.py)

Proper FastAPI/Flask app initialization

Add uvicorn-compatible run configuration

Environment Variables

Move all secrets/configs into .env

Replace hardcoded values with environment variables

Provide a .env.example file

Dockerization

Create a production-ready Dockerfile

Use slim base image

Set working directory properly

Install dependencies efficiently

Add .dockerignore

Server Configuration

Add command to run app (uvicorn/gunicorn)

Ensure app runs on 0.0.0.0 and correct port

Logging & Error Handling

Add basic logging (INFO level)

Ensure errors don’t crash silently

Health Check Endpoint

Add /health endpoint returning simple status

README for Deployment

Add clear steps:

install

run locally

run with Docker

environment variables

Final Validation

Ensure project runs WITHOUT modification after changes

Do NOT leave broken imports

Do NOT rename files unnecessarily

OUTPUT FORMAT:

Show updated folder structure

Provide all new/modified files

Clearly mark what was added vs unchanged

IMPORTANT:
If any change risks breaking existing functionality, SKIP it and explain instead.








💡 Why This Prompt Works

It:

Constrains the agent (prevents over-engineering)

Focuses only on deployment layers

Forces safe behavior

👉 This is how senior engineers guide junior devs

🚀 How to Use It Properly (VERY IMPORTANT)
Step 1

Run your project locally ✅
(make sure everything works)

Step 2

Paste this prompt + your codebase (or files)

Step 3

Let agent modify

Step 4 (CRITICAL)

Test again locally before deploying

⚠️ Common Mistake (Avoid This)

❌ “Make this production ready”
→ Too vague → agent rewrites everything → breaks code










🔥 Optional Add-On (Even More Powerful)

After running above prompt, run this:



Review the deployment setup you just created.

Identify any risks that could break in production

Suggest improvements WITHOUT modifying core logic

Check for:

security issues

missing configs

scalability concerns







🧠 Pro Tip (Used by startups)

Use two-pass system:

Gemini → apply deployment prompt

Claude → review and clean

👉 Result = production-grade code

✅ Final Outcome You’ll Get

After this prompt, your project will have:

requirements.txt ✅

Dockerfile ✅

clean entrypoint ✅

env config ✅

health check ✅

run instructions ✅