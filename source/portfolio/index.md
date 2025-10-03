---
title: portfolio
date: 2025-09-23 00:33:23
toc: true
---
# Welcome!
My name is Yong Khang, and I have been dabbled as a Game designer for over 8 years! I enjoy crafting polished games with fun mechanics and engaging monetization strategies. Throughout the years I had the oppoturnity to lead or co-design several amazing titles with Unity on mobile platform, most notably, Ejen Ali: Emergency, Ejen Ali: Agents’ Arena, Komuniti Kita, and also, Titan Heroes on Roblox platform.

I am adept at writing Game Design Documents and balance the game progression and economy on spreadsheets, while working closely with programmers, artists, and producer to ensure a smooth production that meet our requirement targets.

During my free time I often immerse myself in technological stuff, be it server hosting, security practices, or 

During my free time I often immerse myself in technological stuff, from password manager to Nginx to Jamstack hosting and optimization. Sometimes I just watch some anime or play my bass guitar.

## Skills
{% tabs Skills %}

<!-- tab Game Design @fas fa-gamepad -->
### Game Design Documents
Experienced in generating fun and engaging ideas and documenting the details in the GDD. Periodically updates the GDD to meet the changes throughout the development cycle, as well as preserving links to supporting documents.

### Progression Planning and Balancing
Plan out and balance the player's progression based on agreed content amount, and design a good progression curve that works in conjunction with retention and rewards systems.

### Combat and Map Design
Design each character skills that matches with their intended lore and personality to increase immersion, and blockout the map layout that helps each characters stand out in their own way.
<!-- endtab -->

<!-- tab Game Engines @fas fa-gears -->
### Unity
Understand the basic workflow of Unity engine and capable of scripting the editor to make design workflow easier. Also familar with managing Prefabs and Scriptable Objects for a more streamlined content management.

### Roblox Studio
Familiar with Roblox Studio and capable of blockout a detailed game level to properly convey the design idea to artists and programmers.
<!-- endtab -->

<!-- tab Programming @fas fa-code -->
### Something
Something
<!-- endtab -->

<!-- tab Productivity Software @fas fa-file-excel -->
### Something
Something
<!-- endtab -->


{% endtabs %}


---



## Experiences

{% timeline Electronic Arts, red %}
<!-- timeline Nov 2024 to April 2025 -->

{% inlineImg /portfolio/Electronic_Arts_2020.png 50px %}

### Game Content Designer


- Balance the cost and odds of a card packs rewards such as player cards and event tokens to ensure the packs to be attractive and relevant to the players
- Balance the economy of event tokens from various free / freemium / premium card packs while aligning with the engagement, acquisition, and monetization target of the current event
- Collaborate on card packs content design to provide an interesting economy loop relevant to the main event
- Update balancing values in Perforce and maintain documentation to reflect finalized changes
- Perform automated draw test to verify actual oddsmatch intended odds

<!-- endtimeline -->
{% endtimeline %}




{% timeline The Gang Asia (formerly Common Extract), green %}
<!-- timeline May 2024 to July 2024 -->

{% inlineImg /portfolio/tgs.webp 50px %}

### Senior Game Designer

- Oversees the design department and assisting the production manager in carrying out performance reviews.
- Lead in the designing of Titan Heroes and successfully launched it on Roblox platform while making improvement according to the telemetry and feedback received.
- Organized a Spreadsheet tutorial to level up the department’s Spreadsheet skill.

<!-- endtimeline -->

<!-- timeline May 2018 to April 2024 -->
### Game Designer

- Prepare Game Design Documents according to the interest of clients / stakeholders while work closely with programmers, artists, and project manager to keep the scope and timeline on the track.
- Simulate player’s progression using a Spreadsheet software and carry out balancing while keeping an eye toward the content play time.
- Blockout the game level while making sure key locations would have a nice view with visual leading line toward the next point of interest.
- Worked with Unity engine and later Roblox Studio to deliver various games from competitive, casual, hyper-casual to NFT games.
<!-- endtimeline -->
{% endtimeline %}




{% timeline Dutajaya Media, pink %}
<!-- timeline Aug 2017 to Dec 2017 -->

{% inlineImg /portfolio/djm.webp 50px %}

### Game Designer

- Design VR Games under the guidance of a Senior to make sure nail down the control, immersion, as well as preventing motion sickness.
- Design 4 VR Horror titles that are scalable for 1~4 players while making sure every players gets to enjoy regardless where they are currently standing / looking at.
- Playtest and provide feedback on PvE and PvP 200m² free-roaming titles.



<!-- endtimeline -->
{% endtimeline %}



{% timeline Common Extract, green %}
<!-- timeline May 2024 to July 2024 -->

{% inlineImg /portfolio/ce.png 50px %}

### Game Designer

- Work closely with programmer to come up with ideas and mechanics for Ejen Ali: Emergency.
- Design about 50 levels for the launch of Ejen Ali: Emergency
- Perform a bit of coding to alter / improve the mechanics to what I needed
- Craft several GDDs as well as update old iOS title Wrath of Cheese

<!-- endtimeline -->

<!-- timeline May 2018 to April 2024 -->
### Game Designer Internship

- Same as above
<!-- endtimeline -->
{% endtimeline %}


## Education

{% timeline Multimedia University, blue %}

<!-- timeline 2012 to 2016 -->

### Bachelor in Computer Science with Specialization in Games Development

- Campus: Cyberjaya
- CGPA: 3.2 / 4
- Link to verify [here](https://osc.mmu.edu.my/psc/csprd/EMPLOYEE/SA/s/WEBLIB_N_ROG.WEBSERVICE.FieldFormula.IScript_info?convocation=2016&id=31313132373030353337&encoded=Y)
  - ID: 1112700537
  - Scroll Number: 2016/03706

<!-- endtimeline -->
{% endtimeline %}


---


## Notable Career Projects
{% tabs Projects %}


<!-- tab Ejen Ali: Agent's Arena @fab fa-android -->
### Self-Hosting and Infrastructure Migration
asd
<!-- endtab -->

<!-- tab Ejen Ali: Emergency @fab fa-android -->
### Static Site Hosting and Optimization
asd
<!-- endtab -->

<!-- tab asdasd @fas fa-child-reaching -->
### Networking and DNS Configuration
Something
<!-- endtab -->


{% endtabs %}


---


## Pet Projects
{% tabs Projects %}


<!-- tab Self-Hosting and Infrastructure Migration @fas fa-diagram-project -->
### Self-Hosting and Infrastructure Migration
My experience on this started with setting up Docker containers within a virtual machine using Hyper-V, and using Nginx as a reverse proxy to expose my applications to the internet. I configured my router's DHCP to assign a static IP and set up port forwarding to the VM, while using Duck DNS maintain a consistent domain name.

Initially I used Let's Encrypt to generate SSL certificates, but some messaging platforms flagged it as suspicious, so I switched to using Cloudflare SSL on my own domain.

I originally used a cron job to update Cloudflare DNS records, but after my ISP stopped providing a public IP and placed me behind CGNAT, so I switched to Cloudflare Tunnel as a workaround. I also configured Cloudflare Access to restrict entry using access rules and TOTP-based authentication.

I eventually found it cumbersome to keep my PC online to maintain access, so I migrated them to Google Compute Engine.
<!-- endtab -->

<!-- tab Static Site Hosting and Optimization @fas fa-diagram-project -->
### Static Site Hosting and Optimization
The idea of building a Jamstack site came from wanting a personal portfolio that wasn't hosted on third-party platforms with questionable privacy practices. I picked Hugo as the static site generator for its vast amount of themes and near-instant build time.

Working with Hugo was a valuable learning experience. I picked up YAML and deepened my understanding of Markdown through writing post and configuring the themes. Initially, I manually generate the site and uploaded the files to Cloudflare Pages, without involving GitHub into the pipeline.

After iterating through several themes on my other blogs, I decided to streamline the workflow by storing project files on GitHub and letting Cloudflare Pages to automatically pull and build the site.

For content management, I started with Decap CMS (previously Netlify CMS) since it can be hosted directly within the Jamstack repo. However, due to its slow development pace, I switched to Sveltia CMS, a modern rewrite that is 99% compatible with Decap CMS while offering significant improvements.

Using the CMS requires a GitHub OAuth application and an OAuth client running on Cloudflare Worker for authentication, so I did that. To secure the `/admin/` path, once again I used Cloudflare Access.

Most recently, I migrated from Hugo to Hexo, as I found Hugo's themes are often too minimalistic. On the other hand, Hexo's themes offered better flexibility in customization, while still being blazing fast.
<!-- endtab -->

<!-- tab asdasd @fas fa-diagram-project -->
### Networking and DNS Configuration
Something
<!-- endtab -->


{% endtabs %}