# hey, I'm Miralem

> *Code in the morning,*<br>
> *armbars in the afternoon,*<br>
> *poems after dark.*

That's most days. The code part is GTM engineering, which mostly means making
sure cold email lands in the inbox and not next to the "you've won an iPhone"
ones. Lists, domains, DNS, copy, replies, all of it. I sent 80M+ emails in
2026, and when something breaks twice, I write a tool so it can't break a
third time.

## stuff I built

### [micsnitch](https://github.com/miralemalic/micsnitch)

Your phone asks before an app uses the mic. Linux never did, so now it does.
Any app that tries to record your mic or system audio gets stopped, and you get
a popup to allow or deny it. GNOME, KDE Plasma, Sway, Hyprland, niri, COSMIC.

<p align="center">
  <a href="https://github.com/miralemalic/micsnitch"><img src="https://raw.githubusercontent.com/miralemalic/micsnitch/main/docs/popup.png" width="380" alt="micsnitch asking whether to let an app use the microphone"></a>
</p>

<p align="center">
  <a href="https://github.com/miralemalic/bouncesitrep"><img src="bouncesitrep.gif" width="33%" alt="bouncesitrep reading a 79,800-lead campaign export: the bounce rate, the bounces split by whose problem they are, and what to do about each"></a>
  <a href="https://github.com/miralemalic/inboxsitrep"><img src="https://raw.githubusercontent.com/miralemalic/inboxsitrep/main/docs/demo.gif" width="63%" alt="A walk through the Inbox Sitrep app"></a>
</p>

### [bouncesitrep](https://github.com/miralemalic/bouncesitrep)

Point it at any sequencer's bounce export and it tells you whose problem each
bounce is: your list, your domains, your DNS or your copy. Then what to do
about each one.

Most bounce tools stop at hard vs soft, which doesn't tell you much. A dead
address and a blocked domain are both "hard", but one means clean your list
and the other means stop sending from that domain right now.

Built on 250k+ real bounce messages from 50+ workspaces and almost 1,500 sending domains. If you
send real volume, you want this. One Python file, no dependencies.

### [Inbox Sitrep](https://github.com/miralemalic/inboxsitrep)

Cold email has way too many moving parts. Domains, mailboxes, warmup,
SPF/DKIM/DMARC, blocklists, bounce rates, merge fields that break the second
you hit send. Most people starting out juggle five tabs and a spreadsheet and
still miss the one thing that's on fire.

Inbox Sitrep puts all of it on one page. Every few hours it checks your setup
and tells you what's broken, why, and what to do about it. Approve the fix and
it does it for you, with an undo. It also tells you how many domains to buy
before you run out, warns you before a campaign runs out of leads, and catches
broken copy before it sends. Every morning there's a short report waiting in
Slack or Telegram.

PlusVibe, Instantly and EmailBison. Desktop app, Claude Code plugin or MCP
server. Tested on 15+ workspaces and 200k+ mailboxes.

## off the clock

- **OSINT, cybersecurity, intelligence.** Finding an email no database has is
  basically OSINT with a quota, so this one was always going to happen.
- **Wrestling, BJJ, MMA.** The armbars in the haiku are real.
- **Amateur poet.** Hence the haiku. Most of my published work has
  `{three|four}` variants per line.
- **Linux and privacy stuff.** Fedora and Pop!_OS, on ThinkPads, always
  ThinkPads. GrapheneOS on the phone, and a MikroTik that grabs
  every DNS query in the house. On purpose.

## what I use

Python, SQL, n8n, Clay, Claude Code, Codex, and a long list of others. I'd
type them out, but it's after dark and I have poems to write.

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/miralem-alic-094497250/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+Cg==" alt="LinkedIn"></a>
</p>

<p align="center"><sub>thanks for reading. unlike most cold emails, this one doesn't need a reply.</sub></p>
