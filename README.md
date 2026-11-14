# Miralem Alic

GTM engineer · CET (UTC+1)

I closed 100+ B2B deals as a co-founder. I build cold email end to end, from
domain setup to the positive reply.

## About

In 2022 I co-founded a small outbound agency. I set up its outbound from
scratch, cold email and cold calling to 25,000+ decision-makers at an 8%
average reply rate, ran the campaigns, and sold in the biggest meetings they
booked. That was before GTM engineer was a job title.

As a GTM engineer I've handled everything from the lead list to the replies,
with AI agents answering the replies, for up to 12 clients at a time:

- **Leads:** scrapers for SAM.gov, state business registries, freight load
  boards, Overture Maps, Angi and Yellow Pages. Email permutations for
  businesses no database covers. Enrichment from databases of up to 18
  million rows.
- **List hygiene:** company names cleaned so they read naturally in a
  sentence; past bounces, repliers, do-not-contact lists and addresses known
  to bounce taken out before every upload.
- **Campaigns:** copy, spintax and A/B variants, checked for broken merge
  fields before they send. Lists split by the prospect's email provider.
  Follow-up rounds that re-send with a fresh variant. All built and loaded
  through the API.
- **Infrastructure:** domains, mailboxes and warmup pools for clients sending
  millions of emails a month.
- **Deliverability:** blocklists, burned domains and authentication, and
  catching what breaks before it reaches the other domains or the warmup
  pools.
- **Replies and CRM:** the AI agents that answer replies, n8n workflows, and
  CRM integrations and reporting.

## Results

- **23,000+ positive replies for two clients.** For one, 1.48 million
  emails: 4.7% reply rate, 12,766 positive replies, 1.7% bounce rate. For
  the other, in a single month, 1.24 million emails: 3.2% reply rate, 34.2%
  of replies positive (10,582), 1.4% bounce rate.
- **$25M+ in contracts for clients.** At the agency I co-founded, our
  campaigns booked the meetings and I joined the big ones to close them:
  100+ deals, the largest over $400k.
- **Leads nobody else is emailing.** I build lists from SAM.gov, state
  business registries, freight load boards, Overture Maps and trade
  directories. Where a business has no listed email, I work out its likely
  address and verify it. None of these are in Apollo or ZoomInfo, so nobody
  else is emailing them. On one client, scraped and open-data sources got 4.3
  to 6.1 interested replies per 1,000 emails; bought databases got 1.8 to
  2.9.
- **Every campaign split by the prospect's email provider.** Gmail,
  Microsoft 365 and other ESPs filter mail differently, so I split each list
  by who hosts the inbox and run each part as its own campaign, with its own
  volume and senders. The largest build: 1.75 million leads across 24
  campaigns.
- **Problems caught before they spread.** Blocklistings, Microsoft blocking
  a whole tenant, Gmail quietly filing mail as spam: I find them early and act
  before they reach the rest of the domains or the warmup pools. Inbox
  Sitrep, below, is that work turned into software.

## What I built

### [Inbox Sitrep](https://github.com/miralemalic/inboxsitrep)

Checks a cold email setup every few hours: which domains and campaigns have a
problem, why, and the fix, which it applies from the app with an undo. Tells
you how many domains to buy before you run out, and catches broken copy
before it sends. PlusVibe, Instantly and EmailBison. Desktop app, Claude Code
plugin and MCP server. Built, used and tested on 15+ workspaces and 200,000+
mailboxes.

<a href="https://github.com/miralemalic/inboxsitrep"><img src="https://raw.githubusercontent.com/miralemalic/inboxsitrep/main/docs/demo.gif" alt="Inbox Sitrep" width="100%"></a>

### [bouncesitrep](https://github.com/miralemalic/bouncesitrep)

Reads any sequencer's bounce export and says who has to fix each bounce: your
list, your domains, your DNS or your copy, and what to do about it. Built on
254,054 real bounce messages from 8 workspaces and 1,482 sending domains. It
reads 99.7% of them, and 99.4% of a workspace it never learned from.

<img src="bouncesitrep.gif" alt="bouncesitrep reading a 79,800-lead campaign export: the bounce rate, the bounces split by whose problem they are, and what to do about each" width="400">

### Smaller tools

- [**mkcsv**](https://github.com/miralemalic/mkcsv) turns database dumps and
  text with an unknown delimiter into clean CSV.
- [**micsnitch**](https://github.com/miralemalic/micsnitch) asks before any
  app records your microphone, on Linux.

## Tools

Python, SQL (DuckDB), REST APIs and webhooks, n8n, Claude Code and Codex.
Clay, Apollo, ZoomInfo, Sales Navigator. PlusVibe, Instantly, EmailBison.
HubSpot, Salesforce, GoHighLevel. SPF, DKIM, DMARC, blocklists, Gmail and
Microsoft filtering.

## Contact

[LinkedIn](https://www.linkedin.com/in/miralem-alic-094497250/)
