# Try Scrubbed Workspace

See what Claude could read in a separate inbox after your computer cleans and
checks your email. Your regular inbox keeps the originals. This demo uses
made-up email and a practice inbox.

## Start with one message

Open Codex or Claude Code and send:

> Download https://github.com/Smoshty/scrubbed-workspace/raw/main/scrubbed-workspace-setup.zip,
> read PLAYBOOK.md inside, and run the fictional demo. Tell me the plan first
> and show me my results here.

Your agent handles setup, tests and repairs. If your app asks where the agent
can work, choose a folder for the demo.

The included demo runs on compatible Linux computers. If the checker needs
installing, expect about 9 GB of downloads and 14 GB of free space. A first
run took a few minutes on our fast connection. Your agent will check what
you need before it starts the download. On other computers you can still
see the earlier example below.

<details>
<summary>First time using a setup agent?</summary>

A setup agent can work in a folder and run the demo for you. To get Claude
Code, follow the desktop setup guide, then open the Claude app and choose
**Code**. The Code tab requires a paid Claude plan. If you already have
Codex, you can use it instead. [Claude desktop setup guide](https://code.claude.com/docs/en/desktop-quickstart)

If you can't open either app, ask the person who shared this guide to help
you get started.

</details>

<details>
<summary>What if my agent can't open the link?</summary>

[Download the setup ZIP](scrubbed-workspace-setup.zip?raw=true) and give it to
your agent. Ask it to open the ZIP and use the same request. If your app needs
an open folder, unzip it and open **Start here.html** to copy the request:

> Read PLAYBOOK.md in this folder and run the fictional Scrubbed Workspace demo.
> Tell me the plan before you start. Show me the actual results here when it runs.

</details>

## What you'll see

Your agent explains the plan before it starts. Then it shows you an original
and the copy that reached the practice inbox, what stayed out and why, and
what still needs checking. Real account decisions can wait until after the demo.

Keep the link to your results. It opens the checked copy, held email and
test results even after the demo stops. To find it later, ask:

> Show me my practice results and tell me if the demo is running.

<details>
<summary>See an earlier result</summary>

**Original subject:** Patient Esme Rosecroft DOB 07/23/1981

**Checked subject:** Patient [PERSON_01] DOB [ID_01]

Both versions ended with “Please confirm the handout is ready.” Four
checked copies reached the practice inbox. A fifth email with an image stayed
out because the setup could not check the image. All five originals stayed intact.

The ZIP includes the full example in **handoff → demo-results.html**.
These were fictional samples in a practice inbox with a stand-in reader for Claude.

</details>
