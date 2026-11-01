# Marcus Shaw

I build things to understand how they work, then write down what broke.

Currently moving into IT infrastructure and support. Everything below is work I did myself, documented well enough that you can check it.

## Start here

**[Labs](https://github.com/marcshawco/Labs)** · Seven hands-on infrastructure labs in Microsoft Azure

An Active Directory domain with 10,000 scripted user accounts and a Group Policy lockout policy. A help desk built from an empty VM up through IIS, PHP and MySQL, with tickets triaged to closure. Packet captures across ICMP, SSH, DHCP, DNS and RDP, with a firewall rule written and proven to work. DNS caching demonstrated rather than described.

Every lab includes a troubleshooting section covering what actually went wrong, because that is the part that transfers.

## Also built

| Project | What it is | Built with |
|---|---|---|
| [ATHENS](https://github.com/marcshawco/Athenaeum) | Local-first macOS document library. Imports documents into a sandboxed vault, extracts searchable text, and answers questions across the archive with on-device retrieval. Nothing leaves the Mac. | SwiftUI, SwiftData, Vision, PDFKit, llama.cpp |
| [SIL](https://github.com/marcshawco/SIL) | iOS behaviour engine for structured goals and measurable progress. Successor to an earlier codebase, rebuilt around a calmer design language. | Swift, SwiftUI, WidgetKit, watchOS |
| [QA automation](https://github.com/marcshawco/python-selenium-automation) | End-to-end UI test automation across real consumer workflows, written as BDD scenarios with cross-browser and mobile-emulated coverage. | Python, Selenium, Behave, Allure, BrowserStack |

ATHENS is the one I would point at if you want to see how I handle a problem with real constraints. Running language models on a laptop means budgeting threads against performance cores, releasing multi-gigabyte memory under pressure, and cleaning up child processes that macOS will not kill for you. Those are not tutorial problems.

## What I work with

**Infrastructure** · Azure (virtual machines, virtual networks, network security groups, storage, resource groups), Windows Server 2022, Active Directory Domain Services, Group Policy, DNS, SMB and NTFS permissions

**Networking** · TCP/IP, DHCP, DNS, SSH, RDP, ICMP, VPN, packet analysis in Wireshark

**Scripting** · PowerShell, Python

**Support** · osTicket, ticket triage and escalation, SLA design, account lockouts and password resets, Event Viewer and log review

**Development** · Swift, SwiftUI, SwiftData, local LLM inference

**Testing** · Selenium WebDriver, Behave, Gherkin, Allure, BrowserStack

## How I work

I would rather verify something than assume it. In the labs that means pinging the host before joining the domain, checking `gpresult` before claiming a policy applied, and testing a share with a second account rather than the one already in hand.

When something breaks I write down what the error actually said, what I thought it meant, and what it turned out to be. Three of those are in the Active Directory lab. They are the most useful pages in the repo.

## Contact

Los Angeles, CA · [marcus@marcusshaw.com](mailto:marcus@marcusshaw.com) · [marcshaw.co](https://marcshaw.co)
