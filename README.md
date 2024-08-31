# EMC-2 Sample Dataset README

## Introduction

Hey there, and welcome to the EMC-2 Sample Dataset, a little project I've been cooking up to scratch an itch that's been bugging me (and probably you) for well over a decade.

I've been in the litigation and eDiscovery trenches since passing the bar, and in all that time, I've never come across a public dataset that really hits the spot for testing, demoing, or just playing around with eDiscovery and digital forensics tools. Sure, we've all used the Enron set, but let's be real - it's showing its age, and we're all a bit tired of it. (Pour one out for Andy Zipper.)

So, I decided to create something new. Something that tells a story. Something that's manageable, yet complex enough to be interesting. And yeah, something that's actually kind of fun to work with. Welcome to the Ellingson Mineral Company (EMC-2) dataset.

## Why EMC-2?

Look, we all know the Enron dataset. It's been the workhorse of eDiscovery for years. But here's the thing - our tools have evolved, our needs have changed, and frankly, we deserve better source material. Here's why EMC-2 might just be the refresh you've been waiting for:

1. It tells a story: Unlike the Enron emails, which can feel like reading someone else's grocery lists out of context, EMC-2 has a narrative. You can actually follow what's going on, which makes it great for testing tools that need to piece together a coherent timeline or spot key events.
2. It's manageable: At around 200 documents, it's big enough to be meaningful but small enough that you can actually review it yourself. Perfect for comparing your work to what your shiny new AI tool spits out.
3. It's got range: Emails, sure, but also chat logs, voicemails, and more. Because modern investigations aren't just about emails anymore.
4. It's synthetic: No ethical quandaries about using real people's private data. Analyze away without worry.
5. It's got easter eggs: There might be a prize in it for you if you dig deep enough. Just saying.

## Dataset Contents

Alright, let's break down what you're getting in this digital goodie bag:

### Custodians

1. Hal Benson (CEO) (I swear I didn't guide the AI to this name)
2. Dr. Sarah Chen
3. Eugene Belford
4. Dade Murphy
5. Margo Wallace
6. Kate Libby
7. Richard Gill
8. Jennifer Mack
9. jur1st

### Document Types

- Emails (with attachments, because who doesn't love attachments?)
- Internal memos and reports
- Chat logs
- Voicemail transcripts
- Press releases
- News articles
- Technical specs
- Financial spreadsheets
- Code snippets
- System logs

The whole shebang spans from about October 15 to October 25, 1995. Why 1995? Let's just say I might have been inspired by a certain movie. But don't worry, you don't need to know the film to appreciate the dataset. It's a self-contained story of corporate shenanigans, cyber threats, and the digital equivalent of "who dunnit?"

## How to Use This Data

The envisioned use is to take the data, feed it through the data analysis tool of your choice, and then play with it. I've processed the full set without processing errors, although there are a couple of files which may appear corrupt or strange.

## What Kind of Things are Inside the Data?

At the most basic level, this might be one of the most bizarre expressions of what I suppose is categorized as fan fiction of sorts but expressed through the most soul-crushing medium imaginable...someone else's email. Think of it as a short story told in a non-traditional medium if nothing else, and you don't need to know a darn thing about the movie to find it a quick, compelling, and dense narrative to pull facts and details from.

There are references and easter eggs that were intentional and unintentional. There's also something of a golden ticket that's stored inside here. If you find it, you let me know, and you may be immortalized on a wall of fame. First come, first served. In-person turn-ins might receive prizes and certainly will receive a high five.

## Limitations and Known Issues

- This is a small set of documents (at this point), so it's probably not suited for much extrapolation of a predictive model at scale. If it is, someone's welcome to correct me, but making something that is statistically defensible is not the intention.
- The types of native files currently are limited to plain text, though that also remains the current state of the art for most legal-specific tools I've taken a look at so far.
- Metadata for CSV and TXT documents presently have no time metadata, which impacts the set's ability to sort chronologically within days.
- While this got seeded with things from the movie, this is not and isn't intended to be some kind of detailed stand-in. We get broad arcs, main characters, motivations, that kind of thing.

## Technical Details

The dataset was implemented using a combination of human creativity and AI assistance:

- Initial taxonomies of different elements of the universe that exists in the seminal 1995 film, Hackers, at first as kind of a gag. Then the results started coming out and things escalated to sciencey things quickly.
- AI models were used to expand on these outlines, generating consistent and varied content.
- Human review and editing ensured quality, coherence, and adherence to the storyline.
- Technical details (e.g., code snippets, log files) were double-checked for accuracy along the way.

This hybrid approach allowed us to create a dataset that combines the creativity and nuance of human-generated content with the scale and consistency made possible by AI.

This hybrid approach allowed us to create a dataset that combines the creativity and nuance of human-generated content with the scale and consistency made possible by AI.

## Dataset Contents

The Ellingson Mineral Company Synthetic Dataset comprises a rich tapestry of documents that tell the story of a corporate cyber attack and its aftermath. Here's an overview of what you'll find:

### Custodians

1. Hal Benson (CEO) (I swear to you I didn't guide Claude to this name)
2. Dr. Sarah Chen 
3. Eugene Belford
4. Dade Murphy
5. Margo Wallace
6. Kate Libby
7. Richard Gill
8. Jennifer Mack
9. jur1st 

### Document Types

1. Emails (including attachments)
2. Internal memos and reports
3. Chat logs
4. Voicemail transcripts
5. Press releases
6. News articles
7. Technical specifications
8. Financial spreadsheets
9. Code snippets
10. System logs

### Timeline

The main events of the dataset span from approximately October 15 to October 25, 1995, with some documents providing background context from earlier dates.

### Key Themes

1. Corporate espionage and insider threats
2. Cybersecurity and hacking
3. Financial fraud
4. Legal and ethical dilemmas
5. Media relations and crisis management

### Sample Document: Email from The Plague

```
From: eugene.belford@offshore-secure.net
To: margo.wallace@ellingson.com
Subject: It's Time
Date: Tue, 10 Oct 1995 15:20:10 -0400

M,

I've submitted my resignation. Two weeks from now, we'll be sipping mai tais on a beach while Ellingson burns. Make sure everything is in place on your end.

Remember, if anyone gets suspicious, you know nothing. As far as you're concerned, I'm leaving for a better opportunity elsewhere.

- E
```

This email exemplifies the type of incriminating evidence hidden within the dataset, challenging users to uncover key information amidst a sea of routine corporate communications.

## Technical Specifications

The Ellingson Mineral Company Synthetic Dataset is designed to be compatible with a wide range of eDiscovery and analysis tools. Here are the key technical details:

### File Formats

- Emails:  mbox files split per custodian
- Attachments: .txt, .csv 
- Standalone documents: .txt, .csv

### Metadata

Each email includes standard metadata fields and is known to thread properly:

- Date Created
- Date Modified
- Author
- Recipients (for emails)
- Subject (for emails)
- File Size
- File Type

### Dataset Size

- Total Documents: Approximately 200
- Total Size: Approximately 200kb. Yeah, you read that correctly. Can we go back to using Pine for email now? 

### Contents

```
EMC-2/
├── LICENSE.txt
├── README.txt
├── edocs
│   ├── Da_Vinci_virus_analys.txt
│   ├── budget.csv
│   ├── da_vinci_vir_core.c.txt
│   ├── diff.txt
│   ├── gibson_security_patch.txt
│   ├── hacker_chatlog.txt
│   ├── irc_htp.txt
│   ├── memo_10101995.txt
│   ├── nytimes_article_ellingson_hack.txt
│   ├── plague_voicemail_transcript.txt
│   ├── talk_log.txt
│   ├── talk_log2.txt
│   ├── traffic_report.txt
│   ├── ts_phone_log.txt
│   ├── virus_rpt_cyber.txt
│   └── vm_0827.txt
└── email
	├── DOJ_EmailFile.mbox
	├── dmurphy.mbox
	├── ebelford.mbox
	├── hbenson.mbox
	├── jmack.mbox
	├── jur1st.mbox
	├── klibby.mbox
	├── mwallace.mbox
	├── rgill.mbox
	└── schen.mbox

3 directories, 28 files

```

## Contact Info

If you enjoy this or find it useful, let me know by dropping me a line over email (john at john-benson dot com) and letting me know what you do with it. Heck if you want to take the concept and run with it on your own that's fine too. If nothing else this proves that there's no darn reason that we need search or summarize Andy Fastow's email or scratch your head Jeb(!)'s use of "FUP" as an abbreviation for follow-up. To paraphrase the last best hope we had before this at solving this problem...please clap? 👏

