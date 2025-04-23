# Awesome Opentofu Overview

A curated list of OpenTofu tools, resources, and related projects.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/virtualroot/awesome-opentofu/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 virtualroot/awesome-opentofu](https://github.com/virtualroot/awesome-opentofu) · ⭐ 125 · 🏷️ DevOps

[ [Daily](/content/virtualroot/awesome-opentofu/README.md) / [Weekly](/content/virtualroot/awesome-opentofu/week/README.md) / Overview ]

---

# Awesome OpenTofu [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->

> A curated and collaborative list of awesome OpenTofu resources and tools.

[OpenTofu](https://opentofu.org/) allows you to declaratively manage your infrastructure. It's an open-source, community-driven alternative to Terraform.

## Contents <!-- omit in toc -->

*   [Official](#official)
*   [Community](#community)
*   [Features](#features)
*   [Tools](#tools)
    *   [Environment managers](#environment-managers)
    *   [Wrappers](#wrappers)
    *   [CI](#ci)
    *   [Tests](#tests)
    *   [State](#state)
    *   [Providers](#providers)
    *   [Platforms](#platforms)
    *   [Registry](#registry)
    *   [Helpers](#helpers)
*   [Learning](#learning)
*   [Media](#media)
*   [Podcasts](#podcasts)

## Official

*   [OpenTofu repository (⭐25k)](https://github.com/opentofu/opentofu) 🎉
*   [Fork announcement](https://opentofu.org/announcement)
*   [Official registry (⭐366)](https://github.com/opentofu/registry)
*   [Weekly updates (⭐25k)](https://github.com/opentofu/opentofu/blob/main/WEEKLY_UPDATES.md#weekly-updates)
*   [Office hours](https://www.youtube.com/watch?v=aEoMzUza6Ok\&list=PLnVotLM2QsyhCc1_8PA7fbVF-ixt4_XAY)
*   [Technical Steering Committee updates (⭐25k)](https://github.com/opentofu/opentofu/blob/main/TSC_SUMMARY.md#technical-steering-committee-tsc-summary)

## Community

*Communication channels, meetups, newsletters, and forums.*

*   [OpenTofu GitHub Discussion](https://github.com/orgs/opentofu/discussions)
*   [OpenTofu LinkedIn](https://www.linkedin.com/company/opentofuorg/)
*   [OpenTofu Slack](https://opentofu.org/slack)
*   [OpenTofu Twitter](https://twitter.com/opentofuorg)

## Features

<!--lint disable double-link-->

*   [1.9 - Provider iteration with for\_each](https://opentofu.org/docs/intro/whats-new/#provider-iteration-for_each)
*   [1.9 - The -exclude flag](https://opentofu.org/docs/intro/whats-new/#the--exclude-flag)
*   [1.8 - Override files for OpenTofu (.tofu)](https://opentofu.org/docs/intro/whats-new/#override-files-for-opentofu-keeping-compatibility)
*   [1.8 - Early variable and locals evaluation](https://opentofu.org/docs/intro/whats-new/#early-variablelocals-evaluation)
*   [1.7 - End-to-end encryption for state files](https://opentofu.org/docs/v1.7/intro/whats-new/#state-encryption)
*   [1.7 - Provider-defined functions](https://opentofu.org/docs/v1.7/intro/whats-new/#provider-defined-functions)
*   [1.7 - Removed block](https://opentofu.org/docs/v1.7/intro/whats-new/#removed-block)
*   [1.7 - Loopable import blocks](https://opentofu.org/docs/v1.7/intro/whats-new/#loopable-import-blocks)
*   [OCI-compliant registry support](https://twitter.com/OpenTofuOrg/status/1696913055576387599) 🚧
*   [CanI.TF - Feature parity between Terraform and OpenTofu](https://cani.tf/)

<!--lint enable double-link-->

## Tools

### Environment managers

*   [arkade (⭐4.4k)](https://github.com/alexellis/arkade) - CLI and Kubernetes app installer.
*   [asdf-opentofu (⭐28)](https://github.com/virtualroot/asdf-opentofu) - OpenTofu plugin for asdf version manager.
*   [tenv (⭐1k)](https://github.com/tofuutils/tenv) - Terraform and OpenTofu version manager written in Go.
*   [tfswitcher (⭐4)](https://github.com/ASleepyCat/tfswitcher) - Terraform and OpenTofu version switcher written in Rust.
*   [tofuenv (⭐181)](https://github.com/tofuutils/tofuenv) - OpenTofu version manager inspired by tfenv.

### Wrappers

*Simplify your OpenTofu workflows with a thin wrapper.*

*   [Atmos (⭐953)](https://github.com/cloudposse/atmos) - Orchestration tool that keeps environment configuration DRY.
*   [Terragrunt (⭐8.6k)](https://github.com/gruntwork-io/terragrunt) - Keep your configurations DRY, work with multiple modules, and manage remote state.
*   [Terramate (⭐3.4k)](https://github.com/terramate-io/terramate) - Automation, orchestration, and code generation for OpenTofu, Terraform, Kubernetes, and others.
*   [easy\_infra (⭐72)](https://github.com/SeisoLLC/easy_infra) - Docker container to simplify and secure the use of infrastructure as code.
*   [pug (⭐534)](https://github.com/leg100/pug) - A terminal user interface for power users.
*   [tf (⭐78)](https://github.com/dex4er/tf) - Less verbose and more friendly command outputs.
*   [tfam (⭐23)](https://github.com/Ant0wan/tfam) - Rust-powered wrapper for concurrent Terraform/OpenTofu apply, enabling multi-deployment support.
*   [tfexe (⭐3)](https://github.com/Ant0wan/tfexe) - Rust-powered wrapper for seamless execution of tfswitch and Terraform/OpenTofu with version control.
*   [tfwrapper (⭐142)](https://github.com/claranet/tfwrapper) - Python wrapper that simplifies OpenTofu usage and enforces best practices.

### CI

*   [Atlantis](https://www.runatlantis.io/) - Automating workflows via pull requests.
*   [TF-via-PR (⭐196)](https://github.com/OP5dev/TF-via-PR) - GitHub Action to init, plan and apply Terraform/OpenTofu via PR automation.
*   [pre-commit-opentofu (⭐56)](https://github.com/tofuutils/pre-commit-opentofu) - Git pre-commit hooks plugin.
*   [setup-opentofu (⭐101)](https://github.com/opentofu/setup-opentofu) - Set up OpenTofu CLI in your GitHub Actions workflow.
*   [terraform-github-actions (⭐836)](https://github.com/dflook/terraform-github-actions) - GitHub Actions for OpenTofu.
*   [tofu-controller (⭐1.4k)](https://github.com/flux-iac/tofu-controller) - GitOps OpenTofu and Terraform controller for Flux.

### Tests

*   [Terratest (⭐7.6k)](https://github.com/gruntwork-io/terratest) - Go library that makes writing automated tests for your infrastructure code easier.

### State

*Analyze and manipulate OpenTofu's state.*

*   [tfmigrate (⭐1.2k)](https://github.com/minamijoyo/tfmigrate) - State migration tool.

### Providers

*Inspect and interact with OpenTofu providers.*

*   [tfschema (⭐299)](https://github.com/minamijoyo/tfschema) - Schema inspector for providers.

### Platforms

*Alternatives to Terraform Cloud.*

*   [digger (⭐4.5k)](https://github.com/diggerhq/digger) - Open-source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline.
*   [terrakube (⭐626)](https://github.com/AzBuilder/terrakube) - Open-source platform with a private registry, remote state, custom flows, scheduled workspaces, and visual states.
*   [tofutf (⭐77)](https://github.com/tofutf/tofutf) - Open-source alternative to Terraform Enterprise with SSO, team management, agents, etc.
*   [Terrateam](https://terrateam.io) - Open-source alternative to Terraform Cloud/Enterprise, GitOps-first with native GitHub integration and designed for scale, security, and reliability.

### Registry

*   [library.tf](https://library.tf/) - An indexer of registries for providers and modules with insights and documentation.
*   [boring-registry (⭐202)](https://github.com/boring-registry/boring-registry) - Boring-registry is an open-source module and provider registry compatible with OpenTofu.
*   [hermitcrab (⭐29)](https://github.com/seal-io/hermitcrab) - Registry network mirroring service compatible with OpenTofu.
*   [terrac (⭐31)](https://github.com/haoliangyu/terrac) - Minimal private module registry compatible with OpenTofu.
*   [GitLab Module Registry](https://docs.gitlab.com/ee/user/packages/terraform_module_registry/) - Use GitLab projects as a private registry for terraform modules.
*   [terralist (⭐385)](https://github.com/terralist/terralist) - Private registry for providers and modules.
*   [citizen (⭐639)](https://github.com/outsideris/citizen) - Private registry for modules and providers with support for multiple databases and storages.
*   [petra (⭐44)](https://github.com/devoteamgcloud/petra) - Private registry manager using Google Cloud Storage.
*   [tapir (⭐218)](https://github.com/PacoVK/tapir) - Private registry for modules and providers with a UI.
*   [terraform-registry (⭐105)](https://github.com/nrkno/terraform-registry) - Modules registry with authentication and support for multiple backends.
*   [terrareg (⭐295)](https://github.com/MatthewJohn/terrareg) - Open-source modules registry with UI, optional Git integration and deep analysis.
*   [terustry (⭐66)](https://github.com/veepee-oss/terustry) - Proxy registry for providers.

### Helpers

*   [terratag (⭐974)](https://github.com/env0/terratag) - CLI tool allowing for tags or labels to be applied across an entire set of OpenTofu/Terraform files.

## Learning

*   [OpenTofu Course](https://killercoda.com/quincycheng/course/course_opentofu) - Interactive tutorials.
*   [Terraform in Depth](https://www.manning.com/books/terraform-in-depth) - Book with OpenTofu sections.
*   [Infrastructure automation with OpenTofu](https://www.udemy.com/course/infrastructure-automation-with-opentofu-hands-on-devops/?couponCode=1D97F4D8FFE62E296BE1) - Learn infrastructure provisioning with lectures, quizzes, hands-on demos and coding exercises.
*   [Migrating From Terraform To OpenTofu](https://www.youtube.com/watch?v=v9rJgtHzxUk) - Introduction to OpenTofu history and how to migrate.

## Media

*   [OSS EU 2023 - Announcement](https://www.youtube.com/watch?v=Ha77rpusEDM\&t=1190s)
*   [OSS EU 2023 - Project Overview](https://www.youtube.com/watch?v=-8sOE9-icmY\&t=15116s)
*   [Code To Cloud - Getting Started With OpenTofu](https://www.youtube.com/watch?v=HeUz6TMg82U)
*   [CNCF - OpenTofu Day Europe 2024](https://www.youtube.com/playlist?list=PLnVotLM2Qsyiw_6Pd_9WxRRLdrUAs3c1c)
*   [CNCF - OpenTofu Day North America 2024](https://www.youtube.com/playlist?list=PLnVotLM2QsyhhCO5TgEUsAip601j3NUlm)

## Podcasts

<!-- DESC, from most recent to oldest. -->

*   [SE Radio: Christian Mesh on OpenTofu](https://se-radio.net/2025/01/se-radio-652-christian-mesh-on-opentofu/)
*   [Kubernetes Podcast - OpenTofu, with Ohad Maislish](https://kubernetespodcast.com/episode/232-opentofu/)
*   [TheIaCPodcast - Expert Panel on OpenTofu GA Release, Licensing, and OSS Future](https://www.theiacpodcast.com/episode/expert-panel-on-opentofu-ga-release-licensing-and-oss-future)
*   [Contributor - Community-Driven IaC](https://www.contributor.fyi/opentofu)
*   [Ned in the Cloud - IaC Live Stream](https://www.youtube.com/watch?v=p0vDydkUWB4)
*   [Arrested DevOps - What's Up With Open Terraform?](https://www.arresteddevops.com/open-tofu/)
*   [OpenObservability - Terraform is no longer open source. Is OpenTF the successor?](https://www.youtube.com/watch?v=5QdUs9VKq5g)
*   [TheCloudGambit - The Future of OpenTF](https://www.thecloudgambit.com/2236725/13576531-the-future-of-opentf-with-ohad-maislish)
*   [Oxide and Friends - Fork in the road for Terraform?](https://www.youtube.com/watch?v=QaU94LY891M)
*   [Changelog -  OpenTF for an open Terraform](https://changelog.com/podcast/556)

