# PWPP Study Plan

## Introduction
Hello! In early 2025, <a href="https://www.linkedin.com/in/shawn-szczepkowski">Shawn</a> and <a href="https://www.linkedin.com/in/angsec">myself</a> created a plan and ran a study group as we prepared for TCM Security's Practical Web Pentest Professional (PWPP). We hope that this will help folks in the future to land this cert! If this page is incomplete, we are currently running the study group on the <a href="https://discord.gg/GYBUtkUCyF">f0xhunt Discord server</a>. 

There are a couple affiliate links here. If you by chance benefitted from the education plan we've put together please consider using them or paying it forward with mentorship to others as they come up. <3 <br><br><br>

## **To Do Before you Begin**
Set up an account with PortSwigger <br>
https://portswigger.net/web-security <br><br>
Set up Juice Shop <br>
https://pwning.owasp-juice.shop <br> <br>
Set up a TryHackMe (THM) account (referral) <br>
https://tryhackme.com/signup?referrer=5fc50abdccbc930779bcc40e <br><br>
Set up a HackTheBox (HTB) account (referral) <br>
https://referral.hackthebox.com/mzBESgu<br><br>
Set up a Quizlet account <br>
https://quizlet.com <br><br><br>

## **A Note on TCM Courses and Certification**
You can get the courses with the <a href="Head to All Access Management Product Page">All-Access Membership</a> or when you purchase the certification. <br>
If you purchase the cert, please consider using Shawn's referral code: <br>
https://certifications.tcm-sec.com/?ref=161 <br><br><br>

## Educational Topics and Plan
The following topics are taught within the <a href="https://academy.tcm-sec.com/p/practical-web-hacking"> Practical Web Hacking</a> and <a href="https://academy.tcm-sec.com/p/hacking-apis">Practical API Hacking</a> courses, and will have sections below: <br>
- **How web applications work** <br>
- **Authentication attacks** <br>
- **Broken access control** <br>
- **Server-side request forgery** <br>
- **Advanced SQL injection attacks and NoSQL injection** <br>
- **File inclusion** <br>
- **XML External Entity Injection** <br>
- **XSS and filter bypasses** <br>
- **Attacking JSON Web Tokens** <br>
- **Mass assignment** <br>
- **Open redirects** <br>
- **Race conditions** <br>
- **Enumerating APIs** <br>
- **Chaining vulnerabilities** <br><br>

We do suggest you do everything in each section! Sections will direct the learner to do both the segment within the TCM course and also provide additional videos, reading, and labs to fully learn the topic. 
As a last note, we have tried to keep the plan low to no cost but it is possible that the labs included will not all be free. 
<br><br><br>

## **Section 1 - How web applications work** <br>
- Complete the section "Introduction" in the TCM Practical Web Hacking course
  - Deep Dive: Web App Basics
  - Deep Dive: Web Application Components
  - Deep Dive: HTTP Basics
<br><br>

*Web App Basics*
- Video
   - The "Web Demystified" series from Mozilla Hacks: https://www.youtube.com/playlist?list=PLo3w8EB99pqLEopnunz-dOOBJ8t-Wgt2g
- Read/Write
   - Read & take notes: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works
   - Read & take notes: https://rinaarts.com/the-absolute-beginners-guide-to-web-applications/
   - Look up image searches like "website diagram" or "web basics diagram", find a few that from trusted sources and make your own in your notes.
- Labs
   - THM room "How Websites Work": https://tryhackme.com/r/room/howwebsiteswork
   - THM room "DNS in Detail": https://tryhackme.com/room/dnsindetail
   - THM room "HTTP in Detail": https://tryhackme.com/room/httpindetail
<br><br>

*Web Application Components*
- Video
   - ForrestKnight's "Everything You NEED to Know About WEB APP Architecture": https://www.youtube.com/watch?v=sDlCSIDwpDs
- Read/Write
   - Read & take notes: https://docs.oracle.com/cd/E13222_01/wls/docs81/webapp/basics.html
- Lab
   - HTM "Introduction to Web Applications": https://academy.hackthebox.com/module/75/section/719
<br><br>

*HTTP Basics*
- Auditory
   - Hackersploit's "Web App Penetration Testing - Introduction To HTTP" : https://www.youtube.com/watch?v=TvRyJmPjcbw
- Read/Write
   - Read & take notes: https://www.freecodecamp.org/news/secure-your-web-application-with-these-http-headers-fd66e0367628/
   - Read & take notes: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
- Lab
  - THM room "HTTP in Detail": https://tryhackme.com/r/room/httpindetail
<br><br>

*Optional Extra Work:* <br>
This three part series is great - if you want to solidify your knowledge:
- Part 1: https://www.freecodecamp.org/news/how-the-web-works-a-primer-for-newcomers-to-web-development-or-anyone-really-b4584e63585c/
- Part 2: https://www.freecodecamp.org/news/how-the-web-works-part-ii-client-server-model-the-structure-of-a-web-application-735b4b6d76e3/
- Part 3: https://www.freecodecamp.org/news/how-the-web-works-part-iii-http-rest-e61bc50fa0a/ 
<br><br>

*Other Resources:* <br>
<a href="https://quizlet.com/816442633/web-basics-flash-cards/?funnelUUID=a0174714-fa96-457f-937b-2b50d58a0b81">Web Basics Flashcards</a>
<br><br><br>

## **Section 2 - Authentication attacks** <br>
- Complete the section "Authentication" in the TCM Practical Web Hacking course
  - Deep Dive: Brute-Force Attacks
  - Deep Dive: Response Timings
  - Deep Dive: Session Tokens and Sequencer
  - Deep Dive: Multi-Factor Authentication (MFA)
<br><br>
