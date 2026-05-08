# Hi, I'm Luigi

Computer Science student at the University of Salerno, based in Nola (Naples), Italy.
I build websites, break things on purpose to understand how they work, and spend a fair amount of time on servers and home labs.

I run a small studio called **ImprontaWeb**, where I help professionals and small businesses get online with custom websites and e-commerce stores instead of cookie-cutter templates. On the side I'm building **WeRemind**, a SaaS that sends automatic WhatsApp reminders so businesses stop losing appointments and unpaid invoices.

---

## What I'm into

I started coding because I wanted to build the kind of tools I couldn't find. Now I split my time between three things:

- **Web development.** Mostly full-stack: front-end with HTML, CSS, JavaScript, TypeScript and React; back-end in PHP, Java, Python and Node. WordPress when the project calls for it, Next.js when it deserves something more.
- **Server & infrastructure.** I like making servers behave. I run my own home lab on **Proxmox** and **VMware ESXi** — VMs, LXC containers, virtual networks, self-hosted services. **Docker** and **Kubernetes** for container workloads, **Cloudflare** in front of public services, **AWS** and **Azure** when a project needs to live in the cloud. I treat virtualization like a hobby that pays off: cluster setups, snapshots, backups, and a bit of Cisco networking on the side. This is also where **IPMI Fan Pilot** was born — I wanted a clean web UI for my Dell server's fans and ended up shipping the tool I couldn't find.
- **Hardware repair.** Phones, tablets, laptops, the occasional weird DIY electronics project. If it has a board inside, I want to open it.

On top of that I'm a certified **EASA A1-A3 drone pilot**, with a good amount of hours in flight simulators before I touched a real one.

---

## Stuff I've built

### WeRemind — automatic WhatsApp reminders for businesses
A SaaS I'm building from scratch to help studios, clinics and small businesses stop missing appointments and chasing late payments. Customers configure templates and contacts from a dashboard, WeRemind handles the WhatsApp infrastructure. REST API for CRM integrations, 15-day free trial, three plans.

> 🔗 [weremind.it](https://weremind.it) · 📧 info@weremind.it

### IPMI Fan Pilot — web control panel for server fans
A self-hosted dashboard that talks to a server's BMC over IPMI and lets you control fan speeds, monitor sensors and tweak fan curves from a clean web interface — without ever touching `ipmitool` again. Backend in **FastAPI**, frontend in **React**, real-time data over **WebSocket**, settings persisted in **SQLite**. Currently supports Dell iDRAC raw commands; Supermicro and HPE are on the roadmap.

I posted it on **r/homelab** and it picked up real traction — the community started forking it, opening issues, suggesting features and asking for boards I don't even own. Easily the most rewarding "side project" feedback I've ever received.

> 🔗 [github.com/dev-luigi/IPMI-FanPilot](https://github.com/dev-luigi/IPMI-FanPilot)

### ImprontaWeb — my web studio
Custom websites, e-commerce and digital workflows for professionals and small businesses. Built around a "no templates, no shortcuts" philosophy.

> 🔗 [improntaweb.it](https://improntaweb.it)

### Personal portfolio
Where I keep my projects, my CV, my certifications and a bit of who I am. Built as a SPA, with a dark/light theme and a few side experiments.

> 🔗 [luigitanzillo.it](https://luigitanzillo.it)

### Home server lab
A small but growing rack on Proxmox: VMs for development, LXC containers for self-hosted services, a separate VLAN for tests, and an ESXi node where I break things on purpose.

More projects live in the repositories below — feel free to dig around.

---

## Tech Stack

Stuff I actually use, not stuff I clicked through once.

### Frontend
<p align="left">
  <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" height="50" /></a>
  <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" height="50" /></a>
  <a href="https://www.javascript.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" height="50" /></a>
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" height="50" /></a>
  <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" height="50" /></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://cdn.simpleicons.org/nextdotjs/white" alt="Next.js" height="50" /></a>
  <a href="https://vitejs.dev/" target="_blank"><img src="https://vitejs.dev/logo.svg" alt="Vite" height="50" /></a>
  <a href="https://tailwindcss.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" height="50" /></a>
  <a href="https://getbootstrap.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" height="50" /></a>
</p>

### Backend
<p align="left">
  <a href="https://www.java.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" height="50" /></a>
  <a href="https://www.php.net/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" height="50" /></a>
  <a href="https://www.python.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" height="50" /></a>
  <a href="https://nodejs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" height="50" /></a>
  <a href="https://expressjs.com/" target="_blank"><img src="https://cdn.simpleicons.org/express/white" alt="Express" height="50" /></a>
  <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" height="50" /></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" height="50" /></a>
  <a href="https://www.postgresql.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" height="50" /></a>
  <a href="https://www.mongodb.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" height="50" /></a>
  <a href="https://redis.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" height="50" /></a>
  <a href="https://supabase.com/" target="_blank"><img src="https://cdn.simpleicons.org/supabase" alt="Supabase" height="50" /></a>
</p>

### CMS & E-commerce
<p align="left">
  <a href="https://wordpress.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/wordpress/wordpress-original.svg" alt="WordPress" height="50" /></a>
  <a href="https://woocommerce.com/" target="_blank"><img src="https://cdn.simpleicons.org/woocommerce" alt="WooCommerce" height="50" /></a>
</p>

### Systems & Virtualization
<p align="left">
  <a href="https://www.proxmox.com/" target="_blank"><img src="https://cdn.simpleicons.org/proxmox" alt="Proxmox" height="50" /></a>
  <a href="https://www.vmware.com/" target="_blank"><img src="https://cdn.simpleicons.org/vmware/white" alt="VMware" height="50" /></a>
  <a href="https://www.linux.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" height="50" /></a>
  <a href="https://ubuntu.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ubuntu/ubuntu-plain.svg" alt="Ubuntu" height="50" /></a>
  <a href="https://www.cisco.com/" target="_blank"><img src="https://cdn.simpleicons.org/cisco" alt="Cisco" height="50" /></a>
</p>

### DevOps & Cloud
<p align="left">
  <a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" height="50" /></a>
  <a href="https://kubernetes.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes" height="50" /></a>
  <a href="https://github.com/features/actions" target="_blank"><img src="https://cdn.simpleicons.org/githubactions/2088FF" alt="GitHub Actions" height="50" /></a>
  <a href="https://aws.amazon.com/lambda/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS Lambda" height="50" /></a>
  <a href="https://azure.microsoft.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azure/azure-original.svg" alt="Azure" height="50" /></a>
  <a href="https://vercel.com/" target="_blank"><img src="https://cdn.simpleicons.org/vercel/white" alt="Vercel" height="50" /></a>
  <a href="https://www.cloudflare.com/" target="_blank"><img src="https://cdn.simpleicons.org/cloudflare/F38020" alt="Cloudflare" height="50" /></a>
</p>

### Tools
<p align="left">
  <a href="https://git-scm.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" height="50" /></a>
  <a href="https://github.com/" target="_blank"><img src="https://cdn.simpleicons.org/github/white" alt="GitHub" height="50" /></a>
  <a href="https://code.visualstudio.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VS Code" height="50" /></a>
  <a href="https://www.postman.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postman/postman-original.svg" alt="Postman" height="50" /></a>
</p>

---

## Outside the screen

I take photos, hike when the weather lets me, play piano badly but happily, and lose entire weekends to strategy games.

---

## Get in touch

- Portfolio: [luigitanzillo.it](https://luigitanzillo.it)
- WeRemind: [weremind.it](https://weremind.it) · info@weremind.it
- LinkedIn: [linkedin.com/in/luigi-tanzillo](https://www.linkedin.com/in/luigi-tanzillo-7602a633a/)
- Personal email: dazzler-yip3o@icloud.com
- Instagram: [@luigi._.tanzillo](https://instagram.com/luigi._.tanzillo)

If you want to talk about a project, a server problem, or just say hi — my inbox is open.
