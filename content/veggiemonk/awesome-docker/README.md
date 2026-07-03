# Track Awesome Docker Updates Daily

:whale: A curated list of Docker resources and projects

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/veggiemonk/awesome-docker/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 veggiemonk/awesome-docker](https://github.com/veggiemonk/awesome-docker) · ⭐ 36K · 🏷️ Back-End Development

[ Daily / [Weekly](/content/veggiemonk/awesome-docker/week/README.md) / [Overview](/content/veggiemonk/awesome-docker/readme/README.md) ]

## [Jul 03, 2026](/content/2026/07/03/README.md)

### Developer Workflow / CI/CD

*   [Self Hosted Runner (⭐114)](https://github.com/youssefbrr/self-hosted-runner) - Dockerized solution for setting up a self-hosted GitHub Actions runner with support for Linux, macOS, and Windows.

## [Jun 22, 2026](/content/2026/06/22/README.md)

### Storage & Data / Reverse Proxy

*   [resq (⭐0)](https://github.com/mashb1t/resq) - Restic-powered Docker backups for volumes, databases, and .env files, with or without stopping containers. Works with local, SSH, or any S3 compatible storage.

## [Jun 15, 2026](/content/2026/06/15/README.md)

### User Interfaces / Terminal

*   [DockTUI (⭐29)](https://github.com/strmax195-hue/docktui) - Fast, zero-dependency terminal dashboard for Docker and Compose.

## [Jun 14, 2026](/content/2026/06/14/README.md)

### Running Containers / Deployment & Platforms

*   [doco-cd (⭐1.6k)](https://github.com/kimdre/doco-cd) - Lightweight GitOps and Continuous Deployment tool to deploy Docker Compose projects and Swarm stacks using polling and webhooks.

## [May 19, 2026](/content/2026/05/19/README.md)

### Observability / Reverse Proxy

*   [docker-exporter (⭐1)](https://github.com/dlepaux/docker-exporter) - Lightweight Prometheus exporter for Docker container metrics written in Rust. Correct cgroup v2 memory working set on ARM64 (Raspberry Pi 5), runs non-root with a read-only socket, \~7 MiB idle RAM.
*   [Middleware](https://middleware.io/) - :yen: Monitor Docker hosts, containers, logs, and application performance from a unified observability platform.

### Security / Reverse Proxy

*   [container-explorer (⭐99)](https://github.com/google/container-explorer) - Forensic utility to explore Docker and containerd container details from mounted disk images.

## [May 18, 2026](/content/2026/05/18/README.md)

### Official Projects

*   [Moby (⭐72k)](https://github.com/moby/moby)
*   [Docker Hub](https://hub.docker.com)
*   [Docker Compose (⭐38k)](https://github.com/docker/compose/) - Define and run multi-container applications with Docker.
*   [Docker Registry (⭐10k)](https://github.com/docker/distribution) - The Docker toolset to pack, ship, store, and deliver content

### Engine & Runtime

*   [colima (⭐29k)](https://github.com/abiosoft/colima) - Container runtimes on macOS (and Linux) with minimal setup.
*   [containerd (⭐21k)](https://github.com/containerd/containerd) - An open and reliable container runtime.
*   [gVisor (⭐19k)](https://github.com/google/gvisor) - Application Kernel for Containers.
*   [runc (⭐13k)](https://github.com/opencontainers/runc) - CLI tool for spawning and running containers according to the OCI specification.
*   [youki (⭐7.5k)](https://github.com/youki-dev/youki) - Container runtime written in Rust, implementing the OCI runtime specification.

### Building Images / Builder

*   [apko (⭐1.6k)](https://github.com/chainguard-dev/apko) - Declarative OCI image builder from apk packages; reproducible by design.
*   [buildx (⭐4.4k)](https://github.com/docker/buildx) - Official Docker CLI plugin for multi-platform builds backed by BuildKit.
*   [earthly (⭐12k)](https://github.com/earthly/earthly) - Containerized build automation with Dockerfile-meets-Makefile syntax.
*   [ko (⭐8.5k)](https://github.com/ko-build/ko) - Build and deploy Go applications as container images without a Dockerfile.
*   [nix2container (⭐868)](https://github.com/nlewo/nix2container) - Build OCI images with Nix without `docker load` round-trips.
*   [Production-Ready Python Containers](https://pythonspeed.com/products/pythoncontainer/) - :yen: A template for creating production-ready Docker images for Python applications.

### Building Images / Base Images

*   [Chainguard Images (⭐680)](https://github.com/chainguard-images/images) - Minimal, signed, SBOM-attested container images built on Wolfi.
*   [melange (⭐609)](https://github.com/chainguard-dev/melange) - Build apk packages from declarative YAML for use with apko.
*   [Wolfi (⭐1.2k)](https://github.com/wolfi-dev/os) - Undistro Linux designed for containers; glibc-based, signed, daily SBOMs.

### Building Images / Dockerfile

*   [Trsuted Builds](https://dockerfile.github.io/) - Trusted Automated Docker Builds. Dockerfile Project maintains a central repository of Dockerfile for various popular open source software services runnable on a Docker container.

### Image Lifecycle / Registry

*   [Amazon Elastic Container Registry](https://aws.amazon.com/ecr/) - :yen: Amazon Elastic Container Registry (ECR) is a fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images.
*   [Azure Container Registry](https://azure.microsoft.com/en-us/products/container-registry/#overview) - :yen: Manage a Docker private registry as a first-class Azure resource.
*   [Cloudsmith](https://cloudsmith.com/product/formats/docker-registry) - :yen: A fully managed package management SaaS, with first-class support for public and private Docker registries (and many others, incl. Helm charts for the Kubernetes ecosystem). Has a generous free-tier and is also completely free for open-source.
*   [Container Registry Service](https://container-registry.com/) - :yen: Harbor based Container Management Solution as a Service for teams and organizations. Free tier offers 1 GB storage for private repositories.
*   [Cycle.io](https://cycle.io/) - :yen: Bare-metal container hosting.
*   [DigitalOcean](https://www.digitalocean.com/products/container-registry) - :yen: DigitalOcean Container Registry.
*   [GCP Artifact Registry](https://docs.cloud.google.com/artifact-registry/docs) - :yen: Fast, private Docker image storage on Google Cloud Platform.
*   [JFrog Artifactory](https://jfrog.com/artifactory/) - :yen: Artifact Repository Manager, can be used as private Docker Registry as well.
*   [kontain.me (⭐243)](https://github.com/imjasonh/kontain.me) - On-demand container image registry that builds and serves images when they are pulled.
*   [Quay.io](https://quay.io/) - :yen: Secure hosting for private Docker repositories.

### Image Lifecycle / Registry CLI

*   [crane (⭐4k)](https://github.com/google/go-containerregistry/tree/main/cmd/crane) - Lightweight CLI to manipulate registry images, from `go-containerregistry`.
*   [go-containerregistry (⭐4k)](https://github.com/google/go-containerregistry) - Go library and CLI tools (`crane`, `gcrane`, `registry`) for working with container registries.
*   [oras (⭐2.3k)](https://github.com/oras-project/oras) - Push and pull arbitrary OCI artifacts to and from any OCI registry.
*   [regctl (⭐1.9k)](https://github.com/regclient/regclient) - Daemonless registry client; copy, inspect, modify, and sign OCI images.

### Image Lifecycle / Image Scanning & SBOM

*   [Docker Scout (⭐451)](https://github.com/docker/scout-cli) - Official Docker CLI for SBOM generation, vulnerability analysis, and policy evaluation.

### Image Lifecycle / Supply Chain

*   [cosign (⭐6.1k)](https://github.com/sigstore/cosign) - Container signing, verification, and transparency log for OCI artifacts.
*   [in-toto (⭐1k)](https://github.com/in-toto/in-toto) - Framework for supply chain attestations; underpins SLSA and cosign provenance.
*   [policy-controller (⭐175)](https://github.com/sigstore/policy-controller) - Kubernetes admission controller enforcing cosign signatures on container images.
*   [witness (⭐534)](https://github.com/in-toto/witness) - Generate and verify in-toto attestations across the build pipeline.

### Running Containers / Deployment & Platforms

*   [Cloud Run Compose](https://docs.cloud.google.com/run/docs/deploy-run-compose) - :yen: Deploy `docker-compose.yaml` files directly to Google Cloud Run as a managed service.

### Security / Reverse Proxy

*   [docker-socket-proxy (⭐2.6k)](https://github.com/Tecnativa/docker-socket-proxy) - HAProxy-based fine-grained filter for the Docker API socket; widely used to expose a restricted socket to reverse proxies and homelab stacks.

### Developer Workflow / CI/CD

*   [Buddy](https://buddy.works) - :yen: The best of Git, build & deployment tools combined into one powerful tool that supercharged our development.
*   [CodeFresh](https://octopus.com/codefresh) - :yen: End-to-end build, test, and share for Docker applications, with automated testing.
*   [Depot](https://depot.dev) - :yen: Build Docker images fast, in the cloud. Blazing fast compute, automatic intelligent caching, and zero configuration.
*   [Screwdriver](https://screwdriver.cd/) - :yen: Yahoo's OpenSource buildplatform designed for Continous Delivery.

### In-Container Tooling / Wrappers

*   [cdebug (⭐1.7k)](https://github.com/iximiuz/cdebug) - Swiss-army knife for debugging running containers via ephemeral sidecars; works with Docker, containerd, and Kubernetes.

### Where to Start / Wrappers

*   [Benefits of using Docker](https://semaphore.io/blog/docker-benefits) for development and delivery, with a practical roadmap for adoption.
*   [Bootstrapping Microservices](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform) - A practical and project-based guide to building applications with microservices, starts by building a Docker image for a single microservice and publishing it to a private container registry, finishes by deploying a complete microservices application to a production Kubernetes cluster.
*   [Docker Curriculum (⭐6.1k)](https://github.com/prakhar1989/docker-curriculum): A comprehensive tutorial for getting started with Docker. Teaches how to use Docker and deploy dockerized apps on AWS with Elastic Beanstalk and Elastic Container Service.
*   [Docker Documentation](https://docs.docker.com/): the official documentation.
*   [Docker for beginners (⭐85)](https://github.com/groda/big_data/blob/master/docker_for_beginners.md): A tutorial for beginners who need to learn the basics of Docker—from "Hello world!" to basic interactions with containers, with simple explanations of the underlying concepts.
*   [Docker for novices](https://www.youtube.com/watch?v=xsjSadjKXns) An introduction to Docker for developers and testers who have never used it. (Video 1h40, recorded linux.conf.au 2019 — Christchurch, New Zealand)
*   [Docker katas (⭐288)](https://github.com/eficode-academy/docker-katas) A series of labs that will take you from "Hello Docker" to deploying a containerized web application to a server.
*   [Docker simplified in 55 seconds](https://www.youtube.com/watch?v=vP_4DlOH1G4): An animated high-level introduction to Docker. Think of it as a visual tl;dr that makes it easier to dive into more complex learning materials.
*   [Docker Training](https://training.mirantis.com) - :yen:
*   [Dockerlings](https://github.com/furkan/dockerlings): Learn docker from inside your terminal, with a modern TUI and bite sized exercises.
*   [Introduction à Docker](https://blog.stephane-robert.info/docs/conteneurs/moteurs-conteneurs/docker/) A dedicated section to master Docker on a French site about DevSecOps: From the basics to best practices, including optimizing, securing your containers...
*   [Learn Docker (⭐243)](https://github.com/dwyl/learn-docker): step-by-step tutorial and more resources (video, articles, cheat sheets)
*   [Learn Docker (Visually)](https://pagertree.com/learn/docker/overview) - A beginner-focused high-level overview of all the major components of Docker and how they fit together. Lots of high-quality images, examples, and resources.
*   [Play With Docker](https://training.play-with-docker.com/): PWD is a great way to get started with Docker from beginner to advanced users. Docker runs directly in your browser.
*   [Practical Guide about Docker Commands in Spanish (⭐260)](https://github.com/brunocascio/docker-espanol) This Spanish guide contains the use of basic docker commands with real life examples.
*   [Setting Python Development Environment with VScode and Docker (⭐952)](https://github.com/RamiKrispin/vscode-python): A step-by-step tutorial for setting up a dockerized Python development environment with VScode, Docker, and the Dev Container extension.
*   [The Docker Handbook](https://docker-handbook.farhan.dev/) An open-source book that teaches you the fundamentals, best practices and some intermediate Docker functionalities. The book is hosted on [fhsinchy/the-docker-handbook (⭐873)](https://github.com/fhsinchy/the-docker-handbook) and the projects are hosted on [fhsinchy/docker-handbook-projects](https://github.com/fhsinchy/docker-handbook-projects) repository.
*   [eon01 (⭐3.9k)](https://github.com/eon01/DockerCheatSheet)
*   [dimonomid (⭐200)](https://github.com/dimonomid/docker-quick-ref) (PDF)
*   [JensPiegsa (⭐23)](https://github.com/JensPiegsa/docker-cheat-sheet)
*   [wsargent (⭐23k)](https://github.com/wsargent/docker-cheat-sheet) (Most popular)

### Where to Start (Windows) / Wrappers

*   [Docker on Windows behind a firewall](https://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/)
*   [Docker Reference Architecture: Modernizing Traditional .NET Framework Applications](https://docs.mirantis.com/containers/v3.0/dockeree-ref-arch/app-dev/modernize-dotnet-apps.html) - You will learn to identify the types of .NET Framework applications that are good candidates for containerization, the "lift-and-shift" approach to containerization.
*   [Docker with Microsoft SQL 2016 + ASP.NET](https://blog.alexellis.io/docker-does-sql2016-aspnet/) Demonstration running ASP.NET and SQL Server workloads in Docker
*   [Exploring ASP.NET Core with Docker in both Linux and Windows Containers](https://www.hanselman.com/blog/exploring-aspnet-core-with-docker-in-both-linux-and-windows-containers) Running ASP.NET Core apps in Linux and Windows containers, using [Docker for Windows](https://docs.docker.com/desktop/setup/install/windows-install/)
*   [Running a Legacy ASP.NET App in a Windows Container](https://blog.sixeyed.com/dockerizing-nerd-dinner-part-1-running-a-legacy-asp-net-app-in-a-windows-container/) Steps for Dockerizing a legacy ASP.NET app and running as a Windows container
*   [Windows Containers and Docker: The 101](https://www.youtube.com/watch?v=N7SG2wEyQtM) - A 20-minute overview, using Docker to run PowerShell, ASP.NET Core and ASP.NET apps.
*   [Windows Containers Quick Start](https://learn.microsoft.com/en-us/virtualization/windowscontainers/about/) Overview of Windows containers, drilling down to Quick Starts for Windows 10 and Windows Server 2016

## [Apr 29, 2026](/content/2026/04/29/README.md)

### User Interfaces / Terminal

*   [wharf (⭐7)](https://github.com/idesyatov/wharf) - A k9s-inspired TUI for Docker Compose with vim-style navigation, real-time CPU/MEM monitoring with braille charts, container file browser, SSH remote host support, and command mode.

## [Apr 24, 2026](/content/2026/04/24/README.md)

### Image Lifecycle / Image Scanning & SBOM

*   [pindock (⭐2)](https://github.com/deadnews/pindock) - Pin and update Docker image digests in Dockerfiles and compose files.

### User Interfaces / Terminal

*   [easydocker (⭐118)](https://github.com/joao-zanutto/easydocker) - A Terminal UI highly inpired by k9s levaraging beatiful BubbleTea graphics.

## [Apr 01, 2026](/content/2026/04/01/README.md)

### Engine & Runtime

*   [Mocker (⭐270)](https://github.com/us/mocker) - Docker-compatible container CLI for macOS, built on Apple's Containerization framework.

### Image Lifecycle / Registry

*   [NORA (⭐195)](https://github.com/getnora-io/nora) - Lightweight multi-protocol artifact registry supporting Docker, Maven, npm, Cargo and PyPI in a single 32MB binary. Pull-through cache, Web UI, Prometheus metrics, RBAC auth.

### Image Lifecycle / Image Scanning & SBOM

*   [Grype (⭐13k)](https://github.com/anchore/grype) - A vulnerability scanner for container images, filesystems and SBOMs.

### Observability / Reverse Proxy

*   [Docker-Sentinel](https://github.com/Will-Luck/Docker-Sentinel) - Automated container updates with per-container policies, rollback safety, and a real-time web dashboard.
*   [Wiremap (⭐4)](https://github.com/codeofmario/wiremap) - A self-hosted visual Docker network topology explorer with real-time log streaming, live stats, embedded terminal, and container inspection.

### Security / Reverse Proxy

*   [Den (⭐8)](https://github.com/us/den) - Self-hosted sandbox runtime for AI agents with Docker containers, security hardening, REST API and WebSocket support.

### User Interfaces / Terminal

*   [swarmcli (⭐19)](https://github.com/Eldara-Tech/swarmcli) - Swarm Management at the speed of thought — with real-time log streaming, instant shell access to containers, seamless port forwarding, and on-demand secret reveal capabilities, giving you full control over your Docker Swarm without breaking your flow.
*   [tdocker (⭐84)](https://github.com/pivovarit/tdocker) - A `docker ps` replacement for everyday container operations.

### Developer Workflow / Development Environment

*   [HarborPilot (⭐2)](https://github.com/potterwhite/HarborPilot) - Automated multi-platform Docker image builder for embedded Linux development (RK3588, RV1126, RK3568). Features three-layer config inheritance, PORT\_SLOT-based port allocation, and cross-version Ubuntu support (20.04/22.04/24.04).

## [Mar 18, 2026](/content/2026/03/18/README.md)

### Observability / Reverse Proxy

*   [DockProbe (⭐16)](https://github.com/deep-on/dockprobe) - Lightweight Docker monitoring dashboard in a single container. Real-time metrics, 6 anomaly detection rules, Telegram alerts, and 16 automated security scans. Zero config, \~50MB RAM.
*   [Maintenant (⭐377)](https://github.com/kolapsis/maintenant) - Self-discovering infrastructure monitoring for Docker and Kubernetes. Auto-detects containers via labels, with endpoint monitoring, heartbeats, TLS certificates, resource metrics, update intelligence, and a built-in status page. Single binary with embedded SPA.

## [Mar 11, 2026](/content/2026/03/11/README.md)

### Observability / Reverse Proxy

*   [ADRG (⭐9)](https://github.com/jaldertech/adrg) - Dynamic Docker resource governor using cgroups v2 to manage system load.

### User Interfaces / Web

*   [Arcane (⭐6.1k)](https://github.com/getarcaneapp/arcane) - An easy and modern Docker management platform, built with everybody in mind.

## [Feb 28, 2026](/content/2026/02/28/README.md)

### Running Containers / Deployment & Platforms

*   [Google Container Engine](https://docs.cloud.google.com/kubernetes-engine/docs) - :yen: Docker containers on Google Cloud Computing powered by [Kubernetes](https://kubernetes.io).

### Observability / Reverse Proxy

*   [Dynatrace](https://docs.dynatrace.com/docs/observe/infrastructure-observability/container-platform-monitoring) - :yen: Monitor containerized applications without installing agents or modifying your Run commands.

### Developer Workflow / Testing

*   [dgoss (⭐5.9k)](https://github.com/goss-org/goss/tree/master/extras/dgoss) - A fast YAML based tool for validating docker containers.

## [Feb 24, 2026](/content/2026/02/24/README.md)

### Networking & Proxies / Reverse Proxy

*   [BunkerWeb (⭐11k)](https://github.com/bunkerity/bunkerweb) - Open-source and next-gen Web Application Firewall (WAF).

### Security / Reverse Proxy

*   [segspec (⭐15)](https://github.com/dormstern/segspec) - Extracts network dependencies from Docker Compose, Kubernetes manifests, Helm charts, and other config files to generate Kubernetes NetworkPolicies with evidence tracing.

### User Interfaces / Web

*   [usulnet (⭐117)](https://github.com/fr4nsys/usulnet) - A complete and modern Docker management platform designed for sysadmin, devops with enterprise grade tools, cve scanner, ssh, rdp on web and much more.

## [Feb 21, 2026](/content/2026/02/21/README.md)

### Observability / Reverse Proxy

*   [Drydock (⭐204)](https://github.com/CodesWhat/drydock) - Container update monitoring with web dashboard, 23 registry providers, 20 notification triggers, and distributed agent architecture.

### Security / Reverse Proxy

*   [buildcage (⭐8)](https://github.com/dash14/buildcage) - Restricts outbound network access during Docker builds to prevent supply chain attacks, working as a drop-in BuildKit remote driver for Docker Buildx, with ready-to-use GitHub Actions.

## [Jan 28, 2026](/content/2026/01/28/README.md)

### Observability / Reverse Proxy

*   [DLIA (⭐5)](https://github.com/zorak1103/dlia) - DLIA is an AI-powered Docker log monitoring agent that uses Large Language Models (LLMs) to intelligently analyze container logs, detect anomalies, and provide contextual insights over time.

## [Jan 27, 2026](/content/2026/01/27/README.md)

### Networking & Proxies / Reverse Proxy

*   [mesh-router (⭐12)](https://github.com/Yundera/mesh-router) - Free domain(nsl.sh) provider for Docker containers with automatic HTTPS routing. Uses Wireguard VPN to securely route subdomain requests across networks. Ideal for self-hosted NAS and cloud deployments.

## [Jan 20, 2026](/content/2026/01/20/README.md)

### Building Images / Linter

*   [Dockadvisor (⭐209)](https://github.com/deckrun/dockadvisor) - Lightweight Dockerfile linter with 60+ rules, quality scoring, and security checks.

## [Jan 19, 2026](/content/2026/01/19/README.md)

### User Interfaces / Terminal

*   [d4s (⭐105)](https://github.com/jr-k/d4s) - A fast, keyboard-driven terminal UI to manage Docker containers, Compose stacks, and Swarm services with the ergonomics of K9s.
*   [DockMate (⭐329)](https://github.com/shubh-io/dockmate) - Lightweight terminal-based Docker and Podman manager with a text-based user interface,.
*   [dprs](https://github.com/durableprogramming/dprs) - A developer-focused TUI for managing Docker containers with real-time log streaming and container management.

## [Nov 17, 2025](/content/2025/11/17/README.md)

### In-Container Tooling / Wrappers

*   [microcheck (⭐145)](https://github.com/tarampampam/microcheck) - Lightweight health check utilities for Docker containers (75 KB instead of 9.3 MB for httpcheck versus cURL) in pure C - http(s), port checks, and parallel execution are included.

## [Oct 30, 2025](/content/2025/10/30/README.md)

### Image Lifecycle / Registry

*   [nscr (⭐1)](https://github.com/jhstatewide/nscr) - A light-weight, self-contained container registry that's easy to run and maintain.

## [Oct 23, 2025](/content/2025/10/23/README.md)

### User Interfaces / Terminal

*   [docker-captain (⭐2)](https://github.com/lucabello/docker-captain) - A friendly CLI to manage multiple Docker Compose deployments with style — powered by Typer, Rich, questionary, and sh.

## [Oct 08, 2025](/content/2025/10/08/README.md)

### User Interfaces / Desktop

*   [Docker DB Manager (⭐163)](https://github.com/AbianS/docker-db-manager) - Desktop app for managing Docker database containers with visual interface and one-click operations.

## [Sep 26, 2025](/content/2025/09/26/README.md)

### Networking & Proxies / Reverse Proxy

*   [OpenResty Manager (⭐1.4k)](https://github.com/Safe3/openresty-manager) - The easiest using, powerful and beautiful OpenResty Manager(Nginx Enhanced Version), open source alternative to OpenResty Edge.

## [Sep 21, 2025](/content/2025/09/21/README.md)

### Image Lifecycle / Registry

*   [GitLab Container Registry](https://docs.gitlab.com/user/packages/container_registry/) - Registry focused on using its images in GitLab CI.

### Observability / Reverse Proxy

*   [Dozzle](https://github.com/veggiemonk/awesome-docker/blob/master/README.md/dozzle) - Monitor container logs in real-time with a browser or mobile device.
*   [Sysdig Monitor](https://www.sysdig.com/products/monitor) - :yen: Software or SaaS service that monitors, alerts, and troubleshoots containers using system calls; container-specific features for Docker and Kubernetes.

### Security / Reverse Proxy

*   [Sysdig Secure](https://www.sysdig.com/solutions/cloud-detection-and-response-cdr) - :yen: Sysdig Secure addresses run-time security through behavioral monitoring and defense, and provides deep forensics based on open source Sysdig for incident response.

### Developer Workflow / CI/CD

*   [Defang (⭐164)](https://github.com/DefangLabs/defang) - Deploy Docker Compose to your favorite cloud in minutes.
*   [Semaphore CI](https://semaphore.io/) - :yen: High-performance cloud CI that builds, tests and ships containers to production.

### Good Tips / Wrappers

*   [Docker vs. VMs? Combining Both for Cloud Portability Nirvana](https://www.flexera.com/blog/finops/)

## [Sep 11, 2025](/content/2025/09/11/README.md)

### Networking & Proxies / Networking

*   [docker-dns (⭐4)](https://github.com/bytesharky/docker-dns) - Lightweight DNS forwarder for Docker containers, resolves container names with custom suffixes (e.g. `.docker`) on the host to simplify service discovery.

## [Aug 27, 2025](/content/2025/08/27/README.md)

### Image Lifecycle / Registry

*   [RepoFlow](https://www.repoflow.io) - A simple and easy-to-use package management platform with Docker support alongside other formats like PyPI, Maven, npm, and Helm. Includes smart search, built-in Docker image scanning, and a great free option for both self-hosted and cloud use.

## [May 18, 2025](/content/2025/05/18/README.md)

### Storage & Data / Reverse Proxy

*   [Label Backup (⭐23)](https://github.com/resulgg/label-backup) - A lightweight, Docker-aware backup agent that automatically discovers and backs up containerized databases (PostgreSQL, MySQL, MongoDB, Redis) based on Docker labels. Supports local storage and S3-compatible destinations with flexible scheduling via cron expressions.

## [May 08, 2025](/content/2025/05/08/README.md)

### Running Containers / Deployment & Platforms

*   [docker-to-iac (⭐21)](https://github.com/deploystackio/docker-to-iac) - Translate docker run and commit into Infrastructure as Code templates for AWS, Render.com and DigitalOcean.

## [Jan 31, 2025](/content/2025/01/31/README.md)

### User Interfaces / Terminal

*   [lazyjournal (⭐1.3k)](https://github.com/Lifailon/lazyjournal) - A interface for reading and filtering the logs output of Docker and Podman containers like [Dozzle](https://github.com/veggiemonk/awesome-docker/blob/master/README.md/dozzle) but for the terminal with support for fuzzy find, regex and output coloring.

## [Nov 12, 2024](/content/2024/11/12/README.md)

### User Interfaces / Web

*   [Komodo (⭐12k)](https://github.com/mbecker20/komodo) - A tool to build and deploy software on many servers.

## [Oct 22, 2024](/content/2024/10/22/README.md)

### Building Images / Builder

*   [docker-repack](https://github.com/orf/docker-repack) - Repacks a Docker image into a smaller, more efficient version that makes it significantly faster to pull.

## [Oct 07, 2024](/content/2024/10/07/README.md)

### Running Containers / Deployment & Platforms

*   [swarm-ansible (⭐57)](https://github.com/LombardiDaniel/swarm-ansible?tab=readme-ov-file) - Swarm-Ansible bootstraps a production-ready swarm cluster using ansible. Comes with tools to automate CI, help monitoring and traefik pre-configured for SSL certificates and simple-auth. Comes with a private registry and more!.

## [Aug 15, 2024](/content/2024/08/15/README.md)

### Running Containers / Deployment & Platforms

*   [OpenShift](https://okd.io/) - An open source PaaS built on [Kubernetes](https://kubernetes.io) and optimized for Dockerized app development and deployment by [Red Hat](https://www.redhat.com/en)

## [Jul 13, 2024](/content/2024/07/13/README.md)

### Image Lifecycle / Image Scanning & SBOM

*   [Anchor Enterprise](https://anchore.com/) - :yen: Analyze images for CVE vulnerabilities and against custom security policies.
*   [Syft (⭐9.2k)](https://github.com/anchore/syft) - CLI tool and library for generating a Software Bill of Materials (SBOM) from container images and filesystems.

## [Jun 24, 2024](/content/2024/06/24/README.md)

### User Interfaces / Terminal

*   [goManageDocker (⭐641)](https://github.com/ajayd-san/gomanagedocker) - TUI tool to view and manage your docker objects blazingly fast with sensible keybindings, also supports VIM navigation out of the box.

### Security Articles / Wrappers

*   [Docker Security: Are Your Containers Tightly Secured to the Ship? SlideShare](https://www.slideshare.net/slideshow/docker-security-are-your-containers-tightly-secured-to-the-ship/43834790)

## [Jun 13, 2024](/content/2024/06/13/README.md)

### Networking & Proxies / Reverse Proxy

*   [caddy-docker-upstreams (⭐36)](https://github.com/invzhi/caddy-docker-upstreams) - Docker upstreams module for Caddy, configured with container labels.

## [May 27, 2024](/content/2024/05/27/README.md)

### Image Lifecycle / Image Scanning & SBOM

*   [Anchor (⭐24)](https://github.com/SongStitch/anchor/) - A tool to ensure reproducible builds by pinning dependencies inside your Dockerfiles.

## [May 15, 2024](/content/2024/05/15/README.md)

### Developer Workflow / API Client

*   [docker-controller-bot (⭐253)](https://github.com/dgongut/docker-controller-bot) - Telegram bot to control docker containers.

## [Apr 06, 2024](/content/2024/04/06/README.md)

### Security Articles / Wrappers

*   [Security Best Practices for Building Docker Images](https://linux-audit.com/tags/docker/)

## [Feb 04, 2024](/content/2024/02/04/README.md)

### Running Containers / Garbage Collection

*   [Docuum (⭐700)](https://github.com/stepchowfun/docuum) - Least recently used (LRU) eviction of Docker images.

### Developer Workflow / CI/CD

*   [Gantry (⭐89)](https://github.com/shizunge/gantry) - Automatically update selected Docker swarm services.

## [Feb 03, 2024](/content/2024/02/03/README.md)

### User Interfaces / Web

*   [dockge (⭐24k)](https://github.com/louislam/dockge) - Easy-to-use and reactive self-hosted docker compose.yaml stack-oriented manager.

## [Jan 21, 2024](/content/2024/01/21/README.md)

### Image Lifecycle / Registry

*   [Gitea Container Registry](https://docs.gitea.com/usage/packages/container) - Integrated Docker registry in Gitea, ideal for private, small-scale image hosting.
*   [GitHub Container Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry) - GitHub's solution for storing and managing Docker images, with tight integration into GitHub Actions.

## [Jan 15, 2024](/content/2024/01/15/README.md)

### Developer Workflow / CI/CD

*   [dockcheck (⭐2.4k)](https://github.com/mag37/dockcheck) - A script checking updates for docker images without pulling then auto-update selected/all containers. With notifications, pruning and more.

## [Jan 04, 2024](/content/2024/01/04/README.md)

### Developer Workflow / CI/CD

*   [Tekton CD](https://tekton.dev/) - A cloud-native pipeline resource.

## [Nov 28, 2023](/content/2023/11/28/README.md)

### User Interfaces / Terminal

*   [oxker (⭐1.7k)](https://github.com/mrjackwills/oxker) - A simple tui to view & control docker containers.

## [Oct 20, 2023](/content/2023/10/20/README.md)

### Networking & Proxies / Reverse Proxy

*   [caddy-docker-proxy (⭐4.5k)](https://github.com/lucaslorentz/caddy-docker-proxy) - Caddy-based reverse proxy, configured with service or container labels.

### Developer Workflow / Development Environment

*   [uniget (⭐22)](https://github.com/uniget-org/cli) - Uni(versal)get, the installer and updater for container tools and beyond (formerly docker-setup).

## [Sep 27, 2023](/content/2023/09/27/README.md)

### Building Images / Builder

*   [packer](https://developer.hashicorp.com/packer/integrations/hashicorp/docker/latest/components/builder/docker) - Hashicorp tool to build machine images including docker image integrated with configuration management tools like chef, puppet, ansible.

## [Sep 02, 2023](/content/2023/09/02/README.md)

### User Interfaces / Terminal

*   [decompose (⭐135)](https://github.com/s0rg/decompose) - Reverse-engineering tool for docker environments.

## [Aug 06, 2023](/content/2023/08/06/README.md)

### Developer Workflow / Wrappers

*   [Preevy (⭐2.2k)](https://github.com/livecycle/preevy) - Preview environments for Docker and Docker Compose projects. Test your changes and get feedback from devs and non-devs (Product/Design) by deploying pull requests to the your cloud provider as part of your CI pipeline.

## [Jun 11, 2023](/content/2023/06/11/README.md)

### Books & Tutorials / Wrappers

*   [Docker Blog](https://www.docker.com/blog/) - Regular updates about Docker, the community and tools.

## [May 31, 2023](/content/2023/05/31/README.md)

### In-Container Tooling / Wrappers

*   [Ofelia (⭐3.9k)](https://github.com/mcuadros/ofelia/) - Ofelia is a modern and low footprint job scheduler for docker environments, built on Go. Ofelia aims to be a replacement for the old fashioned cron. Supports configuration from container labels and/or configuration files.

## [May 20, 2023](/content/2023/05/20/README.md)

### Image Lifecycle / Registry

*   [Sonatype Nexus Repository](https://www.sonatype.com/products/sonatype-nexus-repository) - Manage binaries and build artifacts across your software supply chain.

## [Apr 17, 2023](/content/2023/04/17/README.md)

### Observability / Reverse Proxy

*   [Better Stack](https://betterstack.com/community/guides/scaling-docker/) - :yen: A Docker-compatible observability stack that delivers log aggregation and uptime monitoring for containerized apps.

## [Apr 03, 2023](/content/2023/04/03/README.md)

### User Interfaces / Terminal

*   [dctl (⭐23)](https://github.com/FabienD/docker-stack) - Dctl is a Cli tool that helps developers by allowing them to execute all docker compose commands anywhere in the terminal, and more.

## [Mar 24, 2023](/content/2023/03/24/README.md)

### Developer Workflow / Testing

*   [Kurtosis (⭐544)](https://github.com/kurtosis-tech/kurtosis) - A composable build system for multi-container test environments that provides developers with: a powerful Python-like SDK for environment configuration, a compile-time validator to verify environment behavior & setup, and a runtime for environment execution, monitoring, & debugging capabilities.

## [Mar 23, 2023](/content/2023/03/23/README.md)

### Developer Workflow / CI/CD

*   [Jaypore CI (⭐37)](https://github.com/theSage21/jaypore_ci) - Simple, very flexible, powerful CI / CD / automation system configured in Python. Offline and local first.

## [Mar 08, 2023](/content/2023/03/08/README.md)

### Security / Reverse Proxy

*   [CetusGuard](https://github.com/hectorm/cetusguard) - CetusGuard is a tool that protects the Docker daemon socket by filtering calls to its API endpoints.

## [Feb 19, 2023](/content/2023/02/19/README.md)

### In-Container Tooling / Wrappers

*   [dockerize (⭐193)](https://github.com/powerman/dockerize) - Utility to simplify running applications in docker containers.

## [Feb 13, 2023](/content/2023/02/13/README.md)

### Running Containers / Orchestration

*   [docker rollout (⭐3.3k)](https://github.com/Wowu/docker-rollout) - Zero downtime deployment for Docker Compose services.

## [Jan 23, 2023](/content/2023/01/23/README.md)

### Books & Tutorials / Wrappers

*   [Docker Certification](https://intellipaat.com/docker-training-course/?US) - :yen: Will help you to will Learn Docker containerization, running Docker containers, Image creation, Dockerfile, Docker orchestration, security best practices, and more through hands-on projects and case studies and helps to clear Docker Certified Associate.
*   [Docker dev bookmarks](https://www.codever.dev/search?q=docker) - Use the tag [docker](https://www.codever.dev/bookmarks/t/docker).

## [Jan 20, 2023](/content/2023/01/20/README.md)

### Image Lifecycle / Registry

*   [Dragonfly (⭐3.2k)](https://github.com/dragonflyoss/Dragonfly2) - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology.

## [Jan 04, 2023](/content/2023/01/04/README.md)

### Security Articles / Wrappers

*   [10 best practices to containerize Node.js web applications with Docker](https://snyk.io/blog/10-best-practices-to-containerize-nodejs-web-applications-with-docker/)

## [Nov 05, 2022](/content/2022/11/05/README.md)

### Running Containers / Deployment & Platforms

*   [Azure AKS](https://azure.microsoft.com/en-us/products/kubernetes-service/) - :yen: Fully managed Kubernetes container orchestration service.

### Observability / Reverse Proxy

*   [Grafana Docker Dashboard Template](https://grafana.com/grafana/dashboards/179-docker-prometheus-monitoring/) - A template for your Docker, Grafana and Prometheus stack.

### Developer Workflow / Wrappers

*   [Vagrant - Docker provider](https://developer.hashicorp.com/vagrant/docs/providers/docker/basics) - Good starting point is [vagrant-docker-example (⭐113)](https://github.com/bubenkoff/vagrant-docker-example).

## [Oct 10, 2022](/content/2022/10/10/README.md)

### Storage & Data / Reverse Proxy

*   [Docker Volume Backup (⭐3.7k)](https://github.com/offen/docker-volume-backup) Backup Docker volumes locally or to any S3 compatible storage.

## [Sep 28, 2022](/content/2022/09/28/README.md)

### Networking & Proxies / Networking

*   [Calico](https://github.com/projectcalico/calico) - Calico is a pure layer 3 virtual network that allows containers over multiple docker-hosts to talk to each other.

## [Sep 22, 2022](/content/2022/09/22/README.md)

### Security / Reverse Proxy

*   [Checkov (⭐8.8k)](https://github.com/bridgecrewio/checkov) - Static analysis for infrastructure as code manifests (Terraform, Kubernetes, Cloudformation, Helm, Dockerfile, Kustomize) find security misconfiguration and fix them.

## [Aug 02, 2022](/content/2022/08/02/README.md)

### Running Containers / Composition

*   [ctk (⭐300)](https://github.com/ctk-hq/ctk) - Visual composer for container based workloads.

## [Jul 13, 2022](/content/2022/07/13/README.md)

### Engine & Runtime

*   [cri-o (⭐5.6k)](https://github.com/cri-o/cri-o) - Open Container Initiative-based implementation of Kubernetes Container Runtime Interface.
*   [lxc (⭐5.2k)](https://github.com/lxc/lxc) - LXC - Linux Containers.
*   [podman (⭐32k)](https://github.com/containers/libpod) - Libpod is a library used to create container pods. Home of Podman.
*   [runtime-tools (⭐487)](https://github.com/opencontainers/runtime-tools) - Oci-runtime-tool is a collection of tools for working with the OCI runtime specification.

### Building Images / Builder

*   [ansible-bender (⭐696)](https://github.com/ansible-community/ansible-bender) - A tool utilising `ansible` and `buildah`.
*   [buildah (⭐8.9k)](https://github.com/containers/buildah) - A tool that facilitates building OCI images.
*   [BuildKit (⭐10k)](https://github.com/moby/buildkit) - Concurrent, cache-efficient, and Dockerfile-agnostic builder toolkit.
*   [cekit (⭐112)](https://github.com/cekit/cekit) - A tool used by openshift to build base images using different build engines.
*   [dlayer (⭐444)](https://github.com/orisano/dlayer) - Docker layer analyzer.
*   [docker-companion (⭐47)](https://github.com/mudler/docker-companion) - A command line tool written in Golang to squash and unpack docker images.
*   [DockerSlim (⭐23k)](https://github.com/docker-slim/docker-slim) shrinks fat Docker images creating the smallest possible images.
*   [essex (⭐38)](https://github.com/utensils/essex) - Boilerplate for Docker Based Projects: Essex is a CLI utility written in bash to quickly setup clean and consistent Docker projects with Makefile driven workflows.
*   [HPC Container Maker (⭐514)](https://github.com/NVIDIA/hpc-container-maker) - Generates Dockerfiles from a high level Python recipe, including building blocks for High-Performance Computing components.
*   [img (⭐4k)](https://github.com/genuinetools/img) - Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder.
*   [RAUDI (⭐558)](https://github.com/cybersecsi/RAUDI) - A tool to automatically update (and optionally push to Docker Hub) Docker Images for 3rd party software whenever theres is a new release/update/commit.
*   [runlike (⭐2.9k)](https://github.com/lavie/runlike) - Generate `docker run`command and options from running containers.
*   [Whaler (⭐1.2k)](https://github.com/P3GLEG/Whaler) - Program to reverse Docker images into Dockerfiles.

### Building Images / Base Images

*   [distroless (⭐23k)](https://github.com/GoogleContainerTools/distroless) - Language focused docker images, minus the operating system.

### Building Images / Dockerfile

*   [Dockerfile Generator (⭐187)](https://github.com/ozankasikci/dockerfile-generator) `dfg` is both a Go library and an executable that produces valid Dockerfiles using various input channels.
*   [Dockershelf (⭐96)](https://github.com/Dockershelf/dockershelf) - A repository that serves as a collector for docker recipes that are universal, efficient and slim. Images are updated, tested and published daily via a Travis cron job.

### Building Images / Linter

*   [docker-image-size-limit (⭐131)](https://github.com/wemake-services/docker-image-size-limit) - A tool to keep an eye on your docker images size.
*   [Hadolint (⭐12k)](https://github.com/hadolint/hadolint) - A Dockerfile linter that checks for best practices, common mistakes, and is also able to lint any bash written in `RUN` instructions;.

### Image Lifecycle / Registry

*   [Docker Hub](https://hub.docker.com/) provided by Docker Inc.
*   [Docker Registry v2 (⭐10k)](https://github.com/docker/distribution) - The Docker toolset to pack, ship, store, and deliver content
*   [Harbor (⭐29k)](https://github.com/goharbor/harbor) An open source trusted cloud native registry project that stores, signs, and scans content. Supports replication, user management, access control and activity auditing.
*   [Kraken (⭐6.7k)](https://github.com/uber/kraken) - Uber's Highly scalable P2P docker registry, capable of distributing TBs of data in seconds.
*   [Registryo (⭐15)](https://github.com/inmagik/registryo) - UI and token based authentication server for onpremise docker registry.

### Image Lifecycle / Registry CLI

*   [skopeo (⭐11k)](https://github.com/containers/skopeo) - Work with remote image registries: retrieve information, copy images, sign content.

### Image Lifecycle / Image Scanning & SBOM

*   [Clair (⭐11k)](https://github.com/quay/clair) - Clair is an open source project for the static analysis of vulnerabilities in appc and docker containers.
*   [oscap-docker (⭐1.8k)](https://github.com/OpenSCAP/openscap) - OpenSCAP provides oscap-docker tool which is used to scan Docker containers and images.
*   [Trivy (⭐37k)](https://github.com/aquasecurity/trivy) - Aqua Security's open source simple and comprehensive vulnerability scanner for containers (suitable for CI).

### Running Containers / Composition

*   [Composerize (⭐3.7k)](https://github.com/magicmark/composerize) - Convert docker run commands into docker-compose files.
*   [kompose (⭐11k)](https://github.com/kubernetes/kompose) - Go from Docker Compose to Kubernetes.
*   [plash (⭐383)](https://github.com/ihucos/plash) - A container run and build engine - runs inside docker.
*   [podman-compose (⭐6.1k)](https://github.com/containers/podman-compose) - A script to run docker-compose.yml using podman.
*   [Smalte (⭐36)](https://github.com/roquie/smalte) – Dynamically configure applications that require static configuration in docker container.

### Running Containers / Orchestration

*   [CloudSlang (⭐241)](https://github.com/CloudSlang/cloud-slang) - CloudSlang is a workflow engine to create Docker process automation.
*   [Kubernetes (⭐123k)](https://github.com/kubernetes/kubernetes) - Open source orchestration system for Docker containers by Google.
*   [Mesos (⭐5.4k)](https://github.com/apache/mesos) - Resource/Job scheduler for containers, VM's and physical hosts.
*   [Nebula](https://github.com/nebula-orchestrator) - A Docker orchestration tool designed to manage massive scale distributed clusters.
*   [Nomad (⭐17k)](https://github.com/hashicorp/nomad) - Easily deploy applications at any scale. A Distributed, Highly Available, Datacenter-Aware Scheduler.
*   [Rancher (⭐26k)](https://github.com/rancher/rancher) - An open source project that provides a complete platform for operating Docker in production.
*   [Swarm-cronjob (⭐876)](https://github.com/crazy-max/swarm-cronjob) - Create jobs on a time-based schedule on Swarm.

### Running Containers / Deployment & Platforms

*   [Amazon ECS](https://aws.amazon.com/ecs/) - :yen: A management service on EC2 that supports Docker containers.
*   [Appfleet](https://appfleet.com/) - :yen: Edge platform to deploy and manage containerized services globally; routes traffic to the closest location for low latency.
*   [blackfish](https://gitlab.com/blackfish/blackfish) - A CoreOS VM to build swarm clusters for Dev & Production.
*   [BosnD](https://gitlab.com/n0r1sk/bosnd) - BosnD, the boatswain daemon - A dynamic configuration file writer & service reloader for dynamically changing container environments.
*   [caprover (⭐15k)](https://github.com/caprover/caprover) - \[Previously known as CaptainDuckDuck] Automated Scalable Webserver Package (automated Docker+nginx) - Heroku on Steroids.
*   [Cloud 66](https://www.cloud66.com) - :yen: Full-stack hosted container management as a service.
*   [Convox Rack (⭐1.9k)](https://github.com/convox/rack) - Convox Rack is open source PaaS built on top of expert infrastructure automation and devops best practices.
*   [Dokku (⭐32k)](https://github.com/dokku/dokku) - Docker powered mini-Heroku that helps you build and manage the lifecycle of applications.
*   [Exoframe](https://github.com/exoframejs/exoframe) - A self-hosted tool that allows simple one-command deployments using Docker.
*   [Giant Swarm](https://www.giantswarm.io/) - :yen: Simple microservice infrastructure. Deploy your containers in seconds.
*   [Grafeas (⭐1.6k)](https://github.com/grafeas/grafeas) - A common API for metadata about containers, from image and build details to security vulnerabilities.
*   [Mesosphere DC/OS Platform](https://d2iq.com/products/dcos) - :yen: Integrated platform for data and containers built on Apache Mesos.
*   [Red Hat OpenShift Dedicated](https://www.redhat.com/en/technologies/cloud-computing/openshift/dedicated) - :yen: Fully-managed Red Hat® OpenShift® service on Amazon Web Services and Google Cloud.
*   [SwarmManagement (⭐21)](https://github.com/hansehe/SwarmManagement) - Swarm Management is a python application, installed with pip. The application makes it easy to manage a Docker Swarm by configuring a single yaml file describing which stacks to deploy, and which networks, configs or secrets to create.
*   [Triton](https://www.joyent.com/) - :yen: Elastic container-native infrastructure.
*   [Tsuru](https://github.com/tsuru/tsuru) - Tsuru is an extensible and open source Platform as a Service software.
*   [werf (⭐4.7k)](https://github.com/werf/werf) - Werf is a CI/CD tool for building Docker images efficiently and deploying them to Kubernetes using GitOps.

### Running Containers / Garbage Collection

*   [docker-custodian](https://github.com/Yelp/docker-custodian) - Keep docker hosts tidy.

### Networking & Proxies / Networking

*   [Flannel (⭐9.5k)](https://github.com/coreos/flannel/) - Flannel is a virtual network that gives a subnet to each host for use with container runtimes.
*   [netshoot (⭐11k)](https://github.com/nicolaka/netshoot) - The netshoot container has a powerful set of networking tools to help troubleshoot Docker networking issues.
*   [Pipework (⭐4.3k)](https://github.com/jpetazzo/pipework) - Software-Defined Networking for Linux Containers, Pipework works with "plain" LXC containers, and with the awesome Docker.
*   [registrator (⭐4.7k)](https://github.com/gliderlabs/registrator) - Service registry bridge for Docker.

### Networking & Proxies / Reverse Proxy

*   [Docker Dnsmasq Updater (⭐34)](https://github.com/moonbuggy/docker-dnsmasq-updater) - Update a remote dnsmasq server with Docker container hostnames.
*   [docker-flow-proxy (⭐319)](https://github.com/docker-flow/docker-flow-proxy) - Reconfigures proxy every time a new service is deployed, or when a service is scaled.
*   [Let's Encrypt Nginx-proxy Companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) - A lightweight companion container for the nginx-proxy. It allow the creation/renewal of Let's Encrypt certificates automatically.
*   [Nginx Proxy Manager (⭐33k)](https://github.com/jc21/nginx-proxy-manager) - A beautiful web interface for proxying web based services with SSL.
*   [nginx-proxy (⭐20k)](https://github.com/nginx-proxy/nginx-proxy) - Automated nginx proxy for Docker containers using docker-gen.
*   [Swarm Router (⭐75)](https://github.com/flavioaiello/swarm-router) - A zero config service name based router for docker swarm mode with a fresh and more secure approach.
*   [Træfɪk (⭐64k)](https://github.com/containous/traefik) - Automated reverse proxy and load-balancer for Docker, Mesos, Consul, Etcd.

### Storage & Data / Reverse Proxy

*   [Netshare (⭐1.1k)](https://github.com/ContainX/docker-volume-netshare) Docker NFS, AWS EFS, Ceph & Samba/CIFS Volume Plugin.
*   [portworx](https://portworx.com) - :yen: Decentralized storage solution for persistent, shared and replicated volumes.
*   [quobyte](https://www.quobyte.com/) - :yen: Fully fault-tolerant distributed file system with a docker volume driver.
*   [REX-Ray](https://github.com/rexray/rexray) provides a vendor agnostic storage orchestration engine. The primary design goal is to provide persistent storage for Docker, Kubernetes, and Mesos.

### Observability / Reverse Proxy

*   [AppDynamics](https://github.com/Appdynamics/docker-monitoring-extension) - :yen: Docker Monitoring extension gathers metrics from the Docker Remote API, either using Unix Socket or TCP.
*   [Autoheal (⭐1.9k)](https://github.com/willfarrell/docker-autoheal) - Monitor and restart unhealthy docker containers automatically.
*   [cAdvisor (⭐19k)](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers.
*   [Datadog](https://www.datadoghq.com/) - :yen: Full-stack monitoring service with first-class Docker, Kubernetes, and Mesos support.
*   [DockProc](https://gitlab.com/n0r1sk/dockproc) - I/O monitoring for containers on processlevel.
*   [dockprom (⭐6.6k)](https://github.com/stefanprodan/dockprom) - Docker hosts and containers monitoring with Prometheus, Grafana, cAdvisor, NodeExporter and AlertManager.
*   [Doku (⭐418)](https://github.com/amerkurev/doku) - Doku is a simple web-based application that allows you to monitor Docker disk usage.
*   [Site24x7](https://www.site24x7.com/docker-monitoring.html) - :yen: Docker Monitoring for DevOps and IT, SaaS Pay-per-Host model.

### Security / Reverse Proxy

*   [Aqua Security](https://www.aquasec.com) - :yen: Securing container-based applications from Dev to Production on any platform.
*   [Deepfence Threat Mapper (⭐5.3k)](https://github.com/deepfence/ThreatMapper) - Powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless.
*   [docker-bench-security (⭐9.7k)](https://github.com/docker/docker-bench-security) - Script that checks for dozens of common best-practices around deploying Docker containers in production.
*   [KICS (⭐2.7k)](https://github.com/checkmarx/kics) - An infrastructure-as-code scanning tool, find security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle. Can be extended for additional policies.
*   [Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) - :yen: (Previously Twistlock Security Suite) detects vulnerabilities, hardens container images, and enforces security policies across the lifecycle of applications.
*   [Sysdig Falco (⭐9.1k)](https://github.com/falcosecurity/falco) - Sysdig Falco is an open source container security monitor. It can monitor application, container, host, and network activity and alert on unauthorized activity.
*   [Trend Micro DeepSecurity](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/deep-security.html) - :yen: Trend Micro DeepSecurity offers runtime protection for container workloads and hosts as well as preruntime scanning of images to identify vulnerabilities, malware and content such as hardcoded secrets.

### User Interfaces / Desktop

*   [Docker Desktop](https://www.docker.com/products/docker-desktop/) - Official native app. Only for Windows and MacOS.
*   [Simple Docker UI](https://github.com/felixgborrego/simple-docker-ui) - Built on Electron.
*   [Stevedore (⭐373)](https://github.com/slonopotamus/stevedore) - Good Docker Desktop replacement for Windows. Both Linux and Windows Containers are supported. [slonopotamus](https://github.com/slonopotamus).

### User Interfaces / Terminal

*   [dcinja](https://github.com/Falldog/dcinja) - The powerful and smallest binary size of template engine for docker command line environment.
*   [dive (⭐54k)](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image.
*   [docker pushrm (⭐152)](https://github.com/christian-korneck/docker-pushrm) - A Docker CLI plugin that lets you push the README.md file from the current directory to Docker Hub. Also supports Quay and Harbor.
*   [dockerfile-mode (⭐563)](https://github.com/spotify/dockerfile-mode) - An Emacs mode for handling Dockerfiles.
*   [dockerfilegraph (⭐266)](https://github.com/patrickhoefler/dockerfilegraph) - Visualize your multi-stage Dockerfiles.
*   [dockly (⭐4k)](https://github.com/lirantal/dockly) - An interactive shell UI for managing Docker containers.
*   [DockSTARTer (⭐2.6k)](https://github.com/GhostWriters/DockSTARTer) - DockSTARTer helps you get started with home server apps running in Docker.
*   [dry (⭐3.3k)](https://github.com/moncho/dry) - An interactive CLI for Docker containers.
*   [lazydocker (⭐52k)](https://github.com/jesseduffield/lazydocker) - The lazier way to manage everything docker. A simple terminal UI for both docker and docker-compose, written in Go with the gocui library.
*   [proco (⭐112)](https://github.com/shiwaforce/poco) - Proco will help you to organise and manage Docker, Docker-Compose, Kubernetes projects of any complexity using simple YAML config files to shorten the route from finding your project to initialising it in your local environment.
*   [scuba](https://github.com/JonathonReinhart/scuba) - Transparently use Docker containers to encapsulate software build environments,.
*   [supdock (⭐86)](https://github.com/segersniels/supdock) - Allows for slightly more visual usage of Docker with an interactive prompt.

### User Interfaces / Web

*   [CASA (⭐85)](https://github.com/knrdl/casa) - Outsource the administration of a handful of containers to your co-workers,.
*   [Container Web TTY (⭐257)](https://github.com/wrfly/container-web-tty) - Connect your containers via a web-tty.
*   [Docker Registry Browser](https://github.com/klausmeyer/docker-registry-browser) - Web Interface for the Docker Registry HTTP API v2.
*   [docker-swarm-visualizer (⭐3.3k)](https://github.com/dockersamples/docker-swarm-visualizer) - Visualizes Docker services on a Docker Swarm (for running demos).
*   [Portainer (⭐38k)](https://github.com/portainer/portainer) - A lightweight management UI for managing your Docker hosts or Docker Swarm clusters.
*   [Swarmpit (⭐3.5k)](https://github.com/swarmpit/swarmpit) - Swarmpit provides simple and easy to use interface for your Docker Swarm cluster. You can manage your stacks, services, secrets, volumes, networks etc.

### User Interfaces / IDE Integrations

*   JetBrains IDEs (IntelliJ IDEA, GoLand, WebStorm, CLion etc.) has [built-in Docker plugin](https://www.jetbrains.com/help/idea/docker.html#managing-images)
*   Eclipse [Docker Tooling plugin](https://www.eclipse.org/community/eclipse_newsletter/2016/july/article2.php)
*   [docker.el (⭐823)](https://github.com/Silex/docker.el) Manage docker from Emacs.

### Developer Workflow / API Client

*   [contajners (⭐148)](https://github.com/lispyclouds/contajners) - An idiomatic, data-driven, REPL friendly Clojure client for OCI container engines.
*   [Docker Client for JVM (⭐121)](https://github.com/gesellix/docker-client) - A Docker remote api client library for the JVM, written in Groovy.
*   [Docker Client TypeScript](https://gitlab.com/masaeedu/docker-client) - Docker API client for JavaScript, automatically generated from Swagger API definition from moby repository.
*   [docker-maven-plugin (⭐1.9k)](https://github.com/fabric8io/docker-maven-plugin) - A Maven plugin for running and creating Docker images.
*   [Docker.DotNet (⭐2.4k)](https://github.com/Microsoft/Docker.DotNet) - C#/.NET HTTP client for the Docker remote API.
*   [Docker.Registry.DotNet](https://github.com/ChangemakerStudios/Docker.Registry.DotNet) - .NET (C#) Client Library for interacting with a Docker Registry API (v2).
*   [dockerode (⭐4.9k)](https://github.com/apocas/dockerode) - Docker Remote API node.js module.
*   [go-dockerclient (⭐2.2k)](https://github.com/fsouza/go-dockerclient/) - Go HTTP client for the Docker remote API.
*   [Gradle Docker plugin (⭐80)](https://github.com/gesellix/gradle-docker-plugin) - A Docker remote api plugin for Gradle.
*   [Portainer stack utils (⭐74)](https://github.com/greenled/portainer-stack-utils) - Bash script to deploy/update/undeploy Docker stacks in a Portainer instance from a docker-compose yaml file.
*   [sbt-docker (⭐732)](https://github.com/marcuslonnberg/sbt-docker) - Create Docker images directly from sbt.

### Developer Workflow / CI/CD

*   [Captain (⭐776)](https://github.com/harbur/captain) - Convert your Git workflow to Docker containers ready for Continuous Delivery.
*   [CircleCI](https://circleci.com/) - :yen: Push or pull Docker images from your build environment, or build and run containers right on CircleCI.
*   [ConcourseCI](https://concourse-ci.org) - :yen: Pipeline-oriented CI SaaS platform for DevOps teams.
*   [Diun (⭐4.8k)](https://github.com/crazy-max/diun) - Receive notifications when an image or repository is updated on a Docker registry.
*   [Docker plugin for Jenkins (⭐498)](https://github.com/jenkinsci/docker-plugin/) - The aim of the docker plugin is to be able to use a docker host to dynamically provision a slave, run a single build, then tear-down that slave.
*   [Drone (⭐37k)](https://github.com/drone/drone) - Continuous integration server built on Docker and configured using YAML files.
*   [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-runner) - GitLab has integrated CI to test, build and deploy your code with the use of GitLab runners.
*   [Kraken CI (⭐159)](https://github.com/Kraken-CI/kraken) - Modern CI/CD, open-source, on-premise system that is highly scalable and focused on testing. One of its executors is Docker. Developed.
*   [Skipper (⭐49)](https://github.com/Stratoscale/skipper) - Easily dockerize your Git repository.
*   [TravisCI](https://www.travis-ci.com/) - :yen: Hosted CI for GitHub projects with Docker support.

### Developer Workflow / Development Environment

*   [coder (⭐14k)](https://github.com/coder/coder) - Remote development machines powered by Terraform or Docker.
*   [dde (⭐46)](https://github.com/whatwedo/dde) - Local development environment toolset based on Docker.
*   [DIP (⭐1.3k)](https://github.com/bibendi/dip) - CLI utility for straightforward provisioning and interacting with an application configured by docker-compose.
*   [EnvCLI](https://github.com/EnvCLI/EnvCLI) - Replace your local installation of Node, Go, ... with project-specific docker containers.
*   [Gebug (⭐631)](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
*   [Lando (⭐4.2k)](https://github.com/lando/lando) - Lando is for developers who want to quickly specify and painlessly spin up the services and tools needed to develop their projects.
*   [Zsh-in-Docker (⭐1.1k)](https://github.com/deluan/zsh-in-docker) - Install Zsh, Oh-My-Zsh and plugins inside a Docker container with one line!.

### Developer Workflow / Serverless

*   [Apache OpenWhisk (⭐6.8k)](https://github.com/apache/openwhisk) - A serverless, open source cloud platform that executes functions in response to events at any scale.
*   [Koyeb](https://www.koyeb.com/) - :yen: Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery.
*   [OpenFaaS (⭐26k)](https://github.com/openfaas/faas) - A complete serverless functions framework for Docker and Kubernetes.

### Developer Workflow / Testing

*   [Container Structure Test (⭐2.5k)](https://github.com/GoogleContainerTools/container-structure-test) - A framework to validate the structure of an image by checking the outputs of commands or the contents of the filesystem.
*   [Pumba (⭐3.1k)](https://github.com/alexei-led/pumba) - Chaos testing tool for Docker. Can be deployed on kubernetes and CoreOS cluster.

### Developer Workflow / Wrappers

*   [Hokusai (⭐97)](https://github.com/artsy/hokusai) - A Docker + Kubernetes CLI for application developers; used to containerize an application and to manage its lifecycle throughout development, testing, and release cycles. From [artsy](https://github.com/artsy).
*   [subuser (⭐894)](https://github.com/subuser-security/subuser) - Makes it easy to securely and portably run graphical desktop applications in Docker.
*   [udocker (⭐1.8k)](https://github.com/indigo-dc/udocker) - A tool to execute simple docker containers in batch or interactive systems without root privileges.

### In-Container Tooling / Wrappers

*   [ckron (⭐56)](https://github.com/nicomt/ckron) - A cron-style job scheduler for docker,.
*   [CoreOS](https://github.com/coreos) - Linux for Massive Server Deployments
*   [docker-gen (⭐4.6k)](https://github.com/jwilder/docker-gen) - Generate files from docker container meta-data.
*   [GoSu (⭐5k)](https://github.com/tianon/gosu) - Run this specific application as this specific user and get out of the pipeline (entrypoint script tool).
*   [is-docker (⭐233)](https://github.com/sindresorhus/is-docker) - Check if the process is running inside a Docker container.
*   [su-exec (⭐1k)](https://github.com/ncopa/su-exec) - This is a simple tool that will simply execute a program with different privileges. The program will be executed directly and not run as a child, like su and sudo does, which avoids TTY and signal issues. Why reinvent gosu? This does more or less exactly the same thing as gosu but it is only 10kb instead of 1.8MB.
*   [supercronic (⭐2.6k)](https://github.com/aptible/supercronic) - Crontab-compatible job runner, designed specifically to run in containers.

### Books & Tutorials / Wrappers

*   [Cloud Native Landscape (⭐9.9k)](https://github.com/cncf/landscape)
*   [Docker in Action, Second Edition](https://www.manning.com/books/docker-in-action-second-edition)
*   [Docker in Practice, Second Edition](https://www.manning.com/books/docker-in-practice-second-edition)
*   [Docker packaging guide for Python](https://pythonspeed.com/docker/) - A series of detailed articles on the specifics of Docker packaging for Python.
*   [Learn Docker in a Month of Lunches](https://www.manning.com/books/learn-docker-in-a-month-of-lunches)
*   [Learn Docker](https://coursesity.com/blog/best-docker-tutorials/) - Learn Docker - curated list of the top online docker tutorials and courses.
*   [Programming Community Curated Resources for learning Docker](https://hackr.io/tutorials/learn-docker)

### Awesome Lists / Wrappers

*   [Awesome Compose (⭐46k)](https://github.com/docker/awesome-compose) - Docker Compose samples.
*   [Awesome Kubernetes (⭐16k)](https://github.com/ramitsurana/awesome-kubernetes)
*   [Awesome Linux Container (⭐2.1k)](https://github.com/Friz-zy/awesome-linux-containers) more general about container than this repo.
*   [Awesome Selfhosted (⭐300k)](https://github.com/awesome-selfhosted/awesome-selfhosted) list of Free Software network services and web applications which can be hosted locally by running in a classical way (setup local web server and run applications from there) or in a Docker container.
*   [Awesome Sysadmin (⭐34k)](https://github.com/n1trux/awesome-sysadmin)
*   [ToolsOfTheTrade (⭐17k)](https://github.com/cjbarber/ToolsOfTheTrade) a list of SaaS and On premise applications

### Demos and Examples / Wrappers

*   [An Annotated Docker Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-docker-config-for-frontend-web-development) A local development environment with Docker allows you to shrink-wrap the devops your project needs as config, making onboarding frictionless.
*   [Local Docker DB (⭐299)](https://github.com/alexmacarthur/local-docker-db) a list of docker-compose samples for a lot of databases
*   [Webstack-micro (⭐88)](https://github.com/ferbs/webstack-micro) Demo web app showing how Docker Compose might be used to set up an API Gateway, centralized authentication, background workers, and WebSockets as containerized services.

### Good Tips / Wrappers

*   [Docker Caveats](http://docker-saigon.github.io/post/Docker-Caveats/) What You Should Know About Running Docker In Production (written 11 APRIL 2016).
*   [Docker Containers on the Desktop](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/)
*   [Don't Repeat Yourself with Anchors, Aliases and Extensions in Docker Compose Files](https://medium.com/@kinghuang/docker-compose-anchors-aliases-extensions-a1e4105d70bd)
*   [GUI Apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)

### Raspberry Pi & ARM / Wrappers

*   [Docker Pirates ARMed with explosive stuff](https://blog.hypriot.com/) Huge resource on clustering, swarm, docker, pre-installed image for SD card on Raspberry Pi
*   [Get Docker up and running on the RaspberryPi in three steps (⭐733)](https://github.com/umiddelb/armhf/wiki/Get-Docker-up-and-running-on-the-RaspberryPi-%28ARMv6%29-in-three-steps)
*   [git push docker containers to linux devices](https://www.balena.io) Modern DevOps for IoT, leveraging git and Docker.
*   [Installing, running, using Docker on armhf (ARMv7) devices (⭐733)](https://github.com/umiddelb/armhf/wiki/Installing,-running,-using-docker-on-armhf-%28ARMv7%29-devices)

### Security Articles / Wrappers

*   [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
*   [CVE Scanning Alpine images with Multi-stage builds in Docker 17.05 (⭐11)](https://github.com/tomwillfixit/alpine-cvecheck)
*   [Docker Secure Deployment Guidelines (⭐607)](https://github.com/AonCyberLabs/Docker-Secure-Deployment-Guidelines)
*   [Docker Security - Quick Reference](https://binarymist.io/publication/docker-security/)
*   [How CVE's are handled on Offical Docker Images (⭐7k)](https://github.com/docker-library/official-images/issues/1448)
*   [Lynis is an open source security auditing tool including Docker auditing](https://cisofy.com/lynis/)
*   [Software Engineering Radio interview of Docker Security Team Lead (Diogo Mónica)](https://www.se-radio.net/2017/05/se-radio-episode-290-diogo-monica-on-docker-security/)
*   [Ten Docker Image Security Best Practices Cheat Sheet](https://snyk.io/blog/10-docker-image-security-best-practices/)
*   [Top ten most popular docker images each contain at least 30 vulnerabilities](https://snyk.io/blog/top-ten-most-popular-docker-images-each-contain-at-least-30-vulnerabilities/)
*   [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)

### Videos / Wrappers

*   [Deploying and scaling applications with Docker, Swarm, and a tiny bit of Python magic](https://www.youtube.com/watch?v=GpHMTR7P2Ms) (3:11:06)
*   [Docker Course](https://www.youtube.com/watch?v=UZpyvK6UGFo) (Spanish)
*   [Docker for Developers](https://www.youtube.com/watch?v=FdkNAjjO5yQ) (54:26)
*   [Docker from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxD-btrjrqdEfQHbkZnQrmqE) (1:22:01)
*   [Docker: How to Use Your Own Private Registry](https://www.youtube.com/watch?v=CAewZCBT4PI) (15:01)
*   [Docker in Production](https://www.youtube.com/watch?v=Glk5d5WP6MI) (36:05)
*   [Docker Primer to Docker Compose](https://www.youtube.com/watch?v=G-s2GXGAjTk) (1:56:45)
*   [Docker Registry from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAz3d4Fj3edq7UcxEhdTCBm) (44:40)
*   [Docker Swarm from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAY4gZd1Wl-GsLvg-e9Ap1e) (1:41:28)
*   [Extending Docker with Plugins](https://vimeo.com/110835013) (15:21)
*   [From Local Docker Development to Production Deployments](https://www.youtube.com/watch?v=7CZFpHUPqXw)
*   [Introduction to Docker and containers](https://www.youtube.com/watch?v=ZVaRK10HBjo) (3:09:00)
*   [Logging on Docker: What You Need to Know](https://vimeo.com/123341629) (51:27)
*   [Performance Analysis of Docker - Jeremy Eder](https://www.youtube.com/watch?v=6f2E6PKYb0w) (1:36:58)
*   [Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) Free Udacity course
*   [State of containers: a debate with CoreOS, VMware and Google](https://www.youtube.com/watch?v=IiITP3yIRd8) (27:38)

### Communities and Meetups / Brazilian

*   [Docker BR on Telegram](https://telegram.me/dockerbr)

### Communities and Meetups / English

*   [Docker Community](https://www.docker.com/community/)
*   [Docker Events](https://www.docker.com/events/)
*   [Docker Online Meetup](https://www.meetup.com/en-AU/Docker-Online-Meetup/)
*   [Docker Reddit Community](https://www.reddit.com/r/docker/)

### Communities and Meetups / Russian

*   [Docker Russian-speaking Community](https://t.me/docker_ru)

### Communities and Meetups / Spanish

*   [Docker Tips](https://dockertips.com/)