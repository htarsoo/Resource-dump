## Active Directory Mindmaps
* Two great resources to have by your side during any Pentest.
    * [https://raw.githubusercontent.com/Orange-Cyberdefense/ocd-mindmaps/main/img/pentest_ad_dark_2023_02.svg](https://raw.githubusercontent.com/Orange-Cyberdefense/ocd-mindmaps/main/img/pentest_ad_dark_2023_02.svg)
    * [https://github.com/eMVee-NL/MindMap/blob/main/image/Mindmap%20AD1.png](https://github.com/eMVee-NL/MindMap/blob/main/image/Mindmap%20AD1.png)

## Learning Active Directory
* Fantastic website that got me started on Active Directory.
    * [https://zer1t0.gitlab.io/posts/attacking_ad/#what-is-active-directory](https://zer1t0.gitlab.io/posts/attacking_ad/#what-is-active-directory)

## Learning Azure
* Although I do not have much experience with attacking Azure AD, I am going to share some resource here that can hopefully help you.
   * [Azure-Threat-Research-Matrix](https://microsoft.github.io/Azure-Threat-Research-Matrix/)
   * [https://github.com/Kyuu-Ji/Awesome-Azure-Pentest](https://github.com/Kyuu-Ji/Awesome-Azure-Pentest) - List of software and guides to help you.

## Digital Forensics and Intrusion Reports
* DFIR reports that you can read to learn about Domain compromise.
    * [https://thedfirreport.com/](https://thedfirreport.com/)
    * [https://thehackernews.com/2023/08/understanding-active-directory-attack.html](https://thehackernews.com/2023/08/understanding-active-directory-attack.html)

## Active Directory software for enumeration
* Some tools that I have used to enumerate environments
    * [CrackMapExec](https://github.com/mpgn/CrackMapExec) - One of the best tools out there for enumeration, gaining a foothold and post exploitation. Make sure to support the developer!
    * [Powershell Port Scanner](https://github.com/nccgroup/PS2)

## Active Directory software for initial compromise
* [Pretender](https://github.com/RedTeamPentesting/pretender) - LLMNR and IPV6 spoofer to help you obtain net-NTLM hashes. Works with other tools such as the Impacket suite. Check out their [blog](https://blog.redteam-pentesting.de/2022/introducing-pretender/#why-pretender-advantages-and-usage-scenarios) for more info.
* [Impacket suite](https://github.com/fortra/impacket) - Bunch of Python scripts that interact with Windows protocols like SMB to help you compromise hosts. Check out this [link](https://www.secureauth.com/labs/open-source-tools/impacket/) for information regarding each script.
* [CrackMapExec](https://github.com/mpgn/CrackMapExec) - CME can also be used for initial compromise using some of its modules such as PetitPotam.

## Active Directory Post Compromise
* [Some commands for enumeration](https://www.daronwolff.com/windows-enumeration-post-explotation/)
* [CrackMapExec](https://github.com/mpgn/CrackMapExec) - Can be used to check which devices you can access and dump creds.
* [Where to find further creds](https://www.alteredsecurity.com/post/fantastic-windows-logon-types-and-where-to-find-credentials-in-them)
* [Checklist for Windows privilege escalation](https://book.hacktricks.xyz/windows-hardening/checklist-windows-privilege-escalation)
* [Abusing AD Certificate Services](https://github.com/grimlockx/ADCSKiller)
* [64 methods to run mimikatz](https://redteamrecipe.com/64-Methods-For-Execute-Mimikatz/)
* [Deploying a VM from the command line](https://hackmag.com/security/windows-mitm/) - Useful if you compromised an endpoint via Phishing and want to deploy a VM to easily deploy tools like the impacket suite.
