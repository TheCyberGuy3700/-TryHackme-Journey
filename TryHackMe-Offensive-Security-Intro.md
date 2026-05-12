### 1} TryHackMe - Think Like A Hacker

**Date Completed:** Monday 11/05/2026  
**Difficulty:** Beginner  

**What I did:**  
Question: Which term describes simulating a hacker's actions to find vulnerabilities? Offensive security or Defensive Security?  
Answer: Offensive Security

**What I learned:**  
I learned the difference between offensive security and defensive security. Offensive security involves actively testing systems by simulating attacks to find weaknesses, while defensive security focuses on protecting and securing systems against those attacks before they happen.

### 2} TryHackMe - Starting The Lab

**What I did:**
Question: What is the bank account number shown in the FakeBank application?  
Answer: 8881

**What I learned:**
I learned how TryHackMe uses a virtual desktop to simulate a real system. I launched the FakeBank application through the "View Site" button and found the answer by interacting with the virtual lab environment.

### 3} TryHackMe - Find Hidden Pages.. Using The Terminal

**What I did:**
Question: Dirb found one URL, http://fakebank.thm/images. What is the other hidden URL?  
Answer: http://fakebank.thm/bank-transfer  
Command used: `dirb http://fakebank.thm`

**What I learned:**
I learned how to use the `dirb` tool in the terminal to find hidden directories and pages on a website. Dirb scanned the site and found two accessible URLs that weren’t linked on the main page. This is a common step in offensive security to discover exposed parts of a site.

## 4} TryHackMe - Attack The Admin Page

**What I did:**
Question: After accessing /bank-transfer, deposit $2000 or more to account 8881. What are the green words in the pop-up?  
Answer: BANK-HACKED

**What I learned:**
I learned that finding hidden pages can expose sensitive functionality. By accessing the hidden /bank-transfer page and depositing money to account 8881, I triggered a success message with the flag. This shows why hidden URLs alone aren’t real security - proper authentication and access controls are needed.


**Room Link:** [Click here](https://tryhackme.com/room/offensivesecurityintro)

