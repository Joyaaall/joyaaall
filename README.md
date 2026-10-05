<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=260&color=0:1a1b27,50:7aa2f7,100:bb9af7&text=JOYAL.exe&fontColor=c0caf5&fontSize=72&animation=blinking&stroke=bb9af7&strokeWidth=1&desc=BUILD.%20AUTOMATE.%20SELF-HOST.&descSize=17&descAlignY=72" alt="Joyal.exe — Build. Automate. Self-host." />
</p>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=1200&color=9ECE6A&background=1A1B2700&center=true&vCenter=true&width=720&height=60&lines=%24+whoami+%E2%86%92+Joyal;%24+focus+%E2%86%92+AI+%2B+Automation;%24+deploy+%E2%86%92+Docker+%2B+Raspberry+Pi;%24+status+%E2%86%92+learning+by+building" alt="Animated terminal: Joyal, AI and automation, Docker and Raspberry Pi, learning by building" width="720" />

**Turning “I wish this existed” into a working project.**

<br/>

<a href="https://github.com/Joyaaall?tab=repositories">
  <img src="https://img.shields.io/badge/PROJECTS-bb9af7?style=for-the-badge&logo=github&logoColor=1a1b27" alt="Projects" />
</a>
&nbsp;
<a href="https://github.com/Joyaaall/homelab">
  <img src="https://img.shields.io/badge/HOMELAB-7aa2f7?style=for-the-badge&logo=raspberrypi&logoColor=1a1b27" alt="Homelab" />
</a>
&nbsp;
<a href="mailto:joyalaliyas123@gmail.com">
  <img src="https://img.shields.io/badge/CONTACT-9ece6a?style=for-the-badge&logo=gmail&logoColor=1a1b27" alt="Contact" />
</a>

</div>

<br/>

## `~/about`

```console
visitor@github:~$ cat joyal.conf

name        = Joyal
education   = Computer Science Engineering
college     = Adi Shankara Institute of Engineering and Technology
interests   = AI agents, automation, software, self-hosting
approach    = Build it. Run it. Understand it. Improve it.
looking_for = AI/software internships and meaningful collaborations
```

I build Python applications, connect services with n8n, and experiment with AI agents.

When I'm not working on application code, I'm usually exploring how to run it on my own infrastructure. My Raspberry Pi homelab is where software meets containers, storage, networking, and the occasional debugging session.

<br/>

## `~/projects`

<table>
<tr>
<td width="50%" valign="top">

### 📊 Attendance Manager

**Less attendance guesswork.**

An Etlab dashboard with attendance calculations, timetable management, semester discovery, and leave planning.

Adapted from the RIT Etlab API, with upstream attribution included.

<br/>

<img src="https://img.shields.io/badge/Python-1a1b27?style=flat-square&logo=python&logoColor=7aa2f7" alt="Python" />
<img src="https://img.shields.io/badge/Flask-1a1b27?style=flat-square&logo=flask&logoColor=c0caf5" alt="Flask" />
<img src="https://img.shields.io/badge/Docker-1a1b27?style=flat-square&logo=docker&logoColor=7aa2f7" alt="Docker" />

<br/><br/>

**[→ Open project](https://github.com/Joyaaall/automated-attendance-manager-for-Etlab)**

</td>
<td width="50%" valign="top">

### 🖥️ Raspberry Pi Homelab

**Beyond “it works on my machine.”**

A self-hosted environment for applications, automation, media, and learning how services fit together.

Documenting the structure, not just collecting containers.

<br/>

<img src="https://img.shields.io/badge/Linux-1a1b27?style=flat-square&logo=linux&logoColor=e0af68" alt="Linux" />
<img src="https://img.shields.io/badge/Docker-1a1b27?style=flat-square&logo=docker&logoColor=7aa2f7" alt="Docker" />
<img src="https://img.shields.io/badge/Raspberry_Pi-1a1b27?style=flat-square&logo=raspberrypi&logoColor=bb9af7" alt="Raspberry Pi" />

<br/><br/>

**[→ Explore the infrastructure](https://github.com/Joyaaall/homelab)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌡️ AC Health Monitoring

**Understand the machine from the outside.**

Developing a non-invasive monitoring concept for airflow, filter blockage, cooling performance, and energy use—without modifying the AC's internal wiring.

`Sensors` · `Monitoring` · `Prototyping`

**↳ Research and development**

</td>
<td width="50%" valign="top">

### ⚡ Automation Experiments

**Give the repetitive work to a workflow.**

Exploring practical ways to connect Python, APIs, n8n, and AI agents.

Useful inputs. Clear outputs. Fewer manual steps.

`Python` · `n8n` · `APIs` · `AI agents`

**↳ Learning through building**

</td>
</tr>
</table>

<br/>

## `~/toolbox`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,flask,js,html,css,docker,linux,raspberrypi,git,github&theme=dark&perline=10" alt="Python, Flask, JavaScript, HTML, CSS, Docker, Linux, Raspberry Pi, Git, and GitHub" />

<br/><br/>

<img src="https://img.shields.io/badge/AUTOMATION-n8n-bb9af7?style=flat-square&labelColor=1a1b27" alt="Automation: n8n" />
&nbsp;
<img src="https://img.shields.io/badge/EXPLORING-AI_AGENTS-7aa2f7?style=flat-square&labelColor=1a1b27" alt="Exploring AI agents" />
&nbsp;
<img src="https://img.shields.io/badge/DEPLOYMENT-SELF_HOSTED-9ece6a?style=flat-square&labelColor=1a1b27" alt="Self-hosted deployment" />

</div>

<br/>

## `~/homelab`

```text
                         ┌───────────────────────┐
                         │   MY DEVICES          │
                         └───────────┬───────────┘
                                     │
                              Private network
                                     │
                         ┌───────────▼───────────┐
                         │   RASPBERRY PI 5      │
                         │   Ubuntu · Docker     │
                         └───────────┬───────────┘
                                     │
                  ┌──────────────────┼──────────────────┐
                  │                  │                  │
          ┌───────▼───────┐  ┌───────▼───────┐  ┌───────▼───────┐
          │  AUTOMATION   │  │  APPLICATIONS │  │  DATA         │
          │  n8n          │  │  Self-hosted  │  │  Databases    │
          │  Workflows    │  │  services     │  │  Storage      │
          └───────────────┘  └───────────────┘  └───────────────┘
```

**Currently learning:** container networking, persistent storage, monitoring, and recovery.

<br/>

## `~/current-focus`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=2300&pause=1000&color=BB9AF7&background=1A1B2700&vCenter=true&width=760&height=50&lines=%3E+Building+useful+tools+with+Python;%3E+Connecting+APIs+and+automating+workflows;%3E+Exploring+practical+AI+agents;%3E+Learning+what+happens+after+deployment" alt="Building Python tools, automating workflows, exploring AI agents, and learning deployment" width="760" />

- Improve the projects I already use.
- Build automations around real problems.
- Understand systems, not just individual tools.
- Turn experiments into something someone else can run.

<br/>

<details>
<summary><strong>▸ Open a little more context</strong></summary>

<br/>

### What I enjoy working on

Projects where software interacts with something real: a student portal, a workflow, a server, or a sensor.

### How I learn

Build a small version, test it, find out what breaks, and improve it.

### What I'm looking for

AI/software internship opportunities and collaborations where I can contribute, learn, and ship useful work.

</details>

<br/>

## `~/connect`

```console
visitor@github:~$ ./start-conversation.sh

> Have an idea, a project, or an internship opportunity?
> Let's talk.
```

<div align="center">

<a href="mailto:joyalaliyas123@gmail.com">
  <img src="https://img.shields.io/badge/SEND_A_MESSAGE-bb9af7?style=for-the-badge&logo=gmail&logoColor=1a1b27" alt="Send a message" />
</a>

<br/><br/>

<sub>Not everything needs AI. Some things just need a good script.</sub>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:7aa2f7,100:bb9af7&height=120&section=footer" alt="" />
