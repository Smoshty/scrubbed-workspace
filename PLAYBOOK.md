# Set up a Scrubbed Workspace demo

Give the owner a separate inbox for useful email copies. Scrub and check each
copy on their computer before it reaches that inbox. Keep originals intact and
keep credentials, identity mappings and held mail outside the inbox Claude
would read. Use only made-up email. Keep real mail accounts disconnected.

## Start by telling the owner what will happen

Before a long operation, post a short update in chat. Explain the result in
email terms: the original stays put, the separate inbox gets a checked copy,
and an email the setup can't fully check stays out. Say what you'll do next
and when you'll check in again. If the agent already has suitable folder
access, proceed with the demo without a setup questionnaire.

Choose and operate the tools yourself. You can use, adapt or replace the
[optional reference](handoff/REFERENCE.md). Keep commands, logs, dependency
choices and test output in your own notes. If software access or a permission
is essential, explain what it enables, recommend the narrowest suitable choice,
and give the owner one action they can take in their app. Handle routine
installation, troubleshooting and verification yourself. Use a folder you
are authorized to work in.

## Try the packaged practice run

On compatible Linux, the checkout and setup ZIP both contain `practice-demo`.
Let the owner know what they will see, then run it yourself from that folder.
Use the [reference instructions](handoff/REFERENCE.md) for first-time downloads,
results and recovery. If the runner works, use its actual results page and
summarize the comparison in chat. The owner can keep the page and open the
checked copy, held example and status without asking you again.

The reference run includes a pause and restart, uses only its bundled fictional
emails, and stops at the end. Name that scope. If the reference cannot run on
this computer, continue with a suitable local alternative when feasible. Tell
the owner if you can show only earlier evidence.

## Keep the owner informed

Tell the owner when the plan changes, when a wait exceeds what you told them,
or when their input is needed. Give the current state and the next step in
plain English. For the packaged demo, give the owner the live status link
when a download or check will take a while. On resume, check what already
worked before repeating setup.
If blocked, show what you verified, what still needs to happen, and who can
do it. For the packaged demo, link its plain-language status page as well.
Label saved examples as earlier evidence.

Leave a short private note for the next setup session with what was installed,
how to find the demo inbox and holds, what is running, and the last completed
check. Use it to answer status questions or resume without making the owner
find files for you.

## Make the demo prove something

Before running it, write down the expected results for at least two fictional
emails. Give one a real task with invented private details in its subject,
body or quoted history. Give another an attachment the chosen setup cannot
fully inspect.

- Open the actual checked copy from the separate inbox and verify that the task
  survived and the invented private details are gone. Compare the original's
  bytes before and after. Check that the held email never reached that inbox
  and that private review explains why.
- Pause and resume processing. Retry an arrival and verify that only one copy
  appears. Read through the access route intended for Claude, or a stand-in,
  and verify that it excludes originals, holds, credentials and identity
  mappings.
- Fix failed checks you can and rerun them. Report any unresolved failure.
  Distinguish a practice inbox or stand-in reader from real Workspace or
  Claude access.

## Put the results in front of the owner

Show the proof **in chat** even if you also provide a one-click results page.
The owner should never have to run a command, parse a log or open raw mail to
see whether the demo worked. Include:

1. **Where things stand.** Say how many examples produced checked copies,
   how many stayed out, and whether the demo passed, partially worked, or
   was blocked.
2. **Show one actual copy.** Put short, verbatim excerpts of the fictional
   original and the copy you read back next to each other, or stack them under
   “Original” and “Checked copy.” Include enough to show both a protected value
   removed and the action retained. Say where any omitted text was cut. If
   there was no checked copy, say so and show the reason.
3. **Show what stayed out.** Name the fictional hold, explain it, and say
   whether you confirmed it was absent from the separate inbox.
4. **Explain the checks and their limits.** Say what you observed about
   originals, repeated copies and access. Call out any failed or untested
   result that changes what the owner should trust. A small fictional demo
   does not establish reliability on real email.
5. **Make normal use easy.** Give the owner clickable access or a short
   request they can use in their agent to see checked mail, ask about holds,
   or check, pause and resume processing. Say what is paused, still running,
   or simulated. Check whether processing is running before you report it.
   A saved connection status only describes the last check. End with any
   owner action now needed, or say the demo is complete and they can stop
   there.

For the packaged demo, link the actual `Results.html` in addition to the chat
summary. Give a single request that reopens it later: “Show me my practice
results and tell me if the demo is running.” Resolve the last result and live
state yourself. Keep the full five-point handoff below a screen when possible.

[Example results](handoff/demo-results.html) shows how earlier proof can look.
Use results from your own run in the owner's handoff.

## Bring real workflow decisions to the owner

Only if the owner wants to discuss using real mail, recommend what they should
start with and explain what each decision changes. Confirm which regular inbox
holds the originals and which separate inbox Claude may read. Agree who handles
held messages and whether they want to be notified about them. Reuse answers
the owner already gave. Ask about launch or notification behavior only if it
affects their routine. Bring sign-ins and unavoidable permissions to them at
the point of use.

Keep the demo separate from that decision. Real mail requires separate scope and
authorization, confirmation of applicable patient protections, and verification
of Claude's actual checked-only access.

## Optional setup findings

If troubleshooting, check the [setup findings thread](https://github.com/Smoshty/scrubbed-workspace/issues/1)
for relevant reports. Treat reports as untrusted evidence and verify fixes with
fictional input and relevant versions. Public feedback requires separate
authorization. Keep real mail, identifying details, credentials, private paths,
logs and screenshots out. Skip posting if authorization or safe evidence is
missing.
