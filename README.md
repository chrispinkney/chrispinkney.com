# https://chrispinkney.com

This repo contains the files that I use to for my personal website.


## Technologies utilized
**Caddy**
- I found Caddy while googling for the latest hip web servers an became interested in it given that it **only** supports https.
- Used Let's Encrypt to create a HTTPS Certificate.
- It's also open source and written in Go (a language I've had my eye on for a while.)
	> **Caddy**, sometimes clarified as the **Caddy web server**, is an open source, HTTP/2-enabled web server written in Go. It uses the Go standard library for its HTTP functionality.
	>One of Caddy's most notable features is enabling HTTPS by default.
	>[Source](https://en.wikipedia.org/wiki/Caddy_(web_server))


**DigitalOcean**
- During my first semester I found the [GitHub education pack](https://education.github.com/pack), a pack of various technologies generously offered by many companies. These technologies are either heavily subsidized, or free.
- They currently offer a fifty dollar credit to verified students, which I'm currently using to host a basic Ubuntu server along with the Caddy installation.
	> **DigitalOcean, Inc.** is an American cloud infrastructure provider headquartered in New York City with data centers worldwide. DigitalOcean provides developers cloud services that help to deploy and scale applications that run simultaneously on multiple computers.
	>[Source](https://en.wikipedia.org/wiki/DigitalOcean)

**Git/Github (Webhook/files)**
- After setting up my DigitalOcean Droplet, Ubuntu, and Caddy, I noticed that Caddy supports webhooks, which can be used in conjunction with my github account.
- Once setup, a new git push to this website's repo will trigger the hook and alert Caddy to automagically retrieve the files.
	> **GitHub** is a global company that provides hosting for software development version control using **Git**.
	> [Source](https://en.wikipedia.org/wiki/GitHub)

**Google Domains**
- I've had my personal domain for a several years now which was otherwise used entirely for the domain, and never for website hosting, until now.
- Alternatively, the github education pack also offers a free .me domains for one year from namecheap.
- I also use Google Domains for [email forwarding](mailto:hey@chrispinkney.com).
	> **Google Domains** is a internet domain name registration service offered by Google.
Google Domains offers domain registration (**including private domain registration**), DNS hosting, DNSSEC, Dynamic DNS, domain forwarding, and **email forwarding**. [Source](https://en.wikipedia.org/wiki/Google_Domains)
