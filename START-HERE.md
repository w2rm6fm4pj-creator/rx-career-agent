# Start here: your personal career assistant

**English** · [Deutsch](START-HERE-DE.md)

You do not need to code, use a terminal, or understand GitHub. This package gives your AI assistant a repeatable career workflow. You bring your experience and make the important decisions.

The first session is successful when the assistant understands your goals, verifies your own RX Resume account, and creates a resume draft you can inspect. Start with one application before relying on the whole process.

## 1. Get the package

Open this repository, click **rx-career-agent.zip**, then use its download button. Keep that ZIP in Downloads. Download the skill ZIP itself, rather than GitHub's ZIP of the entire repository.

If the repository will not open, ask the person sharing it to grant access. You can also ask them to send you the skill ZIP and this guide directly; you do not need GitHub for that route.

## 2. Choose your assistant

### Option A: Codex on your computer

This is the starting route for the workflow developed here. Open your desktop app and select Codex; current OpenAI instructions describe selecting it from the ChatGPT dropdown. Choose **Local** for work on your computer. [Official setup reference](https://learn.chatgpt.com/docs/environments/modes)

Create a private folder named **My Career** on your computer. Open it as a local project in the app using its project/open-folder control. This is where your profile, drafts and application records will live. It should be separate from the downloaded sharing repository. A regular online ChatGPT project does not automatically provide access to local folders. [Projects explained](https://learn.chatgpt.com/docs/projects)

In that project, paste this message and tell the assistant where the downloaded ZIP is:

> Help me set up RX Career Agent. I am not technical. The skill ZIP is in my Downloads folder. Inspect it, install the enclosed rx-career-agent folder as a project skill in .agents/skills, and verify that its references are present. Keep my personal career records private in this project. Tell me if I need to start a new task for the skill to appear. Then check which research, resume, PDF and browser tools are available. Explain any missing setup one step at a time.

Let the assistant handle the folders. Once installed, start a fresh task in this project if needed and say **Use $rx-career-agent to help me get started.** Skills are reusable instructions discovered by the app. [Official skill guide](https://learn.chatgpt.com/docs/build-skills)

If your app has different menus or no Codex option, use the official reference above or the Claude route below. Account and organization settings can affect available features.

### Option B: Claude

In Claude, enable **Code execution and file creation** under **Settings → Capabilities** if needed. Open **Customize → Skills → + → Create skill → Upload a skill**. Upload **rx-career-agent.zip** and enable it. Organization policies may restrict this. [Claude installation instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

Start a conversation and say:

> Use the rx-career-agent skill. Help me set up my own RX Resume account and career workflow one step at a time. First check whether you can research jobs, connect to RX, create and inspect PDFs, and operate application websites. Tell me which steps you can perform and which I will need to do myself. Do not ask me to upload an API key into this conversation.

The skill format is compatible with Claude. This package's complete Claude workflow has not yet been tested. Installing a skill alone does not connect accounts or enable browser control. If an action is unavailable, the assistant should still prepare the content and guide your manual step.

### What about ordinary ChatGPT chat or Work?

You can use chat to review your resume and discuss opportunities. For the full workflow, use a setup that actually exposes the skill and the required tools. This ZIP is a standalone skill, not a published ChatGPT plugin; uploading it into an ordinary conversation is not proof that installation or automation is enabled.

## 3. Create your own RX Resume account

RX Resume is also called **Reactive Resume**. Open [rxresu.me](https://rxresu.me) and follow its registration/sign-in prompts. Use your own email or offered sign-in method. Complete any verification yourself and keep your login in your password manager.

Tell the assistant:

> I need help setting up Reactive Resume. Open the official site if you can, walk me through the screens, and let me handle my password and verification. Once I am in, verify that this is my account before changing anything.

Already have an account? Sign in rather than creating another. If a family member is signed in, switch accounts. The assistant must check account ownership, not just recognize a resume title. An empty account is fine: your first resume can be built from your existing document after the profile interview.

## 4. Connect RX to your assistant

### First choice: sign in through a connection

Ask the assistant whether your app supports RX's official sign-in connection. RX documents a remote connection at **https://rxresu.me/mcp**, including a Claude custom-connector route. Where supported, add it through your app's connection settings and sign in to RX. The assistant should guide the current screens and verify access. This can avoid handling a key. [RX's connection instructions](https://docs.rxresu.me/guides/using-the-mcp-server)

### Alternative: a private API key file

An API key is a password-like credential that lets the assistant work with your RX account. It is an **RX key**, not an OpenAI or Anthropic key.

1. In RX, open **Settings → API Keys**.
2. Choose **Create a new API key**. Name it **My Career Assistant**, choose an expiry, and create it.
3. Copy the secret when it appears; RX displays it only once. [RX's API instructions](https://docs.rxresu.me/guides/using-the-api)
4. If your assistant provides a secure credential field, use that. Otherwise, for an assistant with local file access, save the key alone in a private plain-text file named **RX-Resume-Key.txt**. On Mac, use TextEdit and choose **Format → Make Plain Text** before saving. On Windows, use Notepad. A private local folder is preferable; Desktop is usable if it is not shared, but may sync to your cloud account.
5. Tell the assistant the file location, not its contents. For example:

> My RX API key is in RX-Resume-Key.txt on my Desktop. Use it privately to connect to my Reactive Resume account. Do not display it or put it in logs, generated documents or GitHub. Verify whose account it accesses before making changes.

A website chat cannot read your Desktop just because you name a file. If the assistant cannot access it, use a supported secure connection or a local assistant. **Do not upload the key file as a chat attachment or add it to the shared skill.** A local file is a storage choice, not a guarantee that the AI service never processes the credential; the assistant should keep the value out of model-visible outputs.

If you lose the key, create another. If it was exposed, revoke it in RX and replace it. You do not need to send the key to the person who shared this guide.

**Connection checkpoint:** the assistant confirms a successful read and whose account it accessed. It then verifies a new draft or duplicate without altering your master. Merely saving a key does not establish a connection.

## 5. Build your profile and resume

Provide your current resume and, if useful, a portfolio or LinkedIn profile. Say:

> Analyze my resume first, then interview me in small rounds. Help me explain what I have actually done, what outcomes I can support, and what work I want next. Ask about location, travel, remote work, relocation, seniority and compensation. Preserve my preferred design and keep the original resume unchanged.

Correct the assistant if it exaggerates a claim. You should receive a positioning brief, search criteria and a draft in your own RX account. Inspect the actual exported PDF. The assistant should check readable text, layout and file size; an ATS score cannot guarantee acceptance.

## 6. Try one real application

> Find a short list of verified live opportunities matching my profile. Separate how much I would want each role from how well I fit it. Explain major gaps and unknowns. Check my application history so we do not apply twice.

Choose a role. Then say:

> Prepare this application, tailor a copy of my resume and a cover letter, and check the final PDFs visually and for readable text. Research compensation and ask for my salary decision. Complete the form and attach the documents if your tools allow it. Pause immediately before submission and show me the completed package.

You handle employer account creation, verification and any questions the assistant cannot truthfully answer. Approving a salary for one employer does not approve it for every employer. When satisfied, explicitly approve that completed application. The assistant should verify a confirmation before recording it as submitted; a saved draft is not a receipt.

## 7. Keep using it

Return to the same private project or saved career records. Useful requests:

- “Resume from my saved working state and show me what needs attention.”
- “Search for new opportunities and include these job-alert emails.”
- “Prepare applications for the first two roles; research salary first.”
- “Record this response and help me prepare for the interview.”
- “Save today's decisions and the next step before we stop.”

Email access and scheduled searches require separate setup and authorization. The assistant does not run continuously just because you installed the skill.

## If something goes wrong

| What you see | What to do |
| --- | --- |
| Skill is missing | Check installation/enablement, then start a new task. Ask the assistant to verify the installed files. |
| RX shows someone else's account | Stop edits and sign into yours. Verify the API account separately. |
| “Cannot read the key file” | Use a supported connection or grant the local assistant access to the exact file. Do not paste the secret into chat. |
| “Unauthorized” from RX | Check expiry, account and connection; replace an expired key or reconnect. |
| Cannot operate the employer website | Use the prepared documents and follow the assistant's manual instructions. |
| Submission timed out | Check the portal/receipt before retrying to avoid duplicate applications. |

This is a pilot workflow. Tools, subscriptions and organization settings differ. The first real setup is also a compatibility test; record what actually worked.
