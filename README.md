[aws]: https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white
[redhat]: https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white
[terraform]: https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white
[ansible]: https://img.shields.io/badge/Ansible-000000?style=for-the-badge&logo=ansible&logoColor=white
[cloudflare]: https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white
[digitalocean]: https://img.shields.io/badge/Digital_Ocean-0080FF?style=for-the-badge&logo=DigitalOcean&logoColor=white
[proxmox]: https://img.shields.io/badge/Proxmox-000000?style=for-the-badge&logo=Proxmox&logoColor=orange
[jenkins]: https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white
[github]: https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
[hugo]: https://img.shields.io/badge/Hugo-FF4088?style=for-the-badge&logo=hugo&logoColor=white
[markdown]: https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white
[nginx]: https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white
[playwright]: https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=Playwright&logoColor=white
[docker]: https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white
[prometheus]: https://img.shields.io/badge/Prometheus-000000?style=for-the-badge&logo=prometheus&labelColor=000000
[grafana]: https://img.shields.io/badge/Grafana-F2F4F9?style=for-the-badge&logo=grafana&logoColor=orange&labelColor=F2F4F9
[mongodb]: https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white
[svelte]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[sveltekit]: https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=Svelte&logoColor=white
[typescript]: https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
[tailwind]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[nodejs]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[daisy-ui]: https://img.shields.io/badge/Daisy%20UI-522bbe?style=for-the-badge&logo=daisyui&logoColor=white
[jest]: https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white
[kubernetes]: https://img.shields.io/badge/kubernetes-326ce5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white
[argocd]: https://img.shields.io/badge/Argo%20CD-1e0b3e?style=for-the-badge&logo=argo&logoColor=#d16044
[mongodb]: https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white
[nodejs]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[typescript]: https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
[expressjs]: https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white
[jwt]: https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white
[react]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[javascript]: https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E
[webpack]: https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white
[material-ui]: https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white

# Notes

Be sure to read in a Markdown viewer.

This doc contains some notes for you to understand the context of the technologies used. May be of help. Feel free to refer to my writeups on each project if you need additional information.

Categorised per project. Items prepended with an exclamation mark **(!)** and bolded are the highlights of the project. More exclamation marks means more important.

Currently, [pierreccesario.com](https://pierreccesario.com) has covers that are in the aspect ratio 3.84:1. The covers can be of any ratio, though.

# Marketing Guidelines and Variations

There's a lot of variations available. Any additional ones and their guidelines will be listed here with hyperlinks.

- [AWS Co-Marketing Logos](https://aws.amazon.com/co-marketing/)
- [RedHat Logo Brand Standards](https://www.redhat.com/en/about/brand/standards/logo?pfe-rr5a8q32m=logo-a)
- [RedHat Product Logo Brand Standards](https://www.redhat.com/en/about/brand/standards/product-logos)
- [Docker Logos](https://www.docker.com/company/newsroom/media-resources/)
- [Nodejs Guidelines and Hexcodes](https://nodejs.org/static/documents/foundation-visual-guidelines.pdf)
- [GitHub Permitted Logos](https://github.com/logos)
- [MongoDB Guidelines and Hexcodes](https://www.mongodb.com/brand-resources)
- [Prometheus Logos and Hexcodes](https://cncf-branding.netlify.app/projects/prometheus/)
- [Kubernetes Logos and Hexcodes](https://cncf-branding.netlify.app/projects/kubernetes/)
- [ArgoCD Logos and Hexcodes](https://cncf-branding.netlify.app/projects/argo/)
- [Terraform SVGs](https://www.svgrepo.com/svg/376353/terraform)
- [Hugo SVGs](https://www.svgrepo.com/svg/376327/hugo)
- [Nginx SVGs](https://www.svgrepo.com/vectors/nginx/)

# Shuttleday

Badminton scheduling and payment management site.

I don't care for frontend

## Tech Stack

| Infrastructure                                    | Continuous Integration | Container Orchestration | Backend                      | Frontend         |
| ------------------------------------------------- | ---------------------- | ----------------------- | ---------------------------- | ---------------- |
| ![][aws] <br> ![][digitalocean] <br> ![][Proxmox] | ![][jenkins]           | ![][kubernetes]         | ![][mongodb]                 | ![][react]       |
| ![][redhat]                                       | ![][docker]            | ![][argocd]             | ![][typescript]              | ![][javascript]  |
| ![][terraform] <br> ![][ansible]                  | ![][jest]              |                         | ![][nodejs]                  | ![][webpack]     |
| ![][nginx] <br> ![][cloudflare]                   |                        |                         | ![][expressjs] <br> ![][jwt] | ![][material-ui] |

| Item                                 | Description/Use                                                                                    |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- |
| **!!Docker**                         | Containerises application for easy management and deployment                                       |
| **!!Kubernetes (K8s)**               | Container orchestration.                                                                           |
| **!!Jenkins**                        | Continuous Integration service. Automates code tests and validation on commit to Git               |
| **!!ArgoCD**                         | Continuous Deployment service. Automates new version deployments on commit to Git                  |
| **!!Nginx**                          | Reverse proxy Jenkins, Ingress controller for Shuttleday API in K8s cluster                        |
| **!!AWS**                            | Cloud provider, hosts virtual machine to run Jenkins                                               |
| **!DigitalOcean**                    | Cloud provider, hosts Kubernetes cluster                                                           |
| **!Proxmox**                         | Type 1 Hypervisor for my Homelab VMs                                                               |
| **!Cloudflare**                      | DNS service provider.                                                                              |
| **!!Terraform**                      | By code, defines what Cloudflare, DigitalOcean and AWS resources to provision                      |
| **!!Ansible**                        | By code, defines what software to install and configurations to perform on the provisioned AWS VMs |
| **!Red Hat Enterprise Linux (RHEL)** | Linux distribution of choice on the AWS VM                                                         |
| **!TypeScript**                      | Backend language                                                                                   |
| **!Express.js**                      | Backend API framework                                                                              |
| **!Node.js**                         | Backend runtime                                                                                    |
| JWT                                  | Authentication method                                                                              |
| MongoDB                              | Database                                                                                           |
| React                                | Frontend framework                                                                                 |
| JavaScript                           | Frontend language                                                                                  |
| Webpack                              | Frontend bundler                                                                                   |
| Material UI                          | Frontend component library                                                                         |
| GitHub                               | Code repository                                                                                    |
| Jest                                 | Testing framework                                                                                  |

# PCPartsTool

Malaysian e-commerce PC parts price aggregator and configurator

Again, I don't care for frontend

## Tech Stack

| Infrastructure                   | DevOps                            | Backend         | Frontend      |
| -------------------------------- | --------------------------------- | --------------- | ------------- |
| ![][aws] <br> ![][redhat]        | ![][jenkins]                      | ![][mongodb]    | ![][svelte]   |
| ![][terraform] <br> ![][ansible] | ![][playwright]                   | ![][sveltekit]  | ![][tailwind] |
| ![][nginx]                       | ![][docker]                       | ![][typescript] | ![][daisy-ui] |
| ![][cloudflare]                  | ![][prometheus] <br> ![][grafana] |                 |               |

| Item                                 | Description/Use                                                                                              |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| **!!Docker**                         | Containerises application for easy management and deployment                                                 |
| **!!Prometheus**                     | Gathers metrics on site performance, resource usage, etc                                                     |
| **!!Grafana**                        | Displays Prometheus metrics data as nice visualisations                                                      |
| **!!Jenkins**                        | Continuous Integration/Contiuous Deployment service. Automates new version deployments once I commit to Git. |
| **!!Nginx**                          | Reverse proxy.                                                                                               |
| **!!AWS**                            | Cloud provider, hosts virtual machine to run Jenkins and PCPartsTool site                                    |
| **!Cloudflare**                      | DNS service provider.                                                                                        |
| **!!Terraform**                      | By code, defines what Cloudflare and AWS resources to provision                                              |
| **!!Ansible**                        | By code, defines what software to install and configurations to perform on the provisioned AWS VMs           |
| **!Red Hat Enterprise Linux (RHEL)** | Linux distribution of choice on the AWS VM                                                                   |
| **!Node.js**                         | Backend runtime                                                                                              |
| **!TypeScript**                      | Backend language                                                                                             |
| MongoDB                              | Database                                                                                                     |
| SvelteKit/Svelte                     | Backend and Frontend simultaneously. Either logo works                                                       |
| Tailwind                             | Frontend styling framework                                                                                   |
| DaisyUI                              | Frontend component library                                                                                   |
| GitHub                               | Code repository                                                                                              |
| Playwright                           | End-to-end testing framework for the site                                                                    |

# pierreccesario.com

Portfolio website

GitHub is only here because the CI/CD column would be so empty without it. You'll notice that I don't even mention it on the serious projects

## Tech Stack

| Infrastructure                   | CI/CD        | Site          |
| -------------------------------- | ------------ | ------------- |
| ![][aws] <br> ![][redhat]        | ![][jenkins] | ![][hugo]     |
| ![][terraform] <br> ![][ansible] | ![][github]  | ![][markdown] |
| ![][cloudflare]                  |              |               |

| Item                                  | Description/Use                                                                                             |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **!!Jenkins**                         | Continuous Integration/Contiuous Deployment service. Automates updates to the website once I commit to Git. |
| **!!AWS**                             | Cloud provider, hosts virtual machine to run Jenkins and static website file storage                        |
| **!!Red Hat Enterprise Linux (RHEL)** | Linux distribution of choice on the AWS VM                                                                  |
| **!Cloudflare**                       | DNS service provider.                                                                                       |
| **!!Terraform**                       | By code, defines what Cloudflare and AWS resources to provision                                             |
| **!!Ansible**                         | By code, defines what software to install and configurations to perform on the provisioned AWS VMs          |
| Markdown                              | Language used to write the pages.                                                                           |
| Hugo                                  | Static site generator. Turns markdown files like this into nice looking pages                               |
| GitHub                                | Code repository                                                                                             |

# imyour_joy

Discord bot

## Tech Stack

No nice graphic here because it was one of my first projects

| Item            | Description/Use                                                               |
| --------------- | ----------------------------------------------------------------------------- |
| **!!Docker**    | Containerises application for easy management and deployment                  |
| **!!Jenkins**   | Continuous Integration service. Automates code tests and deployment on commit |
| **!TypeScript** | Backend language                                                              |
| **!Node.js**    | Backend runtime                                                               |
| Discord         | Integrates with Discord                                                       |
| GitHub          | Code repository                                                               |
