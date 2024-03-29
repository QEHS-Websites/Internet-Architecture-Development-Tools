# Internet Architecture Development Tools
Introductory Websites

*UNDER CONSTRUCTION*: see below

Purpose: Introduction to Internet and Communication of Servers and Clients
- Introduction to Simple Networking Tools and Mapping the Internet
- Introduction to GitHub Hosting and Development Tools

*Lessons will employ:*
- **GitHub Repositories**- Teaching, Feedback, Grading, and other tools usage (Social Media)
- **Chrome Browser**- consistent with EPSB SchoolZone and other EPSB Tools
- **GitHub Desktop**- Version Control Tool
- **Visual Studio Code**- WYSIWYG (Teaching Choice), see https://code.visualstudio.com/
- **Processing-Java**- Computer Apps, Android sideloading, Visual Data, Looks like other Languages

---

# Quick Link, what is the assignment details

<a href="https://github.com/QEHS-Websites/Internet-Architecture-Development-Tools#movement-of-information-through-the-internet-using-sockets">Click Here</a>

Vocabulary Words to Attend to 
- Port: specific to tool being used (for GitHub Server connection, always GitHub Desktop, uses protected passwords to authenticate)
- NIC Card, MAC Address, or SID
- IP Address of host domain (Edmonton Public Schools & note, switches and intranet routers can be ignored)
- IP Address of GitHub Server (or any server, even Cisco as demonstrated in the classroom)
- Place of GitHub Server (or any server, even Cisco as demonstrated in the classroom)

---

# Setting "Stuff" Up
- Computer Environment: how will you see all the displays needed for building a website (all controlled by sockets (IP Address & Port Number) )
- Internet & Web Documents, <a href="">Click Here When Available</a>

### Ensure GitHub Account Created and *Hello World* Repository accessible

See: https://github.com/QEHS-Websites/Website-Hosting
- Naming Repository
- `index.html`
- Settings

See: https://github.com/MercersKitchen/Creating-a-GitHub-Repository

Create all Website Repositories, Case Studies will follow
- Learning HTML Website
- Promotions Website (for Drawing App and Music App)

### Download and install following applications (See Mr. Mercer for teaching versions)
- Ensure Chrome is updated
- If using another browser, student is responsible for everything

#### GitHub Desktop
- Follow link when opening Repository

#### Microsoft Visual Code Studio (Teaching Choice)
- see https://code.visualstudio.com/
- able to choose another WYSIWYG, but will be students responsibility for using it (Mr. Mercer will not be teaching with it or supporting it's use)
- add Code Spell Checker (View / Extensions / Search and Install)

---

# Introduction to the Internet & Web Documents (with small activities to illustrate)
- Browser
- Internet Devices (switches, routers, etc ... the stuff we all just presume simply works )

### Introductions to a Browser - Specifically Google Chrome (and other exist)

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

2. Pathways inside a computer or to servers ("Where do Files Live?")
   - Windows, Folders, and Pathways
   - The difference between `/` & `\`
   - Pathway Exemplar: `C:\Users\mmercer\Documents\GitHub\Hello-World\exemplarHelloWorld`
   - URL Exemplar: https://github.com/Intro-CS-App-Dev-and-Deploy/Hello-World

3. Pathways outside a computer: URLs in name or number
   - Learning how to read URLs
   - Local Scripting: see example of Browser Notepad
   - Local Hosting: see example of World War II Essay on the Holocaust
   - Client-server hosting: see below
   - The Difference between HTTP & HTTPS (note, good introduction to public ports here & part of a socket)

### Exploring & Illustrating Internet and Web Docs Architecture
- Main Skill Goal: Using CMD through Windows to sending "Packets" or Internet Messages
- Main Concept Goal: diagram image of Internet Architecture (Google Draw, Paper and Pencil, other methods)
  - Symbols of a  Block Diagram: https://github.com/MercersKitchen/Computer-Science-Planning/tree/master/Projects#flow-chart-symbols
- Include all vocabulary
- Main Vocabulary for Client-server relationships of Real (MAC) Addressing and Logical Addressing
  - workstations & NIC Cards (real MAC Address)
  - Sockets: IP Address and Port Numbers
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

- additional command: `whoamI` or `whoamI -all`
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

#### Google Classroom Question 1
- Students submit this through Google Classroom Assignments

What does your physical workstation look like?
- Take an Image
- Draw a Picture

Your image or drawing should answer the following questions
- Are you using multiple displays?
- Do you use the Vanilla CMD Window, PowerShell, or something else?
- Which WYSIWYG do you use (i.e. Visual Code Studio is used as a teaching tool)?
- Which Browser to you use?
- Describe your 3 favorite settings (Operating System, Browser, Visual Code Studio, or GitHub)? If these are all new to you, simply illustrate 3 settings.
- Communication Tool (Schoolzone / GMail / other social media): ???
- Cyber Security Tool(s): ??? (Have I been Pwnd, Badrap, Chrome Password Extension, KeePass, other)

---

#### Google Classroom Question 2
- Draw <a href="https://github.com/MercersKitchen/Computer-Science-Planning/tree/master/Projects#flow-chart-symbols">block diagram</a> of main types of Internet Devices
- Overlay with GitHub Hosting, Version Control, and Tools
  - How do you believe GitHub Desktop Interactions updates repositories and Hosted Websites (i.e. server side, not locally hosted)
- Include Sockets as bit of information to transfer (and all previous bits on TCP/IP Model Stack)

Teacher Note: use Computer-forward-slash instructions to summarized what we found

---

# To Include

Better Lesson

Purpose: learning how to read Pathways and URLs & finding out where these are physically located
- Pathways are important for GitHub and it is also a server with a URL

When we build websites we host it on a computer
- Local: laptop, etc
- public: public domain
Information is contained in folders (type of organization)

A Browser is a powerful tool to illustrate text, images, etc.
- Turning a Browser into a Notepad file (not able to save)

Introducing a pathway using a Browser
- In the magic bar, "C:\" (backslash for going into the computer)
- Take a few minutes to explore you hard drive
- does your computer have any other physical or virtual drives (called drive letters)
- Copy an example pathway using File Explorer

Introducing the Internet
- Open a Browser and search for your favorite company (Cisco)
- copy the domain name, first part of URL after wwww
- note, 4.4.4.4 & 8.8.8.8 are domain name servers (are able to Google these)

Introducing Networking Tools and the CMD Window
- use nslookup to search for the IP address of the domain name (points to a physical machine, server, located somewhere in the world)
- use ping to establish communication
- use tracert to find the physical location

Find your favorite website's physical location

Introducing a package and how GitHub Desktop communicates with GitHub
- look up your MAC Address (ipconfig /all) (i.e. digital finger print for every computer, actually NIC Card)
- Socket: port & IP address (summarized the program you are using and the logical address of your computer)
- When you save info to GitHub Desktop, it is combined with your passwords and repository names (folders in the GitHub Server to organize different accounts, repositories, and accounts)

All information sent by computers has stacked information and it is used by various switches and routers so different computers (servers or clients) can talk with each other. 

The information is only a part of the entire file. Thus, different parts add to reform the entire file.

---

When explaining how information travels through the Internet, use a layered metaphor for adding the socket
- Add IP Address, keep origonating with port
- A router will know how to get to the intended IP (might have a choice of 3 routers, will choose the least busy)
