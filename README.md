# Digital Profiler's Toolkit
![profiling](https://github.com/user-attachments/assets/e653f605-121a-4825-b5c8-37b3251f1226)

### This toolkit, useful for profiling, research, and digital investigations, was built for me and my trainees (profilers, fact-checkers, researchers and journalists). It contains only working and necessary tools. All are tested in real cases and are mostly free. The UI and CLI tools are separated.
### :eye_speech_bubble: For additional purposes use [Bellingcat’s Online Open Source Investigation Toolkit](https://bellingcat.gitbook.io/toolkit). It is awesome! 
### :vulcan_salute: Do you want to have a piece of training from me? Feel free to send a request in Russian or English on my [LinkedIn Service Page](https://www.linkedin.com/services/page/62913232ba4bb59a24/). Please find some free training and webinars in the OSINT Design section of this kit.
### :vulcan_salute: Get more tools and educational videos in Russian on [Provereno's Patreon](https://www.patreon.com/c/provereno).

## Table of contents:
 - [Research](#research)
 - [Target Identification](#target-identification)
 - [Arrange Your Findings](#arrange)
 - [Some Thoughts About OSINT Design and OPSEC](#osint-design)
 - [Professional Standards for Work and reports](#professional-standard)

## Research
**This section is useful not only for the profiler but in general for any journalist, fact-checker, or researcher**
### UI
- [Open Measures](https://public.openmeasures.io/timeline?searchTerm=qanon&startDate=2023-12-11&endDate=2024-06-10&websites=gab&numberOf=10&interval=day&changepoint=false&esquery=content&hostRegex=true). Ex-SMAT. Research in the list of sources
- [TGStat](https://tgstat.ru/x/XDPLu). From $20 monthly. Limited free options.
- [Perplexity](https://www.perplexity.ai). Very good for deep research
- [The Information Laundromat](https://informationlaundromat.com). Developed for propaganda research, but good in producing OSINT leads regarding the construction, sponsorship, and social media linkages of websites, regardless of their content's provenance
- [Domain Digger](https://github.com/wotschofsky/domain-digger)
- [Whoxy](https://www.whoxy.com)
- [American Registry for Internet Numbers](https://www.arin.net)

### CLI
- [SMAT](https://gitlab.com/openmeasures/smat-cli). Provides command line tools for getting data from the Social Media Analysis Toolkit (SMAT)
- [theHarvester](https://github.com/laramies/theHarvester). You should add APIs to make this tool useful
- [creepycrawler](https://github.com/paulpogoda/creepyCrawler). OSINT tool to crawl a site and extract useful recon info

### GitLists
- [OSINT Custom Search Engines](https://github.com/paulpogoda/OSINT-CSE)
- [OSINT Resources/Tools by Country V 2.0](https://github.com/paulpogoda/OSINT-for-countries-V2.0)

## Target Identification
**Names, nicknames, e-mails, phones, crypto wallets — find your target's digital footprint and connections**

### UI
- [OSINT Industries](https://app.osint.industries). The best UI available at the moment, for free for investigators and police
- [OnChain Industries](https://www.onchain.industries). Became a part of OSINT Industries in 2025
- [User Search AI](https://usersearch.ai). Free is not bad. $19 monthly subscription
- [WhatsMyName](https://whatsmyname.app). UI includes 2 CSE. 403 with some VPNs (unveil or use Tor in this case)
- [Epieos](https://epieos.com). From free to 1 euro for a full-access request
- [Intelligence-X](https://intelx.io/tools). From free to $20,000/year
- [Himera Search](). For Russia. Pay what you get (about $1-2 for a detailed report)
- [Hudson Rock](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools). Free cybercrime/infostealer intelligence toolset
#### Telegram
- [VkHistoryRobot](https://t.me/VKHistoryRobo). Free
- [ShaitanMachine Bot](https://t.me/shaytanmachineata_bot ). Paid
- [Telegram OSINT Bot catalogue](https://t.me/AllOSINTrobot). Search for the bots you need

### CLI
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [GoSearch](https://github.com/paulpogoda/gosearch). Sherlock analog in Go. Tool development in progress but it seems very perspective
- [Maigret](https://github.com/soxoj/maigret/blob/main/README.md). CLI is better than the official TG-bot, the local web interface available and it is not bad
- [WhatsMyName](https://github.com/WebBreacher/WhatsMyName). I use [this](https://github.com/C3n7ral051nt4g3ncy/WhatsMyName-Python) version
- [BlackBird](https://github.com/p1ngul1n0/blackbird). Searches for user accounts by username or email. It features WhatsMyName integration
- [GHunt](https://github.com/mxrch/GHunt). Brilliant for Google account research

## Arrange
**Where to keep your findings and/or create a final report**
### Free or Partially Free
- [Obsidian](https://obsidian.md). A customizable writing app from Micah Hoffman, aka [@webbreacher](https://github.com/WebBreacher), excellent and transparent interface. Available for any OS. A lot of plugins. Free for personal use. [Obsidian Templates are here](https://github.com/WebBreacher/obsidian-osint-templates/)
- [Osintracker](https://www.osintracker.com). Run in a browser. Don't forget to backup your findings. [Osintracker WIKI](https://wiki.osintracker.com/docs/overview)
### Partially Free or Paid
- [Maltego](https://www.maltego.com). From $2,500/year. Free Community Edition is available
- [Paliscope Explore](https://www.paliscope.com/explore/). Free Community Edition is available

## OSINT Design

### Operations Security (OPSEC)
Before you start, you have to think about operation security. It is about your security and all the people you work with and accidentally disclosing your target information without your permission. The main task is not to install tons of software on your machine but to change your behavior from insecure to secure. 

- Here's the [link](https://provereno.media/blog/library/pavel-bannikov-osnovy-personalnoj-kiberbezopasnosti/) to my webinar on Personal Cybersecurity Basics (in Russian). 
- [Introduction to OSINT](https://www.myosint.training/courses/introduction-to-osint) by Micah Hoffman and Griffin Glynn | Get a certificate! (In English)
- Otherwise, see [Aidan Rainey's webinar](https://drive.google.com/file/d/1gIU7w_qmU1TdYD-41l4gcBjZlVCNTEVv/view) (in English). 
- See also [this](https://github.com/Scrut1ny/OpSec-Guide) OpSec-Guide on GitHub. 
- [Step-by-step guide to building a custom machine for OSINT activities](https://github.com/Minotaur-OPSEC/OSINTMachineGuide)

### Some Thoughts About Making a Profile
It's best to start with one "don't." Don't create a profile "just because I can." Firstly, it's not always ethical, and secondly, it can lead you down the wrong path.
A good rule I've developed for myself, and which I try to follow, is this: I don't need more data than I actually require to solve a specific task.

A profile is always built around a specific task. When you're investigating a crime, searching for a missing person, or when you need to hire people whose views align with the company's mission, you will naturally include creating a psychological profile. But when your task is to determine if certain provided data is fraudulent, no psychology will likely be needed. Nor will linguistic analysis.

- Choose your tools according to the task. 
- Remember, not all tasks can be solved quickly, easily, or cheaply. There are always some tasks you won't be able to solve by yourself. 
- Learn from others; profiling is a constant learning process.

### Name|Nickname Research Alghorytms
![1690960219_1478178297](https://github.com/user-attachments/assets/974d6368-7a49-493f-a12c-a3903de1f3e7)
![1690960224_659397237](https://github.com/user-attachments/assets/a434b09c-07a9-4c0c-bf6c-bf05235177c7)

- Read: [How to find information on anyone: The best OSINT tools for people search](https://molfar.com/en/blog/how-to-find-information-on-anyone-the-best-osint-tools-for-people-search)
- Look at: [OSINT Framework](https://osintframework.com)

## Professional Standards
- [Ethical Frameworks in OSINT](https://www.dhs.gov/sites/default/files/2022-09/Ethical%20Frameworks%20in%20OSINT%20Final.pdf)

- [Principles For OSINT Professionals](https://www.osintfoundation.com/osint/Standards.asp)
![OSINTF Statement of Principles Inforgraphic](https://github.com/user-attachments/assets/b8f7808b-8cb6-4a4c-8d97-16e5c0721d3c)

- The Intelligence Community Standard (ICS) offers a framework designed to ensure consistency, accuracy, and professionalism across the U.S. Intelligence Community. It is clear and acceptable for use as guidance for OSINTers worldwide. ICS provides clear guidelines for processes, methodologies, and workflows, enabling intelligence professionals to produce reliable and credible outputs. For example, [ICS 206–01, effective December 2, 2024](https://www.dni.gov/files/documents/ICD/ICS-206-01.pdf), focuses on the proper citation and referencing of Publicly Available Information (PAI), Commercially Available Information (CAI), and Open Source Intelligence (OSINT)
- [UK OSINT Community Code of Conduct](https://www.osint.uk/community-code-of-conduct)
