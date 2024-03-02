# Awesome Opentofu Overview

A curated list of OpenTofu tools, resources, and related projects.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/virtualroot/awesome-opentofu/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 virtualroot/awesome-opentofu](https://github.com/virtualroot/awesome-opentofu) · ⭐ 31 · 🏷️ DevOps

[ [Daily](/content/virtualroot/awesome-opentofu/README.md) / [Weekly](/content/virtualroot/awesome-opentofu/week/README.md) / Overview ]

---

# Awesome OpenTofu [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->

> A curated and collaborative list of awesome OpenTofu resources and tools.

[OpenTofu](https://opentofu.org/) lets you declaratively manage your infrastructure. It's an open-source and community-driven alternative to Terraform.

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

*   [OpenTofu repository (⭐19k)](https://github.com/opentofu/opentofu) 🎉
*   [Fork announcement](https://opentofu.org/announcement)
*   [Official registry (⭐112)](https://github.com/opentofu/registry)
*   [Weekly Updates (⭐19k)](https://github.com/opentofu/opentofu/blob/main/WEEKLY_UPDATES.md#weekly-updates)
*   [Office Hours](https://www.youtube.com/watch?v=aEoMzUza6Ok\&list=PLnVotLM2QsyhCc1_8PA7fbVF-ixt4_XAY)
*   [Technical Steering Committee Updates (⭐19k)](https://github.com/opentofu/opentofu/blob/main/TSC_SUMMARY.md#technical-steering-committee-tsc-summary)

## Community

*Communication channels, meetups, newsletters and forums.*

*   [OpenTofu GitHub Discussion](https://github.com/orgs/opentofu/discussions)
*   [OpenTofu LinkedIn](https://www.linkedin.com/company/opentofuorg/)
*   [OpenTofu Reddit](https://www.reddit.com/r/opentf/)
*   [OpenTofu Slack](https://opentofu.org/slack)
*   [OpenTofu Twitter](https://twitter.com/opentofuorg)

## Features

*   [End-to-end encryption for state files](https://youtu.be/rR4IbhlRSkI) 🚧
*   [OCI-compliant registry support](https://twitter.com/OpenTofuOrg/status/1696913055576387599) 🚧
*   [Provider-defined functions](https://www.youtube.com/shorts/4aHZjDz2VWg) 🚧

## Tools

### Environment managers

*   [asdf-opentofu (⭐14)](https://github.com/virtualroot/asdf-opentofu) - OpenTofu plugin for asdf version manager.
*   [tenv (⭐120)](https://github.com/tofuutils/tenv) - Terraform and OpenTofu version manager written in Go.
*   [tfswitcher (⭐2)](https://github.com/ASleepyCat/tfswitcher) - Terraform and OpenTofu version switcher written in Rust.
*   [tofuenv (⭐111)](https://github.com/tofuutils/tofuenv) - OpenTofu version manager inspired by tfenv.

### Wrappers

*Simplify your OpenTofu workflows with a thin wrapper.*

*   [Atmos (⭐499)](https://github.com/cloudposse/atmos) - Orchestration tool that keeps environment configuration DRY.
*   [Terragrunt (⭐7.5k)](https://github.com/gruntwork-io/terragrunt) - Keep your configurations DRY, work with multiple modules, and manage remote state.
*   [Terramate (⭐2.9k)](https://github.com/terramate-io/terramate) - Automation, orchestration and code generation for OpenTofu, Terraform, Kubernetes, and others.
*   [easy\_infra (⭐65)](https://github.com/SeisoLLC/easy_infra) - Docker container to simplify and secure the use of infrastructure as code.
*   [tf (⭐59)](https://github.com/dex4er/tf) - Less verbose and more friendly command outputs.
*   [tfam (⭐20)](https://github.com/Ant0wan/tfam) - Rust-powered wrapper for concurrent Terraform/OpenTofu apply, enabling multi-deployment support.
*   [tfexe (⭐2)](https://github.com/Ant0wan/tfexe) - Rust-powered wrapper for seamless execution of tfswitch and Terraform/OpenTofu with version control.
*   [tfwrapper (⭐123)](https://github.com/claranet/tfwrapper) - Python wrapper that aims to simplify OpenTofu usage and enforce best practices.

### CI

*   [pre-commit-opentofu (⭐17)](https://github.com/tofuutils/pre-commit-opentofu) - Git pre-commit hooks plugin.
*   [setup-opentofu (⭐54)](https://github.com/opentofu/setup-opentofu) - Set up OpenTofu CLI in your GitHub Actions workflow.
*   [terraform-github-actions (⭐647)](https://github.com/dflook/terraform-github-actions) - GitHub Actions for OpenTofu.
*   [tf-via-pr-comments (⭐35)](https://github.com/devsectop/tf-via-pr-comments) - GitHub Action to run Terraform or OpenTofu CLI commands via PR comments.

### Tests

*   [Terratest (⭐7.3k)](https://github.com/gruntwork-io/terratest) - Go library that makes it easier to write automated tests for your infrastructure code.

### State

*Analize and manipulate OpenTofu's state.*

*   [tfmigrate (⭐1k)](https://github.com/minamijoyo/tfmigrate) - State migration tool.

### Providers

*Inspect and interact with OpenTofu providers.*

*   [tfschema (⭐287)](https://github.com/minamijoyo/tfschema) - Schema inspector for providers.

### Platforms

*Alternatives to Terraform Cloud.*

*   [digger (⭐2.6k)](https://github.com/diggerhq/digger) - Open-source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline.
*   [terrakube (⭐372)](https://github.com/AzBuilder/terrakube) - Open-source platform with private registry, remote state, custom flows, scheduled workspaces, and visual states.
*   [walrus (⭐333)](https://github.com/seal-io/walrus) - Walrus is an open-source application management platform based on IaC tools including OpenTofu, Terraform and others.

### Registry

*   [boring-registry (⭐141)](https://github.com/boring-registry/boring-registry) - Boring-registry is an open-source module and provider registry compatible with OpenTofu.
*   [hermitcrab (⭐12)](https://github.com/seal-io/hermitcrab) - Registry network mirroring service compatible with OpenTofu.
*   [terrac (⭐24)](https://github.com/haoliangyu/terrac) - Minimal private module registry compatible with OpenTofu.
*   [GitLab Module Registry](https://docs.gitlab.com/ee/user/packages/terraform_module_registry/) - Use GitLab projects as a private registry for terraform modules.
*   [terralist (⭐265)](https://github.com/terralist/terralist) - Private registry for providers and modules.
*   [citizen (⭐597)](https://github.com/outsideris/citizen) - Private registry for modules and providers with support for multiple databases and storages.
*   [petra (⭐34)](https://github.com/devoteamgcloud/petra) - Private registry manager using Google Cloud Storage.
*   [tapir (⭐133)](https://github.com/PacoVK/tapir) - Private registry for modules and providers with an UI.
*   [terraform-registry (⭐72)](https://github.com/nrkno/terraform-registry) - Modules registry with authentication and support for multiple backends.
*   [terrareg (⭐218)](https://github.com/MatthewJohn/terrareg) - Open-source modules registry with UI, optional Git integration and deep analysis.
*   [terustry (⭐55)](https://github.com/veepee-oss/terustry) - Proxy registry for providers.

### Helpers

*   [terratag (⭐866)](https://github.com/env0/terratag) - CLI tool allowing for tags or labels to be applied across an entire set of OpenTofu/Terraform files.

## Learning

*   [OpenTofu Course](https://killercoda.com/quincycheng/course/course_opentofu) - Interactive tutorials.
*   [Terraform in Depth](https://www.manning.com/books/terraform-in-depth) - Book with OpenTofu sections.

## Media

*   [OSS EU 2023 - Announcement](https://www.youtube.com/watch?v=Ha77rpusEDM\&t=1190s)
*   [OSS EU 2023 - Project overview](https://www.youtube.com/watch?v=-8sOE9-icmY\&t=15116s)
*   [Code To Cloud - Getting Started With OpenTofu](https://www.youtube.com/watch?v=HeUz6TMg82U)

## Podcasts

<!-- DESC, from most recent to oldest. -->

*   [TheIaCPodcast - Expert Panel on OpenTofu GA Release, Licensing, and OSS Future](https://www.theiacpodcast.com/episode/expert-panel-on-opentofu-ga-release-licensing-and-oss-future)
*   [Contributor - Community Driven IaC](https://www.contributor.fyi/opentofu)
*   [Ned in the Cloud - IaC Live Stream](https://www.youtube.com/watch?v=p0vDydkUWB4)
*   [Arrested DevOps - What's Up With Open Terraform?](https://www.arresteddevops.com/open-tofu/)
*   [OpenObservability - Terraform is no longer open source. Is OpenTF the successor?](https://www.youtube.com/watch?v=5QdUs9VKq5g)
*   [TheCloudGambit - The Future of OpenTF](https://www.thecloudgambit.com/2236725/13576531-the-future-of-opentf-with-ohad-maislish)
*   [Oxide and Friends - Fork in the road for Terraform?](https://www.youtube.com/watch?v=QaU94LY891M)
*   [Changelog -  OpenTF for an open Terraform](https://changelog.com/podcast/556)

