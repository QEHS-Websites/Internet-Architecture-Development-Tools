# Internet Architecture Development Tools
Introductory Websites

Purpose: Introduction to Internet and Communication of Servers and Clients
- Introduction to Simple Networking Tools to Map Internet
- Introduction to GitHub Hosting and Development Tools

*Lessons will employ:*
- **GitHub Repositories**- Teaching, Feedback, Grading, and other tools usage (Social Media)
- **Chrome Browser**- consistent with EPSB SchoolZone and other EPSB Tools
- **GitHub Desktop**- Version Control Tool
- **Atom.io**- WYSIWYG (Teaching Choice)
- **Processing-Java**- Computer Apps, Android sideloading, Visual Data, Looks like other Languages

---

**UNDERCONSTRUCTION** Until 20220701

Sections (Copy to all New Repos)
- Introduction
- Questions
- Expectations
- Instructions, Vocabulary, and Explanations (including URLs and IDE Use)
- Code or Blocks of Code Emphasized (including parameters)
- Gamification or Rubric or Points
- Additional Information to Answer Questions
- Extensions

---

# Progressions
- Computer Environment
- Internet & Web Documents, <a href="">Click Here When Available</a>

### Ensure GitHub Account Created and *Hello World* Repository accessible

See: https://github.com/QEHS-Websites/Website-Hosting
- Naming Repository
- `index.html`
- Settings

See: https://github.com/MercersKitchen/Creating-a-GitHub-Repository

Create all Website Repositories, Case Studies will follow
- Learning HTML Website
- Promotions Website

### Download and install following applications (See Mr. Mercer for teaching versions)

#### GitHub Desktop
- Follow link when opening Repository

#### Atom.io(Teaching Choice)
- able to choice another WYSIWYG, but will be students responsibility
- Atom.io is a give installation, give it a while without using bandwidth
- Sometimes other programs interfere with it and simply needs to be reinstalled

### Google Classroom Question 1: See Next Activities
- Draw block diagram of main types of Internet Devices
- Overlay with GitHub Hosting, Version Control, and Tools
  - How do you believe GitHub Desktop Interactions updates repositories and Hosted Websites (i.e. server side, not locally hosted)
- Include Sockets as bit of information to transfer (and all previous bits on TCP/IP Model Stack)

Teacher Note: use Computer-forward-slash instructions to summarized what we found

### Google Classroom Question 2: Should be completed after downloads are completed and installed
What does your physical workstation look like?

Name the following
- Are you using multiple displays?
- Do you use the Vanilla CMD Window, PowerShell, or something else?
- Which WYSIWYG do you use (i.e. Atom.io is used as a teaching tool)?
- Which Browser to you use?
- Describe your 3 favorite settings?

---

# Introduction to the Internet & Web Documents (with small activities to illustrate)

### Small Activities to illustrate tools and skills

Introductions to a Browser - Specifically Google Chrome (and other exist)
1. "What else can a browser do?"
   - https://www.makeuseof.com/tag/use-browser-notepad/, accessed 20180905
   - A Browser can be a notepad tool, as long as the tab stays open
   - Type the following code into the URL Bar

   ```html
   data:text/html, <html contenteditable>
   ```

   - See: https://www.makeuseof.com/tag/use-browser-notepad/ for additional ideas on how to make a browser a Notepad

   - Uses built-in defaults for font, size, and other formatting rules
   - Google will spell check all the typing
   - If Chrome saves tabs (in settings, "Start where you left off"), or you use Workona, Tab will remain ready for notes but typing will disappear

2. Pathways inside a computer
   - Windows, Folders, and Pathways
   - The difference between `/` & `\`

Note about Pathways and URL's (Internet HTTP & HTTPS): all students will become familiar with ways of noting "Where does my file live?"
- **Reading Hint**: notice the difference between `/` & `\`
- Pathway Exemplar: `C:\Users\mmercer\Documents\GitHub\Hello-World\exemplarHelloWorld`
- URL Exemplar: https://github.com/Intro-CS-App-Dev-and-Deploy/Hello-World
- Instructions: File / Save

3. Pathways outside a computer: URLs in name or number
   - Learning how to read URLs
   - Local Scripting: see example of Browser Notepad
   - Local Hosting: see example of World War II Essay on the Holocaust
   - Client-server hosting: see below
   - The Difference between HTTP & HTTPS (note, good introduction to public ports here & part of a socket)

### Exploring & Illustrating Internet and Web Docs Architecture
- Main Skill Goal: Using CMD through Windows to sending "Packets" or Internet Messages
- Main Concept Goal: diagram image of Internet Architecture (Google Draw, Paper and Pencil, other methods)
- Include all vocabulary
- Main Vocabulary for Client-server relationships of Real (MAC) Addressing and Logical Addressing
  - workstations & NIC Cards (real MAC Address)
  - stub networks (defined by 1 workstation & switch or 1 workstation & router)
  - LANs defined by switch
  - WANs defined by router (edge router)
  - MANs defined by region or provider
  - Backbone of Internet defined by "in the wild" routers

- Main Vocabulary for Internet Services Requests ("all at once" (Netflix), packets (checked) like emails)
  - DNS
  - Pathways
  - Browser
  - EMail Server
  - Print Server

- Main Commands Examples for CMD
  - /? | ?
  - nslookup cisco.com
  - ping 72.163.4.185
    - Note: https://www.cloudns.net/blog/10-most-used-nslookup-commands/, accessed 20201110
  - traceroute | tracert [use IP Address], for example 72.163.4.185

- additional command: whoamI
- usually a login credential (no password)

#### Extra and Related Activities, if available
Brief Introduction to Web Documents Design: hypertext (HTTP & HTTPS)
- Ports for HTTP & HTTPS for IP Sockets
- Security Protocol of HTTPS

Introductions to Raspberry Pi, "Going Headless", and IP Sockets
- IP Sockets (IP Address : Port Number) needed to specify packet direction

TCP/IP & OSI Models: IP Socket is main goal
  - SSH & Putty
  - TightVNC, Real VNC
  - Note: review main ports, public & static, public and variable, variable

Note: https://www.cloudns.net/blog/10-most-used-nslookup-commands/

---

# Movement of Information through the Internet using Sockets

### Describe what your Computer Station Looks like
- See Google Classroom Question above

- Google Classroom Question: Describe the following
  - Physical Workstation, number of monitors: ???
  - Browser: ???
  - WISYWIG: ??? (Installed and Opened, YES or NO)
  - Processing installed to C-Drive / Parent Folder
  - Communication Tool (Schoolzone / GMail): ???
  - Cyber Security Tool(s): ??? (Have I been Pwnd, Badrap, Chrome Password Extension, KeePass, other)
  - GitHub Account and GitHub Desktop (substitutes for Git in CMD, much easier to use)

- Google Classroom Question: "What do you want to accomplish this semester?"

### Additional Notes
Brief Overview of "Where Files Live"
- How do I submit live websites and social media (GitHub)?
- Most recent: C-Drive (Documents / GitHub)
- Final Copies: Server of GitHub (requires updating regularly)

Google Classroom Questions
- Create current description of internet using Internet Tools and Tools for Hosting & Maintaining Website

---

# To Include

---
