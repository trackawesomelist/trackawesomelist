# Awesome Opentofu Overview

A curated list of OpenTofu tools, resources, and related projects.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/virtualroot/awesome-opentofu/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 virtualroot/awesome-opentofu](https://github.com/virtualroot/awesome-opentofu) · ⭐ 61 · 🏷️ DevOps

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

*   [OpenTofu repository (⭐21k)](https://github.com/opentofu/opentofu) 🎉
*   [Fork announcement](https://opentofu.org/announcement)
*   [Official registry (⭐196)](https://github.com/opentofu/registry)
*   [Weekly updates (⭐21k)](https://github.com/opentofu/opentofu/blob/main/WEEKLY_UPDATES.md#weekly-updates)
*   [Office hours](https://www.youtube.com/watch?v=aEoMzUza6Ok\&list=PLnVotLM2QsyhCc1_8PA7fbVF-ixt4_XAY)
*   [Technical Steering Committee updates (⭐21k)](https://github.com/opentofu/opentofu/blob/main/TSC_SUMMARY.md#technical-steering-committee-tsc-summary)

## Community

*Communication channels, meetups, newsletters, and forums.*

*   [OpenTofu GitHub Discussion](https://github.com/orgs/opentofu/discussions)
*   [OpenTofu LinkedIn](https://www.linkedin.com/company/opentofuorg/)
*   [OpenTofu Slack](https://opentofu.org/slack)
*   [OpenTofu Twitter](https://twitter.com/opentofuorg)

## Features

*   [End-to-end encryption for state files](https://opentofu.org/docs/intro/whats-new/#state-encryption)
*   [OCI-compliant registry support](https://twitter.com/OpenTofuOrg/status/1696913055576387599) 🚧
*   [Provider-defined functions](https://opentofu.org/docs/intro/whats-new/#provider-defined-functions)
*   [Removed block](https://opentofu.org/docs/intro/whats-new/#removed-block)
*   [Loopable import blocks](https://opentofu.org/docs/intro/whats-new/#loopable-import-blocks)

## Tools

### Environment managers

*   [arkade (⭐4.1k)](https://github.com/alexellis/arkade) - CLI and Kubernetes app installer.
*   [asdf-opentofu (⭐19)](https://github.com/virtualroot/asdf-opentofu) - OpenTofu plugin for asdf version manager.
*   [tenv (⭐323)](https://github.com/tofuutils/tenv) - Terraform and OpenTofu version manager written in Go.
*   [tfswitcher (⭐5)](https://github.com/ASleepyCat/tfswitcher) - Terraform and OpenTofu version switcher written in Rust.
*   [tofuenv (⭐142)](https://github.com/tofuutils/tofuenv) - OpenTofu version manager inspired by tfenv.

### Wrappers

*Simplify your OpenTofu workflows with a thin wrapper.*

*   [Atmos (⭐595)](https://github.com/cloudposse/atmos) - Orchestration tool that keeps environment configuration DRY.
*   [Terragrunt (⭐7.7k)](https://github.com/gruntwork-io/terragrunt) - Keep your configurations DRY, work with multiple modules, and manage remote state.
*   [Terramate (⭐3.1k)](https://github.com/terramate-io/terramate) - Automation, orchestration, and code generation for OpenTofu, Terraform, Kubernetes, and others.
*   [easy\_infra (⭐65)](https://github.com/SeisoLLC/easy_infra) - Docker container to simplify and secure the use of infrastructure as code.
*   [tf (⭐61)](https://github.com/dex4er/tf) - Less verbose and more friendly command outputs.
*   [tfam (⭐21)](https://github.com/Ant0wan/tfam) - Rust-powered wrapper for concurrent Terraform/OpenTofu apply, enabling multi-deployment support.
*   [tfexe (⭐2)](https://github.com/Ant0wan/tfexe) - Rust-powered wrapper for seamless execution of tfswitch and Terraform/OpenTofu with version control.
*   [tfwrapper (⭐128)](https://github.com/claranet/tfwrapper) - Python wrapper that simplifies OpenTofu usage and enforces best practices.

### CI

*   [pre-commit-opentofu (⭐28)](https://github.com/tofuutils/pre-commit-opentofu) - Git pre-commit hooks plugin.
*   [setup-opentofu (⭐69)](https://github.com/opentofu/setup-opentofu) - Set up OpenTofu CLI in your GitHub Actions workflow.
*   [terraform-github-actions (⭐694)](https://github.com/dflook/terraform-github-actions) - GitHub Actions for OpenTofu.
*   [TF-via-PR (⭐43)](https://github.com/DevSecTop/TF-via-PR) - GitHub Action to automate OpenTofu or Terraform CLI commands via pull request interaction.
*   [tofu-controller (⭐1.2k)](https://github.com/flux-iac/tofu-controller) - GitOps OpenTofu and Terraform controller for Flux.

### Tests

*   [Terratest (⭐7.4k)](https://github.com/gruntwork-io/terratest) - Go library that makes it easier to write automated tests for your infrastructure code.

### State

*Analyze and manipulate OpenTofu's state.*

*   [tfmigrate (⭐1.1k)](https://github.com/minamijoyo/tfmigrate) - State migration tool.

### Providers

*Inspect and interact with OpenTofu providers.*

*   [tfschema (⭐292)](https://github.com/minamijoyo/tfschema) - Schema inspector for providers.

### Platforms

*Alternatives to Terraform Cloud.*

*   [digger (⭐2.7k)](https://github.com/diggerhq/digger) - Open-source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline.
*   [terrakube (⭐430)](https://github.com/AzBuilder/terrakube) - Open-source platform with private registry, remote state, custom flows, scheduled workspaces, and visual states.
*   [tofutf (⭐35)](https://github.com/tofutf/tofutf) - Open-source alternative to Terraform Enterprise with SSO, team management, agents, etc.
*   [walrus (⭐400)](https://github.com/seal-io/walrus) - Walrus is an open-source application management platform based on IaC tools, including OpenTofu, Terraform, and others.

### Registry

*   [boring-registry (⭐153)](https://github.com/boring-registry/boring-registry) - Boring-registry is an open-source module and provider registry compatible with OpenTofu.
*   [hermitcrab (⭐21)](https://github.com/seal-io/hermitcrab) - Registry network mirroring service compatible with OpenTofu.
*   [terrac (⭐27)](https://github.com/haoliangyu/terrac) - Minimal private module registry compatible with OpenTofu.
*   [GitLab Module Registry](https://docs.gitlab.com/ee/user/packages/terraform_module_registry/) - Use GitLab projects as a private registry for terraform modules.
*   [terralist (⭐285)](https://github.com/terralist/terralist) - Private registry for providers and modules.
*   [citizen (⭐609)](https://github.com/outsideris/citizen) - Private registry for modules and providers with support for multiple databases and storages.
*   [petra (⭐39)](https://github.com/devoteamgcloud/petra) - Private registry manager using Google Cloud Storage.
*   [tapir (⭐153)](https://github.com/PacoVK/tapir) - Private registry for modules and providers with a UI.
*   [terraform-registry (⭐78)](https://github.com/nrkno/terraform-registry) - Modules registry with authentication and support for multiple backends.
*   [terrareg (⭐240)](https://github.com/MatthewJohn/terrareg) - Open-source modules registry with UI, optional Git integration and deep analysis.
*   [terustry (⭐56)](https://github.com/veepee-oss/terustry) - Proxy registry for providers.

### Helpers

*   [terratag (⭐899)](https://github.com/env0/terratag) - CLI tool allowing for tags or labels to be applied across an entire set of OpenTofu/Terraform files.

## Learning

*   [OpenTofu Course](https://killercoda.com/quincycheng/course/course_opentofu) - Interactive tutorials.
*   [Terraform in Depth](https://www.manning.com/books/terraform-in-depth) - Book with OpenTofu sections.
*   [Infrastructure automation with OpenTofu](https://www.udemy.com/course/infrastructure-automation-with-opentofu-hands-on-devops/?couponCode=1D97F4D8FFE62E296BE1) - Learn infrastructure provisioning with lectures, quizzes, hands-on demos and coding exercises.

## Media

*   [OSS EU 2023 - Announcement](https://www.youtube.com/watch?v=Ha77rpusEDM\&t=1190s)
*   [OSS EU 2023 - Project Overview](https://www.youtube.com/watch?v=-8sOE9-icmY\&t=15116s)
*   [Code To Cloud - Getting Started With OpenTofu](https://www.youtube.com/watch?v=HeUz6TMg82U)
*   [CNCF - OpenTofu Day 2024](https://www.youtube.com/playlist?list=PLnVotLM2Qsyiw_6Pd_9WxRRLdrUAs3c1c)

## Podcasts

<!-- DESC, from most recent to oldest. -->

*   [TheIaCPodcast - Expert Panel on OpenTofu GA Release, Licensing, and OSS Future](https://www.theiacpodcast.com/episode/expert-panel-on-opentofu-ga-release-licensing-and-oss-future)
*   [Contributor - Community-Driven IaC](https://www.contributor.fyi/opentofu)
*   [Ned in the Cloud - IaC Live Stream](https://www.youtube.com/watch?v=p0vDydkUWB4)
*   [Arrested DevOps - What's Up With Open Terraform?](https://www.arresteddevops.com/open-tofu/)
*   [OpenObservability - Terraform is no longer open source. Is OpenTF the successor?](https://www.youtube.com/watch?v=5QdUs9VKq5g)
*   [TheCloudGambit - The Future of OpenTF](https://www.thecloudgambit.com/2236725/13576531-the-future-of-opentf-with-ohad-maislish)
*   [Oxide and Friends - Fork in the road for Terraform?](https://www.youtube.com/watch?v=QaU94LY891M)
*   [Changelog -  OpenTF for an open Terraform](https://changelog.com/podcast/556)

