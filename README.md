# RX Career Agent

A reusable agent skill for understanding your experience, finding suitable opportunities, tailoring resumes in Reactive Resume, and completing approved applications.

## Start here

1. Download `rx-career-agent.zip` from this repository (open the file, then use the download button). Alternatively, clone or download the repository and use the ZIP inside it.
2. Extract the ZIP. Place the resulting `rx-career-agent` folder inside `.agents/skills/` in a new local Codex project. Create those folders if needed.
3. Open that project in Codex and start a new task with:

   > Use $rx-career-agent to analyze my resume, interview me about my experience and career goals, connect my own Reactive Resume account, and help me find suitable jobs and prepare applications.

4. Provide your current resume and your own RX account access when the agent asks. Use a private credential file or supported secret storage; do not paste API keys into repository files.

Keep resumes, credentials and application records in a **separate private workspace outside this repository**. Tell the agent where that workspace is. Do not upload personal career records to this repository.

## What it covers

- Evidence-based resume analysis and an adaptive profile interview.
- Search criteria reflecting your actual goals, location and work preferences.
- Holistic opportunity research, official vacancy verification and separate WANT/FIT assessments.
- Account-verified RX resume copies, tailored content and cover letters.
- Final PDF visual and text checks, form filling and document uploads.
- Employer-specific salary approval, final submission approval and receipt verification.
- Private application tracking and continuity across sessions.

## What you need

An agent environment with web research, file/PDF handling and authenticated browser control for the full workflow. Bring your own Reactive Resume account and API key or browser login. Employer logins and email access are separate connections.

This repository contains instructions, not a hosted service or an implemented RX API connector. It guides the agent in using current documented APIs and available browser tools. Cover letters can be created in RX where supported, or as matching local documents otherwise. Authentication, CAPTCHA and some final actions may require your participation.

## Built-in boundaries

The agent preserves your master resume, checks account ownership, does not invent achievements, and asks for your employer-specific compensation decision. It obtains approval before final submission and records success only after receipt is verified. No ATS result, interview or offer is guaranteed.

## Share it

Share this repository link with your recipient. For a private repository, grant them repository access first; the URL alone does not grant access. Each recipient uses their own accounts and private career workspace.

## Status

Initial pilot version. Skill structure, references and archive integrity have been checked. A new user's end-to-end RX connection and application workflow still need testing in their environment.

The [complete skill package](rx-career-agent.zip) contains `SKILL.md`, three workflow references, interface metadata and sharing notes. All files are readable text; no executable installer or API keys are included.
