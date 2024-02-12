# Asdf Plugins Overview

Convenience shortname repository for asdf community plugins

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/asdf-vm/asdf-plugins/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 asdf-vm/asdf-plugins](https://github.com/asdf-vm/asdf-plugins) · ⭐ 1K · 🏷️ Computer Science

[ [Daily](/content/asdf-vm/asdf-plugins/README.md) / [Weekly](/content/asdf-vm/asdf-plugins/week/README.md) / Overview ]

---

# asdf plugins repository

The purpose of the [asdf (⭐19k)](https://github.com/asdf-vm/asdf) plugins repository is to enable shorthand installation of plugins with:

```shell
asdf plugin add <name>
```

The asdf core team recommend using the long-form which does not rely on this repository:

```shell
asdf plugin add <name> <git_url>
```

Read each plugins code before installation and usage.

## Existing Plugins

Plugins listed here should be *stable* and actively *maintained*. If you have issues with a specific plugin please raise them on the plugin repository first. If a deprecated plugin is listed here, please let us know and create a PR to add the most used alternative.

## Creating a new Plugin

*   Read the [creating plugins guide (⭐19k)](https://github.com/asdf-vm/asdf/blob/master/docs/plugins/create.md)
*   Consider using our [Template (⭐93)](https://github.com/asdf-vm/asdf-plugin-template) which has the core functionality to tools published to GitHub releases and CI for GitHub/GitLab/CircleCI out of the box.

### `asdf-community`

If you're creating a new plugin consider creating it as part of the [`asdf-community`](https://github.com/asdf-community/.github) project. This is a separate community project with consolidated maintenance.

## Contributing a new Plugin

*   Install repo dependencies: `asdf install`
*   Add the plugin to the repository `README.md` *Plugin List* table.
*   Create a file with the shortname you wish to be used by asdf in `plugins/<name>`. The contents should be `repository = <your_repo>`.
    *   eg: `printf "repository = https://github.com/asdf-vm/asdf-nodejs.git\n" > plugins/nodejs`
*   Test your code : `scripts/test_plugin.bash --file plugins/<name>`
*   Format your code & this README: `scripts/format.bash`
*   Create a PR following the instructions in the PR template.

## Security

The `asdf` core provides a [security policy (⭐19k)](https://github.com/asdf-vm/asdf/security/policy) which covers the core `asdf` tool. Plugins are the responsibility of their creators and not covered by the `asdf` policy. It is the responsibility of the user to evaluate each plugin they use for security concerns, even those in the `asdf-community` repositories. You can pin a plugin to a commit of the source repo with `asdf plugin update <name> <git-ref>`, however running `asdf plugin update <name>` or `asdf plugin update --all` will change the `sha` you have previously set.

## Plugin List

| Tool / Language               | Plugin Repository                                                                                                      |
| :---------------------------- | :--------------------------------------------------------------------------------------------------------------------- |
| .Net                          | [hensou/asdf-dotnet (⭐26)](https://github.com/hensou/asdf-dotnet)                                                      |
| .Net Core                     | [emersonsoares/asdf-dotnet-core (⭐93)](https://github.com/emersonsoares/asdf-dotnet-core)                              |
| 1password-cli                 | [NeoHsu/asdf-1password-cli (⭐7)](https://github.com/NeoHsu/asdf-1password-cli)                                         |
| act                           | [grimoh/asdf-act (⭐6)](https://github.com/grimoh/asdf-act)                                                             |
| action-validator              | [mpalmer/action-validator (⭐219)](https://github.com/mpalmer/action-validator)                                         |
| actionlint                    | [crazy-matt/asdf-actionlint (⭐2)](https://github.com/crazy-matt/asdf-actionlint)                                       |
| adr-tools                     | [td7x/asdf/adr-tools](https://gitlab.com/td7x/asdf/adr-tools)                                                          |
| ag (the\_silver\_searcher)    | [koketani/asdf-ag (⭐0)](https://github.com/koketani/asdf-ag)                                                           |
| age                           | [threkk/asdf-age (⭐1)](https://github.com/threkk/asdf-age)                                                             |
| age-plugin-yubikey            | [str4d/asdf-age-plugin-yubikey](https://github.com/str4d/asdf-age-plugin-yubikey)                                      |
| agebox                        | [slok/asdf-agebox (⭐0)](https://github.com/slok/asdf-agebox)                                                           |
| air                           | [pdemagny/asdf-air (⭐1)](https://github.com/pdemagny/asdf-air)                                                         |
| aks-engine                    | [robsonpeixoto/asdf-aks-engine (⭐0)](https://github.com/robsonpeixoto/asdf-aks-engine)                                 |
| alias                         | [andrewthauer/asdf-alias (⭐23)](https://github.com/andrewthauer/asdf-alias)                                            |
| allure                        | [comdotlinux/asdf-allure (⭐0)](https://github.com/comdotlinux/asdf-allure)                                             |
| alp                           | [asdf-community/asdf-alp (⭐5)](https://github.com/asdf-community/asdf-alp)                                             |
| amass                         | [dhoeric/asdf-amass (⭐0)](https://github.com/dhoeric/asdf-amass)                                                       |
| Amazon ECR Credential Helper  | [dex4er/asdf-amazon-ecr-credential-helper (⭐0)](https://github.com/dex4er/asdf-amazon-ecr-credential-helper)           |
| Ambient                       | [jtakakura/asdf-ambient (⭐2)](https://github.com/jtakakura/asdf-ambient)                                               |
| Ansible (ansible-base)        | [amrox/asdf-pyapp (⭐48)](https://github.com/amrox/asdf-pyapp)                                                          |
| ant                           | [jackboespflug/asdf-ant (⭐0)](https://github.com/jackboespflug/asdf-ant)                                               |
| Apache Jmeter                 | [comdotlinux/asdf-jmeter (⭐0)](https://github.com/comdotlinux/asdf-jmeter)                                             |
| apko                          | [omissis/asdf-apko (⭐0)](https://github.com/omissis/asdf-apko)                                                         |
| Apollo Router                 | [safx/asdf-apollo-router (⭐0)](https://github.com/safx/asdf-apollo-router)                                             |
| arc                           | [ORCID/asdf-arc (⭐0)](https://github.com/ORCID/asdf-arc)                                                               |
| argo                          | [sudermanjr/asdf-argo (⭐1)](https://github.com/sudermanjr/asdf-argo)                                                   |
| argo-rollouts                 | [abatilo/asdf-argo-rollouts (⭐2)](https://github.com/abatilo/asdf-argo-rollouts)                                       |
| argocd                        | [beardix/asdf-argocd (⭐5)](https://github.com/beardix/asdf-argocd)                                                     |
| aria2                         | [asdf-community/asdf-aria2 (⭐7)](https://github.com/asdf-community/asdf-aria2)                                         |
| asciidoctorj                  | [gliwka/asdf-asciidoctorj (⭐2)](https://github.com/gliwka/asdf-asciidoctorj)                                           |
| asdf-plugin-manager           | [asdf-community/asdf-plugin-manager (⭐23)](https://github.com/asdf-community/asdf-plugin-manager)                      |
| assh                          | [zekker6/asdf-assh (⭐2)](https://github.com/zekker6/asdf-assh)                                                         |
| atlas                         | [pbr0ck3r/asdf-atlas (⭐0)](https://github.com/pbr0ck3r/asdf-atlas)                                                     |
| auto-doc                      | [looztra/asdf-auto-doc (⭐0)](https://github.com/looztra/asdf-auto-doc)                                                 |
| aws-copilot                   | [NeoHsu/asdf-copilot (⭐2)](https://github.com/NeoHsu/asdf-copilot)                                                     |
| aws-amplify-cli               | [LozanoMatheus/asdf-aws-amplify-cli (⭐0)](https://github.com/LozanoMatheus/asdf-aws-amplify-cli)                       |
| AWS IAM authenticator         | [zekker6/asdf-aws-iam-authenticator (⭐0)](https://github.com/zekker6/asdf-aws-iam-authenticator)                       |
| aws-nuke                      | [bersalazar/asdf-aws-nuke (⭐1)](https://github.com/bersalazar/asdf-aws-nuke)                                           |
| aws-sam-cli                   | [amrox/asdf-pyapp (⭐48)](https://github.com/amrox/asdf-pyapp)                                                          |
| aws-sso-cli                   | [adamcrews/asdf-aws-sso-cli (⭐0)](https://github.com/adamcrews/asdf-aws-sso-cli)                                       |
| awscli                        | [MetricMike/asdf-awscli (⭐47)](https://github.com/MetricMike/asdf-awscli)                                              |
| awscli-local                  | [paulo-ferraz-oliveira/asdf-awscli-local (⭐6)](https://github.com/paulo-ferraz-oliveira/asdf-awscli-local)             |
| awsebcli                      | [amrox/asdf-pyapp (⭐48)](https://github.com/amrox/asdf-pyapp)                                                          |
| aws-vault                     | [karancode/asdf-aws-vault (⭐9)](https://github.com/karancode/asdf-aws-vault)                                           |
| awsls                         | [chessmango/asdf-awsls (⭐2)](https://github.com/chessmango/asdf-awsls)                                                 |
| awsrm                         | [chessmango/asdf-awsrm (⭐2)](https://github.com/chessmango/asdf-awsrm)                                                 |
| awsweeper                     | [chessmango/asdf-awsweeper (⭐2)](https://github.com/chessmango/asdf-awsweeper)                                         |
| azure-cli (az)                | [EcoMind/asdf-azure-cli (⭐2)](https://github.com/EcoMind/asdf-azure-cli)                                               |
| Azure Functions Core Tools    | [daveneeley/asdf-azure-functions-core-tools (⭐1)](https://github.com/daveneeley/asdf-azure-functions-core-tools)       |
| babashka                      | [pitch-io/asdf-babashka (⭐10)](https://github.com/pitch-io/asdf-babashka)                                              |
| balena-cli                    | [boatkit-io/asdf-balena-cli (⭐0)](https://github.com/boatkit-io/asdf-balena-cli)                                       |
| bashbot                       | [mathew-fleisch/asdf-bashbot (⭐0)](https://github.com/mathew-fleisch/asdf-bashbot)                                     |
| bashly                        | [pcrockett/asdf-bashly (⭐0)](https://github.com/pcrockett/asdf-bashly)                                                 |
| bat                           | [wt0f/asdf-bat](https://gitlab.com/wt0f/asdf-bat)                                                                      |
| bat-extras                    | [vhdirk/asdf-bat-extras (⭐0)](https://github.com/vhdirk/asdf-bat-extras)                                               |
| Batect                        | [johnlayton/asdf-batect (⭐0)](https://github.com/johnlayton/asdf-batect)                                               |
| Bats (Bash unittest)          | [timgluz/asdf-bats (⭐7)](https://github.com/timgluz/asdf-bats)                                                         |
| Bazel                         | [rajatvig/asdf-bazel (⭐7)](https://github.com/rajatvig/asdf-bazel)                                                     |
| bbr                           | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| bbr-s3-config-validator       | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| benthos                       | [benthosdev/benthos-asdf (⭐1)](https://github.com/benthosdev/benthos-asdf)                                             |
| bfs                           | [virtualroot/asdf-bfs (⭐0)](https://github.com/virtualroot/asdf-bfs)                                                   |
| Bin                           | [yozachar/asdf-bin (⭐0)](https://github.com/yozachar/asdf-bin)                                                         |
| binnacle                      | [Traackr/asdf-binnacle (⭐0)](https://github.com/Traackr/asdf-binnacle)                                                 |
| Bitwarden                     | [vixus0/asdf-bitwarden (⭐4)](https://github.com/vixus0/asdf-bitwarden)                                                 |
| bitwarden-secrets-manager     | [asdf-community/asdf-bitwarden-secrets-manager (⭐0)](https://github.com/asdf-community/asdf-bitwarden-secrets-manager) |
| Bombardier                    | [NeoHsu/asdf-bombardier (⭐0)](https://github.com/NeoHsu/asdf-bombardier)                                               |
| borg                          | [lwiechec/asdf-borg (⭐0)](https://github.com/lwiechec/asdf-borg)                                                       |
| bosh                          | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| bottom (btm)                  | [carbonteq/asdf-btm (⭐0)](https://github.com/carbonteq/asdf-btm)                                                       |
| Boundary                      | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| bpkg                          | [bpkg/asdf-bpkg (⭐2)](https://github.com/bpkg/asdf-bpkg)                                                               |
| Brig                          | [Ibotta/asdf-brig (⭐4)](https://github.com/Ibotta/asdf-brig)                                                           |
| BTrace                        | [joschi/asdf-btrace (⭐0)](https://github.com/joschi/asdf-btrace)                                                       |
| Buf                           | [truepay/asdf-buf (⭐9)](https://github.com/truepay/asdf-buf)                                                           |
| Buildpack                     | [johnlayton/asdf-buildpack (⭐2)](https://github.com/johnlayton/asdf-buildpack)                                         |
| Bun                           | [cometkim/asdf-bun (⭐108)](https://github.com/cometkim/asdf-bun)                                                       |
| Bundler                       | [jonathanmorley/asdf-bundler (⭐7)](https://github.com/jonathanmorley/asdf-bundler)                                     |
| Cabal                         | [sestrella/asdf-ghcup (⭐13)](https://github.com/sestrella/asdf-ghcup)                                                  |
| Caddy                         | [salasrod/asdf-caddy (⭐11)](https://github.com/salasrod/asdf-caddy)                                                    |
| Calicoctl                     | [FairwindsOps/asdf-calicoctl (⭐1)](https://github.com/FairwindsOps/asdf-calicoctl)                                     |
| Camunda Modeler               | [barmac/asdf-camunda-modeler (⭐4)](https://github.com/barmac/asdf-camunda-modeler)                                     |
| cargo-make                    | [kachick/asdf-cargo-make (⭐4)](https://github.com/kachick/asdf-cargo-make)                                             |
| Carp                          | [susurri/asdf-carp (⭐0)](https://github.com/susurri/asdf-carp)                                                         |
| carthage                      | [younke/asdf-carthage (⭐0)](https://github.com/younke/asdf-carthage)                                                   |
| ccache                        | [asdf-community/asdf-ccache (⭐6)](https://github.com/asdf-community/asdf-ccache)                                       |
| certstrap                     | [carnei-ro/asdf-certstrap (⭐0)](https://github.com/carnei-ro/asdf-certstrap)                                           |
| cidr-merger                   | [ORCID/asdf-cidr-merger (⭐0)](https://github.com/ORCID/asdf-cidr-merger)                                               |
| cidrchk                       | [ORCID/asdf-cidrchk (⭐1)](https://github.com/ORCID/asdf-cidrchk)                                                       |
| circleci-cli                  | [ucpr/asdf-circleci-cli (⭐0)](https://github.com/ucpr/asdf-circleci-cli)                                               |
| cf                            | [mattysweeps/asdf-cf (⭐5)](https://github.com/mattysweeps/asdf-cf)                                                     |
| cfssl                         | [mathew-fleisch/asdf-cfssl (⭐0)](https://github.com/mathew-fleisch/asdf-cfssl)                                         |
| chamber                       | [mintel/asdf-chamber (⭐0)](https://github.com/mintel/asdf-chamber)                                                     |
| changie                       | [pdemagny/asdf-changie (⭐0)](https://github.com/pdemagny/asdf-changie)                                                 |
| cheat                         | [jmoratilla/asdf-cheat-plugin (⭐2)](https://github.com/jmoratilla/asdf-cheat-plugin)                                   |
| checkov                       | [bosmak/asdf-checkov (⭐0)](https://github.com/bosmak/asdf-checkov)                                                     |
| chezmoi                       | [joke/asdf-chezmoi (⭐6)](https://github.com/joke/asdf-chezmoi)                                                         |
| chezscheme                    | [asdf-community/asdf-chezscheme (⭐5)](https://github.com/asdf-community/asdf-chezscheme)                               |
| CHICKEN                       | [evhan/asdf-chicken (⭐0)](https://github.com/evhan/asdf-chicken)                                                       |
| chisel                        | [lwiechec/asdf-chisel (⭐0)](https://github.com/lwiechec/asdf-chisel)                                                   |
| choose                        | [carbonteq/asdf-choose (⭐0)](https://github.com/carbonteq/asdf-choose)                                                 |
| Chromedriver                  | [schinckel/asdf-chromedriver (⭐3)](https://github.com/schinckel/asdf-chromedriver)                                     |
| cilium-cli                    | [carnei-ro/asdf-cilium-cli (⭐0)](https://github.com/carnei-ro/asdf-cilium-cli)                                         |
| cilium-hubble                 | [NitriKx/asdf-cilium-hubble (⭐0)](https://github.com/NitriKx/asdf-cilium-hubble)                                       |
| Clarinet                      | [alexgo-io/asdf-clarinet (⭐0)](https://github.com/alexgo-io/asdf-clarinet)                                             |
| clj-kondo                     | [rynkowsg/asdf-clj-kondo (⭐0)](https://github.com/rynkowsg/asdf-clj-kondo)                                             |
| Clojure                       | [asdf-community/asdf-clojure (⭐14)](https://github.com/asdf-community/asdf-clojure)                                    |
| Cloudflared                   | [threkk/asdf-cloudflared (⭐1)](https://github.com/threkk/asdf-cloudflared)                                             |
| cloud-sql-proxy               | [pbr0ck3r/asdf-cloud-sql-proxy (⭐0)](https://github.com/pbr0ck3r/asdf-cloud-sql-proxy)                                 |
| Clusterawsadm                 | [kahun/asdf-clusterawsadm (⭐2)](https://github.com/kahun/asdf-clusterawsadm)                                           |
| Clusterctl                    | [pfnet-research/asdf-clusterctl (⭐10)](https://github.com/pfnet-research/asdf-clusterctl)                              |
| cmctl                         | [asdf-community/asdf-cmctl (⭐2)](https://github.com/asdf-community/asdf-cmctl)                                         |
| CMake                         | [asdf-community/asdf-cmake (⭐3)](https://github.com/asdf-community/asdf-cmake)                                         |
| CockroachDB                   | [salasrod/asdf-cockroach (⭐2)](https://github.com/salasrod/asdf-cockroach)                                             |
| CocoaPods                     | [ronnnnn/asdf-cocoapods (⭐8)](https://github.com/ronnnnn/asdf-cocoapods)                                               |
| Codefresh                     | [gurukulkarni/asdf-codefresh (⭐1)](https://github.com/gurukulkarni/asdf-codefresh)                                     |
| CodeQL                        | [bored-engineer/asdf-codeql (⭐0)](https://github.com/bored-engineer/asdf-codeql)                                       |
| Colima                        | [CrouchingMuppet/asdf-colima (⭐0)](https://github.com/CrouchingMuppet/asdf-colima)                                     |
| Conan                         | [amrox/asdf-pyapp (⭐48)](https://github.com/amrox/asdf-pyapp)                                                          |
| Concourse                     | [mattysweeps/asdf-concourse (⭐3)](https://github.com/mattysweeps/asdf-concourse)                                       |
| Conduit                       | [gmcabrita/asdf-conduit (⭐1)](https://github.com/gmcabrita/asdf-conduit)                                               |
| Conform                       | [skyzyx/asdf-conform (⭐0)](https://github.com/skyzyx/asdf-conform)                                                     |
| conftest                      | [looztra/asdf-conftest (⭐2)](https://github.com/looztra/asdf-conftest)                                                 |
| Consul                        | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| container-diff                | [cgroschupp/asdf-container-diff (⭐0)](https://github.com/cgroschupp/asdf-container-diff)                               |
| container-structure-test      | [FeryET/asdf-container-structure-test (⭐0)](https://github.com/FeryET/asdf-container-structure-test)                   |
| cookiecutter                  | [shawon-crosen/asdf-cookiecutter (⭐2)](https://github.com/shawon-crosen/asdf-cookiecutter)                             |
| Copper                        | [vladlosev/asdf-copper (⭐0)](https://github.com/vladlosev/asdf-copper)                                                 |
| Coq                           | [gingerhot/asdf-coq (⭐5)](https://github.com/gingerhot/asdf-coq)                                                       |
| cosign                        | [wt0f/asdf-cosign](https://gitlab.com/wt0f/asdf-cosign)                                                                |
| coursier                      | [jiahuili430/asdf-coursier (⭐3)](https://github.com/jiahuili430/asdf-coursier)                                         |
| crane                         | [dmpe/asdf-crane (⭐1)](https://github.com/dmpe/asdf-crane)                                                             |
| crc                           | [sqtran/asdf-crc (⭐1)](https://github.com/sqtran/asdf-crc)                                                             |
| credhub                       | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| crictl                        | [FairwindsOps/asdf-crictl (⭐1)](https://github.com/FairwindsOps/asdf-crictl)                                           |
| crossplane-cli                | [joke/asdf-crossplane-cli (⭐0)](https://github.com/joke/asdf-crossplane-cli)                                           |
| ctlptl                        | [ezcater/asdf-ctlptl (⭐1)](https://github.com/ezcater/asdf-ctlptl)                                                     |
| Crystal                       | [asdf-community/asdf-crystal (⭐73)](https://github.com/asdf-community/asdf-crystal)                                    |
| ctop                          | [NeoHsu/asdf-ctop (⭐0)](https://github.com/NeoHsu/asdf-ctop)                                                           |
| CUE                           | [asdf-community/asdf-cue (⭐1)](https://github.com/asdf-community/asdf-cue)                                             |
| cyclonedx                     | [xeedio/asdf-cyclonedx (⭐0)](https://github.com/xeedio/asdf-cyclonedx)                                                 |
| D (DMD)                       | [sylph01/asdf-dmd (⭐6)](https://github.com/sylph01/asdf-dmd)                                                           |
| dagger                        | [virtualstaticvoid/asdf-dagger (⭐0)](https://github.com/virtualstaticvoid/asdf-dagger)                                 |
| Dart                          | [PatOConnor43/asdf-dart (⭐38)](https://github.com/PatOConnor43/asdf-dart)                                              |
| Dasel                         | [asdf-community/asdf-dasel (⭐1)](https://github.com/asdf-community/asdf-dasel)                                         |
| datree                        | [lukeab/asdf-datree (⭐0)](https://github.com/lukeab/asdf-datree)                                                       |
| Dbmate                        | [juusujanar/asdf-dbmate (⭐3)](https://github.com/juusujanar/asdf-dbmate)                                               |
| Deck                          | [nutellinoit/asdf-deck (⭐0)](https://github.com/nutellinoit/asdf-deck)                                                 |
| Delta                         | [andweeb/asdf-delta (⭐3)](https://github.com/andweeb/asdf-delta)                                                       |
| Deno                          | [asdf-community/asdf-deno (⭐118)](https://github.com/asdf-community/asdf-deno)                                         |
| Dep                           | [paxosglobal/asdf-dep (⭐4)](https://github.com/paxosglobal/asdf-dep)                                                   |
| depot                         | [depot/asdf-depot (⭐0)](https://github.com/depot/asdf-depot)                                                           |
| Desk                          | [endorama/asdf-desk (⭐3)](https://github.com/endorama/asdf-desk)                                                       |
| DevSpace                      | [NeoHsu/asdf-devspace (⭐0)](https://github.com/NeoHsu/asdf-devspace)                                                   |
| DevStream                     | [zhenyuanlau/asdf-dtm (⭐1)](https://github.com/zhenyuanlau/asdf-dtm)                                                   |
| dhall                         | [aaaaninja/asdf-dhall (⭐3)](https://github.com/aaaaninja/asdf-dhall)                                                   |
| difftastic                    | [volf52/asdf-difftastic (⭐2)](https://github.com/volf52/asdf-difftastic)                                               |
| digdag                        | [jtakakura/asdf-digdag (⭐0)](https://github.com/jtakakura/asdf-digdag)                                                 |
| direnv                        | [asdf-community/asdf-direnv (⭐493)](https://github.com/asdf-community/asdf-direnv)                                     |
| dive                          | [looztra/asdf-dive (⭐4)](https://github.com/looztra/asdf-dive)                                                         |
| djinni                        | [cross-language-cpp/asdf-djinni (⭐2)](https://github.com/cross-language-cpp/asdf-djinni)                               |
| docker-slim                   | [xataz/asdf-docker-slim (⭐0)](https://github.com/xataz/asdf-docker-slim)                                               |
| docker-compose-v1             | [yilas/asdf-docker-compose-v1 (⭐2)](https://github.com/yilas/asdf-docker-compose-v1)                                   |
| dockle                        | [mathew-fleisch/asdf-dockle (⭐0)](https://github.com/mathew-fleisch/asdf-dockle)                                       |
| doctl                         | [maristgeek/asdf-doctl (⭐2)](https://github.com/maristgeek/asdf-doctl)                                                 |
| docToolchain                  | [joschi/asdf-doctoolchain (⭐1)](https://github.com/joschi/asdf-doctoolchain)                                           |
| docuum                        | [bradym/asdf-docuum (⭐0)](https://github.com/bradym/asdf-docuum)                                                       |
| DOME                          | [jtakakura/asdf-dome (⭐0)](https://github.com/jtakakura/asdf-dome)                                                     |
| doppler                       | [takutakahashi/asdf-doppler (⭐0)](https://github.com/takutakahashi/asdf-doppler)                                       |
| dotenv-linter                 | [wesleimp/asdf-dotenv-linter (⭐3)](https://github.com/wesleimp/asdf-dotenv-linter)                                     |
| Dotty                         | [asdf-community/asdf-dotty (⭐6)](https://github.com/asdf-community/asdf-dotty)                                         |
| dprint                        | [asdf-community/asdf-dprint (⭐1)](https://github.com/asdf-community/asdf-dprint)                                       |
| Draft                         | [kristoflemmens/asdf-draft (⭐0)](https://github.com/kristoflemmens/asdf-draft)                                         |
| Driftctl                      | [nlamirault/asdf-driftctl (⭐1)](https://github.com/nlamirault/asdf-driftctl)                                           |
| drone                         | [virtualstaticvoid/asdf-drone (⭐0)](https://github.com/virtualstaticvoid/asdf-drone)                                   |
| dt                            | [so-dang-cool/asdf-dt (⭐2)](https://github.com/so-dang-cool/asdf-dt)                                                   |
| duf                           | [NeoHsu/asdf-duf (⭐1)](https://github.com/NeoHsu/asdf-duf)                                                             |
| dust                          | [looztra/asdf-dust (⭐1)](https://github.com/looztra/asdf-dust)                                                         |
| DVC                           | [fwfurtado/asdf-dvc (⭐0)](https://github.com/fwfurtado/asdf-dvc)                                                       |
| dyff                          | [wt0f/asdf-dyff](https://gitlab.com/wt0f/asdf-dyff)                                                                    |
| earthly                       | [YR-ZR0/asdf-earthly (⭐3)](https://github.com/YR-ZR0/asdf-earthly)                                                     |
| ecspresso                     | [kayac/asdf-ecspresso (⭐3)](https://github.com/kayac/asdf-ecspresso)                                                   |
| editorconfig-checker          | [gabitchov/asdf-editorconfig-checker (⭐2)](https://github.com/gabitchov/asdf-editorconfig-checker)                     |
| ejson                         | [cipherstash/asdf-ejson (⭐0)](https://github.com/cipherstash/asdf-ejson)                                               |
| eksctl                        | [elementalvoid/asdf-eksctl (⭐1)](https://github.com/elementalvoid/asdf-eksctl)                                         |
| elixir-ls                     | [juantascon/asdf-elixir-ls (⭐0)](https://github.com/juantascon/asdf-elixir-ls)                                         |
| Elasticsearch                 | [asdf-community/asdf-elasticsearch (⭐4)](https://github.com/asdf-community/asdf-elasticsearch)                         |
| Elixir                        | [asdf-vm/asdf-elixir (⭐422)](https://github.com/asdf-vm/asdf-elixir)                                                   |
| Elm                           | [asdf-community/asdf-elm (⭐23)](https://github.com/asdf-community/asdf-elm)                                            |
| embulk                        | [yuokada/asdf-embulk (⭐0)](https://github.com/yuokada/asdf-embulk)                                                     |
| Emscripten SDK                | [RobLoach/asdf-emsdk (⭐7)](https://github.com/RobLoach/asdf-emsdk)                                                     |
| EnvCLI                        | [zekker6/asdf-envcli (⭐0)](https://github.com/zekker6/asdf-envcli)                                                     |
| envsubst                      | [dex4er/asdf-envsubst (⭐0)](https://github.com/dex4er/asdf-envsubst)                                                   |
| Ephemeral Postgres            | [smashedtoatoms/asdf-ephemeral-postgres (⭐3)](https://github.com/smashedtoatoms/asdf-ephemeral-postgres)               |
| Erlang                        | [asdf-vm/asdf-erlang (⭐419)](https://github.com/asdf-vm/asdf-erlang)                                                   |
| esy                           | [asdf-community/asdf-esy (⭐4)](https://github.com/asdf-community/asdf-esy)                                             |
| etcd                          | [particledecay/asdf-etcd (⭐4)](https://github.com/particledecay/asdf-etcd)                                             |
| Evans                         | [goki90210/asdf-evans (⭐0)](https://github.com/goki90210/asdf-evans)                                                   |
| exa                           | [nyrst/asdf-exa (⭐1)](https://github.com/nyrst/asdf-exa)                                                               |
| eza                           | [lwiechec/asdf-eza (⭐1)](https://github.com/lwiechec/asdf-eza)                                                         |
| fd                            | [wt0f/asdf-fd](https://gitlab.com/wt0f/asdf-fd)                                                                        |
| FFmpeg                        | [acj/asdf-ffmpeg (⭐5)](https://github.com/acj/asdf-ffmpeg)                                                             |
| figma-export                  | [younke/asdf-figma-export (⭐0)](https://github.com/younke/asdf-figma-export)                                           |
| fillin                        | [ouest/asdf-fillin (⭐1)](https://github.com/ouest/asdf-fillin)                                                         |
| firebase                      | [jthegedus/asdf-firebase (⭐15)](https://github.com/jthegedus/asdf-firebase)                                            |
| fission                       | [virtualstaticvoid/asdf-fission (⭐0)](https://github.com/virtualstaticvoid/asdf-fission)                               |
| Flamingo                      | [log2/asdf-flamingo (⭐0)](https://github.com/log2/asdf-flamingo)                                                       |
| flarectl                      | [ORCID/asdf-flarectl (⭐0)](https://github.com/ORCID/asdf-flarectl)                                                     |
| flatc                         | [TheOpenDictionary/asdf-flatc (⭐0)](https://github.com/TheOpenDictionary/asdf-flatc)                                   |
| Flutter                       | [oae/asdf-flutter (⭐97)](https://github.com/oae/asdf-flutter)                                                          |
| Flux2                         | [tablexi/asdf-flux2 (⭐12)](https://github.com/tablexi/asdf-flux2)                                                      |
| Fluxctl                       | [stefansedich/asdf-fluxctl (⭐2)](https://github.com/stefansedich/asdf-fluxctl)                                         |
| fly                           | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| flyctl                        | [chessmango/asdf-flyctl (⭐4)](https://github.com/chessmango/asdf-flyctl)                                               |
| flyway                        | [junminahn/asdf-flyway (⭐0)](https://github.com/junminahn/asdf-flyway)                                                 |
| func-e                        | [carnei-ro/asdf-func-e (⭐0)](https://github.com/carnei-ro/asdf-func-e)                                                 |
| Furyctl                       | [sighupio/asdf-furyctl (⭐4)](https://github.com/sighupio/asdf-furyctl)                                                 |
| fx                            | [wt0f/asdf-fx](https://gitlab.com/wt0f/asdf-fx)                                                                        |
| fzf                           | [kompiro/asdf-fzf (⭐7)](https://github.com/kompiro/asdf-fzf)                                                           |
| Gauche                        | [sakuro/asdf-gauche (⭐6)](https://github.com/sakuro/asdf-gauche)                                                       |
| gallery-dl                    | [iul1an/asdf-gallery-dl (⭐0)](https://github.com/iul1an/asdf-gallery-dl)                                               |
| gam                           | [offbyone/asdf-gam (⭐0)](https://github.com/offbyone/asdf-gam)                                                         |
| gator                         | [MxNxPx/asdf-gator (⭐0)](https://github.com/MxNxPx/asdf-gator)                                                         |
| gcc-arm-none-eabi             | [dlech/asdf-gcc-arm-none-eabi (⭐3)](https://github.com/dlech/asdf-gcc-arm-none-eabi)                                   |
| gcloud                        | [jthegedus/asdf-gcloud (⭐49)](https://github.com/jthegedus/asdf-gcloud)                                                |
| getenvoy                      | [asdf-community/asdf-getenvoy (⭐2)](https://github.com/asdf-community/asdf-getenvoy)                                   |
| GHC                           | [sestrella/asdf-ghcup (⭐13)](https://github.com/sestrella/asdf-ghcup)                                                  |
| ghidra                        | [Honeypot95/asdf-ghidra (⭐0)](https://github.com/Honeypot95/asdf-ghidra)                                               |
| ghorg                         | [gbloquel/asdf-ghorg (⭐1)](https://github.com/gbloquel/asdf-ghorg)                                                     |
| ghq                           | [kajisha/asdf-ghq (⭐3)](https://github.com/kajisha/asdf-ghq)                                                           |
| ginkgo                        | [jimmidyson/asdf-ginkgo (⭐3)](https://github.com/jimmidyson/asdf-ginkgo)                                               |
| git                           | [jcaigitlab/asdf-git](https://gitlab.com/jcaigitlab/asdf-git)                                                          |
| git-chglog                    | [GoodwayGroup/asdf-git-chglog (⭐2)](https://github.com/GoodwayGroup/asdf-git-chglog)                                   |
| gitconfig                     | [0ghny/asdf-gitconfig (⭐4)](https://github.com/0ghny/asdf-gitconfig)                                                   |
| GitHub CLI                    | [bartlomiejdanek/asdf-github-cli (⭐15)](https://github.com/bartlomiejdanek/asdf-github-cli)                            |
| GitHub Markdown ToC           | [skyzyx/asdf-github-markdown-toc (⭐2)](https://github.com/skyzyx/asdf-github-markdown-toc)                             |
| Gitleaks                      | [jmcvetta/asdf-gitleaks (⭐2)](https://github.com/jmcvetta/asdf-gitleaks)                                               |
| Gitsign                       | [spencergilbert/asdf-gitsign (⭐1)](https://github.com/spencergilbert/asdf-gitsign)                                     |
| gitui                         | [looztra/asdf-gitui (⭐5)](https://github.com/looztra/asdf-gitui)                                                       |
| GLab                          | [particledecay/asdf-glab (⭐3)](https://github.com/particledecay/asdf-glab)                                             |
| Gleam                         | [vic/asdf-gleam (⭐42)](https://github.com/vic/asdf-gleam)                                                              |
| Glen                          | [bradym/asdf-glen (⭐0)](https://github.com/bradym/asdf-glen)                                                           |
| glooctl                       | [halilkaya/asdf-glooctl (⭐0)](https://github.com/halilkaya/asdf-glooctl)                                               |
| glow                          | [chessmango/asdf-glow (⭐2)](https://github.com/chessmango/asdf-glow)                                                   |
| GNU Guile                     | [indiebrain/asdf-guile (⭐1)](https://github.com/indiebrain/asdf-guile)                                                 |
| GNU nano                      | [mfakane/asdf-nano (⭐0)](https://github.com/mfakane/asdf-nano)                                                         |
| Go                            | [asdf-community/asdf-golang (⭐455)](https://github.com/asdf-community/asdf-golang)                                     |
| go-sdk                        | [yacchi/asdf-go-sdk (⭐20)](https://github.com/yacchi/asdf-go-sdk)                                                      |
| go-containerregistry          | [dex4er/asdf-go-containerregistry (⭐0)](https://github.com/dex4er/asdf-go-containerregistry)                           |
| go-getter                     | [ryodocx/asdf-go-getter (⭐1)](https://github.com/ryodocx/asdf-go-getter)                                               |
| go-jsonnet                    | [craigfurman/asdf-go-jsonnet](https://gitlab.com/craigfurman/asdf-go-jsonnet)                                          |
| go-jira                       | [dguihal/asdf-go-jira (⭐2)](https://github.com/dguihal/asdf-go-jira)                                                   |
| go-junit-report               | [jwillker/asdf-go-junit-report (⭐1)](https://github.com/jwillker/asdf-go-junit-report)                                 |
| go-swagger                    | [jfreeland/asdf-go-swagger (⭐0)](https://github.com/jfreeland/asdf-go-swagger)                                         |
| goconvey                      | [therounds-contrib/asdf-goconvey (⭐0)](https://github.com/therounds-contrib/asdf-goconvey)                             |
| gofumpt                       | [looztra/asdf-gofumpt (⭐0)](https://github.com/looztra/asdf-gofumpt)                                                   |
| GoHugo                        | [nklmilojevic/asdf-hugo (⭐6)](https://github.com/nklmilojevic/asdf-hugo)                                               |
| gojq                          | [jimmidyson/asdf-gojq (⭐2)](https://github.com/jimmidyson/asdf-gojq)                                                   |
| golangci-lint                 | [hypnoglow/asdf-golangci-lint (⭐6)](https://github.com/hypnoglow/asdf-golangci-lint)                                   |
| Go Migrate                    | [joschi/asdf-gomigrate (⭐1)](https://github.com/joschi/asdf-gomigrate)                                                 |
| gomplate                      | [sneakybeaky/asdf-gomplate (⭐4)](https://github.com/sneakybeaky/asdf-gomplate)                                         |
| Gopass                        | [trallnag/asdf-gopass (⭐2)](https://github.com/trallnag/asdf-gopass)                                                   |
| GoReleaser                    | [kforsthoevel/asdf-goreleaser (⭐2)](https://github.com/kforsthoevel/asdf-goreleaser)                                   |
| Goss                          | [raimon49/asdf-goss (⭐0)](https://github.com/raimon49/asdf-goss)                                                       |
| GraalVM                       | [asdf-community/asdf-graalvm (⭐17)](https://github.com/asdf-community/asdf-graalvm)                                    |
| Gradle                        | [rfrancis/asdf-gradle (⭐24)](https://github.com/rfrancis/asdf-gradle)                                                  |
| Gradle Profiler               | [joschi/asdf-gradle-profiler (⭐0)](https://github.com/joschi/asdf-gradle-profiler)                                     |
| Grails                        | [weibemoura/asdf-grails (⭐3)](https://github.com/weibemoura/asdf-grails)                                               |
| Grain                         | [cometkim/asdf-grain (⭐4)](https://github.com/cometkim/asdf-grain)                                                     |
| Granted                       | [dex4er/asdf-granted (⭐0)](https://github.com/dex4er/asdf-granted)                                                     |
| grex                          | [ouest/asdf-grex (⭐0)](https://github.com/ouest/asdf-grex)                                                             |
| Groovy                        | [weibemoura/asdf-groovy (⭐3)](https://github.com/weibemoura/asdf-groovy)                                               |
| grpcurl                       | [asdf-community/asdf-grpcurl (⭐3)](https://github.com/asdf-community/asdf-grpcurl)                                     |
| grpc-health-probe             | [zufardhiyaulhaq/asdf-grpc-health-probe (⭐0)](https://github.com/zufardhiyaulhaq/asdf-grpc-health-probe)               |
| grype                         | [poikilotherm/asdf-grype (⭐2)](https://github.com/poikilotherm/asdf-grype)                                             |
| gum                           | [lwiechec/asdf-gum (⭐0)](https://github.com/lwiechec/asdf-gum)                                                         |
| gwvault                       | [GoodwayGroup/asdf-gwvault (⭐0)](https://github.com/GoodwayGroup/asdf-gwvault)                                         |
| hadolint                      | [devlincashman/asdf-hadolint (⭐4)](https://github.com/devlincashman/asdf-hadolint)                                     |
| Hamler                        | [scudelletti/asdf-hamler (⭐1)](https://github.com/scudelletti/asdf-hamler)                                             |
| has                           | [sylvainmetayer/asdf-has (⭐0)](https://github.com/sylvainmetayer/asdf-has)                                             |
| Haskell                       | [asdf-community/asdf-haskell (⭐57)](https://github.com/asdf-community/asdf-haskell)                                    |
| Haskell Language Server (HLS) | [sestrella/asdf-ghcup (⭐13)](https://github.com/sestrella/asdf-ghcup)                                                  |
| Hasura-cli                    | [gurukulkarni/asdf-hasura (⭐3)](https://github.com/gurukulkarni/asdf-hasura)                                           |
| Haxe                          | [asdf-community/asdf-haxe (⭐13)](https://github.com/asdf-community/asdf-haxe)                                          |
| hcl2json                      | [dex4er/asdf-hcl2json (⭐0)](https://github.com/dex4er/asdf-hcl2json)                                                   |
| hcloud                        | [chessmango/asdf-hcloud (⭐3)](https://github.com/chessmango/asdf-hcloud)                                               |
| Helm                          | [Antiarchitect/asdf-helm (⭐46)](https://github.com/Antiarchitect/asdf-helm)                                            |
| Helm Chart Releaser           | [Antiarchitect/asdf-helm-cr (⭐0)](https://github.com/Antiarchitect/asdf-helm-cr)                                       |
| Helm Chart Tester             | [tablexi/asdf-helm-ct (⭐1)](https://github.com/tablexi/asdf-helm-ct)                                                   |
| Helm Diff                     | [dex4er/asdf-helm-diff (⭐2)](https://github.com/dex4er/asdf-helm-diff)                                                 |
| helm-docs                     | [sudermanjr/asdf-helm-docs (⭐0)](https://github.com/sudermanjr/asdf-helm-docs)                                         |
| Helmfile                      | [feniix/asdf-helmfile (⭐2)](https://github.com/feniix/asdf-helmfile)                                                   |
| Helmsman                      | [luisdavim/asdf-helmsman (⭐0)](https://github.com/luisdavim/asdf-helmsman)                                             |
| heroku-cli                    | [treilly94/asdf-heroku-cli (⭐1)](https://github.com/treilly94/asdf-heroku-cli)                                         |
| hey                           | [raimon49/asdf-hey (⭐1)](https://github.com/raimon49/asdf-hey)                                                         |
| hledger                       | [airtonix/hledger (⭐0)](https://github.com/airtonix/asdf-hledger)                                                      |
| hledger-flow                  | [airtonix/hledger-flow (⭐0)](https://github.com/airtonix/asdf-hledger-flow)                                            |
| hostctl                       | [svenluijten/asdf-hostctl (⭐0)](https://github.com/svenluijten/asdf-hostctl)                                           |
| httpie-go                     | [abatilo/asdf-httpie-go (⭐1)](https://github.com/abatilo/asdf-httpie-go)                                               |
| Hub                           | [vixus0/asdf-hub (⭐0)](https://github.com/vixus0/asdf-hub)                                                             |
| Hugo                          | [NeoHsu/asdf-hugo (⭐4)](https://github.com/NeoHsu/asdf-hugo)                                                           |
| Hurl                          | [raimon49/asdf-hurl (⭐0)](https://github.com/raimon49/asdf-hurl)                                                       |
| hwatch                        | [chessmango/asdf-hwatch (⭐2)](https://github.com/chessmango/asdf-hwatch)                                               |
| Hygen                         | [brentjanderson/asdf-hygen (⭐2)](https://github.com/brentjanderson/asdf-hygen)                                         |
| Hyperfine                     | [volf52/asdf-hyperfine (⭐0)](https://github.com/volf52/asdf-hyperfine)                                                 |
| iamlive                       | [chessmango/asdf-iamlive (⭐2)](https://github.com/chessmango/asdf-iamlive)                                             |
| iam-policy-json-to-terraform  | [carlduevel/asdf-iam-policy-json-to-terraform (⭐0)](https://github.com/carlduevel/asdf-iam-policy-json-to-terraform)   |
| ibmcloud                      | [triangletodd/asdf-ibmcloud (⭐1)](https://github.com/triangletodd/asdf-ibmcloud)                                       |
| Idris                         | [asdf-community/asdf-idris (⭐3)](https://github.com/asdf-community/asdf-idris)                                         |
| Idris2                        | [asdf-community/asdf-idris2 (⭐5)](https://github.com/asdf-community/asdf-idris2)                                       |
| ImageMagick                   | [mangalakader/asdf-imagemagick (⭐9)](https://github.com/mangalakader/asdf-imagemagick)                                 |
| imgpkg                        | [vmware-tanzu/asdf-carvel (⭐1)](https://github.com/vmware-tanzu/asdf-carvel)                                           |
| Infracost                     | [dex4er/asdf-infracost (⭐0)](https://github.com/dex4er/asdf-infracost)                                                 |
| Inlets                        | [nlamirault/asdf-inlets (⭐0)](https://github.com/nlamirault/asdf-inlets)                                               |
| Io                            | [mracos/asdf-io (⭐2)](https://github.com/mracos/asdf-io)                                                               |
| Istioctl                      | [virtualstaticvoid/asdf-istioctl (⭐3)](https://github.com/virtualstaticvoid/asdf-istioctl)                             |
| Janet                         | [Jakski/asdf-janet (⭐5)](https://github.com/Jakski/asdf-janet)                                                         |
| Java                          | [halcyon/asdf-java (⭐393)](https://github.com/halcyon/asdf-java)                                                       |
| jb                            | [beardix/asdf-jb (⭐1)](https://github.com/beardix/asdf-jb)                                                             |
| jbang                         | [jbangdev/jbang-asdf (⭐2)](https://github.com/jbangdev/jbang-asdf)                                                     |
| jfrog-cli                     | [LozanoMatheus/asdf-jfrog-cli (⭐1)](https://github.com/LozanoMatheus/asdf-jfrog-cli)                                   |
| jib                           | [joschi/asdf-jib (⭐0)](https://github.com/joschi/asdf-jib)                                                             |
| jiq                           | [chessmango/asdf-jiq (⭐2)](https://github.com/chessmango/asdf-jiq)                                                     |
| jless                         | [jc00ke/asdf-jless (⭐0)](https://github.com/jc00ke/asdf-jless)                                                         |
| JMESPath                      | [skyzyx/asdf-jmespath (⭐2)](https://github.com/skyzyx/asdf-jmespath)                                                   |
| jq                            | [lsanwick/asdf-jq (⭐1)](https://github.com/lsanwick/asdf-jq)                                                           |
| jqp                           | [wt0f/asdf-jqp](https://gitlab.com/wt0f/asdf-jqp)                                                                      |
| JReleaser                     | [joschi/asdf-jreleaser (⭐0)](https://github.com/joschi/asdf-jreleaser)                                                 |
| json2k8s                      | [k14s/asdf-k14s (⭐1)](https://github.com/k14s/asdf-k14s)                                                               |
| Jsonnet                       | [Banno/asdf-jsonnet (⭐2)](https://github.com/Banno/asdf-jsonnet)                                                       |
| Julia                         | [rkyleg/asdf-julia (⭐23)](https://github.com/rkyleg/asdf-julia)                                                        |
| Just                          | [olofvndrhr/asdf-just (⭐2)](https://github.com/olofvndrhr/asdf-just)                                                   |
| jx                            | [vbehar/asdf-jx (⭐2)](https://github.com/vbehar/asdf-jx)                                                               |
| k0sctl                        | [Its-Alex/asdf-plugin-k0sctl (⭐0)](https://github.com/Its-Alex/asdf-plugin-k0sctl)                                     |
| k2tf                          | [carlduevel/asdf-k2tf (⭐1)](https://github.com/carlduevel/asdf-k2tf)                                                   |
| k3d                           | [spencergilbert/asdf-k3d (⭐8)](https://github.com/spencergilbert/asdf-k3d)                                             |
| k3sup                         | [cgroschupp/asdf-k3sup (⭐0)](https://github.com/cgroschupp/asdf-k3sup)                                                 |
| k6                            | [grimoh/asdf-k6 (⭐7)](https://github.com/grimoh/asdf-k6)                                                               |
| k9s                           | [looztra/asdf-k9s (⭐10)](https://github.com/looztra/asdf-k9s)                                                          |
| kafka                         | [ueisele/asdf-kafka (⭐0)](https://github.com/ueisele/asdf-kafka)                                                       |
| kafkactl                      | [anweber/asdf-kafkactl (⭐0)](https://github.com/anweber/asdf-kafkactl)                                                 |
| kapp                          | [vmware-tanzu/asdf-carvel (⭐1)](https://github.com/vmware-tanzu/asdf-carvel)                                           |
| kbld                          | [vmware-tanzu/asdf-carvel (⭐1)](https://github.com/vmware-tanzu/asdf-carvel)                                           |
| kcat                          | [douglasdgoulart/asdf-kcat (⭐0)](https://github.com/douglasdgoulart/asdf-kcat)                                         |
| kcctl                         | [joschi/asdf-kcctl (⭐0)](https://github.com/joschi/asdf-kcctl)                                                         |
| kcl                           | [starkers/asdf-kcl (⭐1)](https://github.com/starkers/asdf-kcl)                                                         |
| kconf                         | [particledecay/asdf-kconf (⭐0)](https://github.com/particledecay/asdf-kconf)                                           |
| Kind                          | [johnlayton/asdf-kind (⭐3)](https://github.com/johnlayton/asdf-kind)                                                   |
| Kiota                         | [asdf-community/asdf-kiota (⭐1)](https://github.com/asdf-community/asdf-kiota)                                         |
| ki                            | [comdotlinux/asdf-ki (⭐0)](https://github.com/comdotlinux/asdf-ki)                                                     |
| kn                            | [joke/asdf-kn (⭐1)](https://github.com/joke/asdf-kn)                                                                   |
| ko                            | [zasdaym/asdf-ko (⭐0)](https://github.com/zasdaym/asdf-ko)                                                             |
| Koka                          | [susurri/asdf-koka (⭐0)](https://github.com/susurri/asdf-koka)                                                         |
| Kompose                       | [technikhil314/asdf-kompose (⭐0)](https://github.com/technikhil314/asdf-kompose)                                       |
| Kops                          | [Antiarchitect/asdf-kops (⭐4)](https://github.com/Antiarchitect/asdf-kops)                                             |
| Kotlin                        | [asdf-community/asdf-kotlin (⭐35)](https://github.com/asdf-community/asdf-kotlin)                                      |
| Kpt                           | [nlamirault/asdf-kpt (⭐1)](https://github.com/nlamirault/asdf-kpt)                                                     |
| kp                            | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| kscript                       | [edgelevel/asdf-kscript (⭐0)](https://github.com/edgelevel/asdf-kscript)                                               |
| krab                          | [ohkrab/asdf-krab (⭐0)](https://github.com/ohkrab/asdf-krab)                                                           |
| krew                          | [bjw-s/asdf-krew (⭐1)](https://github.com/bjw-s/asdf-krew)                                                             |
| Ksonnet                       | [Banno/asdf-ksonnet (⭐0)](https://github.com/Banno/asdf-ksonnet)                                                       |
| ksops                         | [janpieper/asdf-ksops (⭐0)](https://github.com/janpieper/asdf-ksops)                                                   |
| ktlint                        | [esensar/asdf-ktlint (⭐3)](https://github.com/esensar/asdf-ktlint)                                                     |
| kube-capacity                 | [looztra/asdf-kube-capacity (⭐0)](https://github.com/looztra/asdf-kube-capacity)                                       |
| kube-code-generator           | [jimmidyson/asdf-kube-code-generator (⭐0)](https://github.com/jimmidyson/asdf-kube-code-generator)                     |
| kube-controller-tools         | [jimmidyson/asdf-kube-controller-tools (⭐0)](https://github.com/jimmidyson/asdf-kube-controller-tools)                 |
| kube-credential-cache         | [ryodocx/kube-credential-cache (⭐11)](https://github.com/ryodocx/kube-credential-cache)                                |
| kube-linter                   | [devlincashman/asdf-kube-linter (⭐2)](https://github.com/devlincashman/asdf-kube-linter)                               |
| kube-score                    | [bageljp/asdf-kube-score (⭐2)](https://github.com/bageljp/asdf-kube-score)                                             |
| kubebuilder                   | [virtualstaticvoid/asdf-kubebuilder (⭐6)](https://github.com/virtualstaticvoid/asdf-kubebuilder)                       |
| kubecm                        | [samhvw8/asdf-kubecm (⭐0)](https://github.com/samhvw8/asdf-kubecm)                                                     |
| kubecolor                     | [dex4er/asdf-kubecolor (⭐0)](https://github.com/dex4er/asdf-kubecolor)                                                 |
| kubeconform                   | [lirlia/asdf-kubeconform (⭐1)](https://github.com/lirlia/asdf-kubeconform)                                             |
| Kubectl                       | [asdf-community/asdf-kubectl (⭐112)](https://github.com/asdf-community/asdf-kubectl)                                   |
| kubectl-bindrole              | [looztra/asdf-kubectl-bindrole (⭐0)](https://github.com/looztra/asdf-kubectl-bindrole)                                 |
| kubectl-convert               | [iul1an/asdf-kubectl-convert (⭐0)](https://github.com/iul1an/asdf-kubectl-convert)                                     |
| kubectl-buildkit              | [ezcater/asdf-kubectl-buildkit (⭐1)](https://github.com/ezcater/asdf-kubectl-buildkit)                                 |
| kubectl-kots                  | [ganta/asdf-kubectl-kots (⭐2)](https://github.com/ganta/asdf-kubectl-kots)                                             |
| kubectx                       | [wt0f/asdf-kubectx](https://gitlab.com/wt0f/asdf-kubectx)                                                              |
| Kubefedctl                    | [kvokka/asdf-kubefedctl (⭐0)](https://github.com/kvokka/asdf-kubefedctl)                                               |
| Kubefirst                     | [Claywd/asdf-kubefirst (⭐2)](https://github.com/Claywd/asdf-kubefirst)                                                 |
| Kubelogin                     | [sechmann/asdf-kubelogin (⭐0)](https://github.com/sechmann/asdf-kubelogin)                                             |
| Kubemqctl                     | [johnlayton/asdf-kubemqctl (⭐0)](https://github.com/johnlayton/asdf-kubemqctl)                                         |
| kubent                        | [virtualstaticvoid/asdf-kubent (⭐1)](https://github.com/virtualstaticvoid/asdf-kubent)                                 |
| Kubergrunt                    | [NeoHsu/asdf-kubergrunt (⭐0)](https://github.com/NeoHsu/asdf-kubergrunt)                                               |
| Kubeseal                      | [stefansedich/asdf-kubeseal (⭐2)](https://github.com/stefansedich/asdf-kubeseal)                                       |
| Kubesec                       | [vitalis/asdf-kubesec (⭐1)](https://github.com/vitalis/asdf-kubesec)                                                   |
| kubeshark                     | [carnei-ro/asdf-kubeshark (⭐0)](https://github.com/carnei-ro/asdf-kubeshark)                                           |
| kubespy                       | [jfreeland/asdf-kubespy (⭐0)](https://github.com/jfreeland/asdf-kubespy)                                               |
| Kubeval                       | [stefansedich/asdf-kubeval (⭐0)](https://github.com/stefansedich/asdf-kubeval)                                         |
| KubeVela                      | [gustavclausen/asdf-kubevela (⭐0)](https://github.com/gustavclausen/asdf-kubevela)                                     |
| Kubie                         | [johnhamelink/asdf-kubie (⭐0)](https://github.com/johnhamelink/asdf-kubie)                                             |
| Kustomize                     | [Banno/asdf-kustomize (⭐19)](https://github.com/Banno/asdf-kustomize)                                                  |
| kuttl                         | [jimmidyson/asdf-kuttl (⭐0)](https://github.com/jimmidyson/asdf-kuttl)                                                 |
| kwt                           | [vmware-tanzu/asdf-carvel (⭐1)](https://github.com/vmware-tanzu/asdf-carvel)                                           |
| lab                           | [particledecay/asdf-lab (⭐0)](https://github.com/particledecay/asdf-lab)                                               |
| lane                          | [CodeReaper/asdf-lane (⭐0)](https://github.com/CodeReaper/asdf-lane)                                                   |
| lazygit                       | [nklmilojevic/asdf-lazygit (⭐6)](https://github.com/nklmilojevic/asdf-lazygit)                                         |
| Lean                          | [asdf-community/asdf-lean (⭐4)](https://github.com/asdf-community/asdf-lean)                                           |
| Leiningen                     | [miorimmax/asdf-lein (⭐9)](https://github.com/miorimmax/asdf-lein)                                                     |
| Lefthook                      | [jtzero/asdf-lefthook (⭐3)](https://github.com/jtzero/asdf-lefthook)                                                   |
| Levant                        | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| LFE                           | [asdf-community/asdf-lfe (⭐7)](https://github.com/asdf-community/asdf-lfe)                                             |
| Lima                          | [CrouchingMuppet/asdf-lima (⭐0)](https://github.com/CrouchingMuppet/asdf-lima)                                         |
| Link (system tools)           | [asdf-community/asdf-link (⭐49)](https://github.com/asdf-community/asdf-link)                                          |
| Linkerd                       | [kforsthoevel/asdf-linkerd (⭐0)](https://github.com/kforsthoevel/asdf-linkerd)                                         |
| liqoctl                       | [pdemagny/asdf-liqoctl (⭐0)](https://github.com/pdemagny/asdf-liqoctl)                                                 |
| Litestream                    | [threkk/asdf-litestream (⭐1)](https://github.com/threkk/asdf-litestream)                                               |
| Logtalk                       | [LogtalkDotOrg/asdf-logtalk (⭐3)](https://github.com/LogtalkDotOrg/asdf-logtalk)                                       |
| Loki-Logcli                   | [comdotlinux/asdf-loki-logcli (⭐5)](https://github.com/comdotlinux/asdf-loki-logcli)                                   |
| ls-lint                       | [ameausoone/asdf-ls-lint (⭐0)](https://github.com/ameausoone/asdf-ls-lint)                                             |
| Lua                           | [Stratus3D/asdf-lua (⭐47)](https://github.com/Stratus3D/asdf-lua)                                                      |
| LuaJIT                        | [smashedtoatoms/asdf-luaJIT (⭐3)](https://github.com/smashedtoatoms/asdf-luaJIT)                                       |
| lua-language-server           | [bellini666/asdf-lua-language-server (⭐2)](https://github.com/bellini666/asdf-lua-language-server)                     |
| Lucy                          | [cometkim/asdf-lucy (⭐0)](https://github.com/cometkim/asdf-lucy)                                                       |
| maestro                       | [dotanuki-labs/asdf-maestro (⭐3)](https://github.com/dotanuki-labs/asdf-maestro)                                       |
| mage                          | [mathew-fleisch/asdf-mage (⭐1)](https://github.com/mathew-fleisch/asdf-mage)                                           |
| make                          | [yacchi/asdf-make (⭐4)](https://github.com/yacchi/asdf-make)                                                           |
| mani                          | [anweber/asdf-mani (⭐0)](https://github.com/anweber/asdf-mani)                                                         |
| mark                          | [jfreeland/asdf-mark (⭐1)](https://github.com/jfreeland/asdf-mark)                                                     |
| markdownlint-cli2             | [paulo-ferraz-oliveira/asdf-markdownlint-cli2 (⭐3)](https://github.com/paulo-ferraz-oliveira/asdf-markdownlint-cli2)   |
| marp-cli                      | [xataz/asdf-marp-cli (⭐0)](https://github.com/xataz/asdf-marp-cli)                                                     |
| mask                          | [aaaaninja/asdf-mask (⭐0)](https://github.com/aaaaninja/asdf-mask)                                                     |
| Maven                         | [halcyon/asdf-maven (⭐20)](https://github.com/halcyon/asdf-maven)                                                      |
| mdbook                        | [cipherstash/asdf-mdbook (⭐0)](https://github.com/cipherstash/asdf-mdbook)                                             |
| mdbook-linkcheck              | [cipherstash/asdf-mdbook-linkcheck (⭐0)](https://github.com/cipherstash/asdf-mdbook-linkcheck)                         |
| melange                       | [omissis/asdf-melange (⭐0)](https://github.com/omissis/asdf-melange)                                                   |
| melt                          | [chessmango/asdf-melt (⭐1)](https://github.com/chessmango/asdf-melt)                                                   |
| Memcached                     | [furkanural/asdf-memcached (⭐1)](https://github.com/furkanural/asdf-memcached)                                         |
| Mercury                       | [susurri/asdf-mercury (⭐0)](https://github.com/susurri/asdf-mercury)                                                   |
| Meson                         | [asdf-community/asdf-meson (⭐5)](https://github.com/asdf-community/asdf-meson)                                         |
| Micronaut                     | [weibemoura/asdf-micronaut (⭐2)](https://github.com/weibemoura/asdf-micronaut)                                         |
| Mill                          | [asdf-community/asdf-mill (⭐4)](https://github.com/asdf-community/asdf-mill)                                           |
| mimirtool                     | [asdf-community/asdf-mimirtool (⭐0)](https://github.com/asdf-community/asdf-mimirtool)                                 |
| minify                        | [axilleas/asdf-minify (⭐1)](https://github.com/axilleas/asdf-minify)                                                   |
| Minikube                      | [alvarobp/asdf-minikube (⭐17)](https://github.com/alvarobp/asdf-minikube)                                              |
| Minio                         | [aeons/asdf-minio (⭐6)](https://github.com/aeons/asdf-minio)                                                           |
| Minio Client                  | [penpyt/asdf-mc (⭐1)](https://github.com/penpyt/asdf-mc)                                                               |
| Minishift                     | [sqtran/asdf-minishift (⭐1)](https://github.com/sqtran/asdf-minishift)                                                 |
| Mint                          | [mint-lang/asdf-mint (⭐3)](https://github.com/mint-lang/asdf-mint)                                                     |
| mirrord                       | [metalbear-co/asdf-mirrord (⭐0)](https://github.com/metalbear-co/asdf-mirrord)                                         |
| mitmproxy                     | [NeoHsu/asdf-mitmproxy (⭐0)](https://github.com/NeoHsu/asdf-mitmproxy)                                                 |
| mkcert                        | [salasrod/asdf-mkcert (⭐3)](https://github.com/salasrod/asdf-mkcert)                                                   |
| mlton                         | [asdf-community/asdf-mlton (⭐5)](https://github.com/asdf-community/asdf-mlton)                                         |
| mockery                       | [cabify/asdf-mockery (⭐2)](https://github.com/cabify/asdf-mockery)                                                     |
| Monarch                       | [nyuyuyu/asdf-monarch (⭐0)](https://github.com/nyuyuyu/asdf-monarch)                                                   |
| mongo-tools                   | [itspngu/asdf-mongo-tools (⭐1)](https://github.com/itspngu/asdf-mongo-tools)                                           |
| MongoDB                       | [sylph01/asdf-mongodb (⭐10)](https://github.com/sylph01/asdf-mongodb)                                                  |
| mongosh                       | [itspngu/asdf-mongosh (⭐0)](https://github.com/itspngu/asdf-mongosh)                                                   |
| mutanus                       | [SoriUR/asdf-mutanus (⭐0)](https://github.com/SoriUR/asdf-mutanus)                                                     |
| mvnd                          | [joschi/asdf-mvnd (⭐2)](https://github.com/joschi/asdf-mvnd)                                                           |
| MySQL                         | [iroddis/asdf-mysql (⭐18)](https://github.com/iroddis/asdf-mysql)                                                      |
| nancy                         | [iilyak/asdf-nancy (⭐0)](https://github.com/iilyak/asdf-nancy)                                                         |
| nasm                          | [Dpbm/asdf-nasm (⭐0)](https://github.com/Dpbm/asdf-nasm)                                                               |
| Neko Virtual Machine          | [asdf-community/asdf-neko (⭐4)](https://github.com/asdf-community/asdf-neko)                                           |
| Neovim                        | [richin13/asdf-neovim (⭐73)](https://github.com/richin13/asdf-neovim)                                                  |
| nerdctl                       | [dmpe/asdf-nerdctl (⭐1)](https://github.com/dmpe/asdf-nerdctl)                                                         |
| newrelic-cli                  | [NeoHsu/asdf-newrelic-cli (⭐1)](https://github.com/NeoHsu/asdf-newrelic-cli)                                           |
| nfpm                          | [ORCID/asdf-nfpm (⭐1)](https://github.com/ORCID/asdf-nfpm)                                                             |
| Nim                           | [asdf-community/asdf-nim (⭐20)](https://github.com/asdf-community/asdf-nim)                                            |
| Ninja                         | [asdf-community/asdf-ninja (⭐6)](https://github.com/asdf-community/asdf-ninja)                                         |
| Node.js                       | [asdf-vm/asdf-nodejs (⭐815)](https://github.com/asdf-vm/asdf-nodejs)                                                   |
| Nomad                         | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| nomad-pack                    | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| notation                      | [bodgit/asdf-notation (⭐0)](https://github.com/bodgit/asdf-notation)                                                   |
| nova                          | [elementalvoid/asdf-nova (⭐1)](https://github.com/elementalvoid/asdf-nova)                                             |
| NSC                           | [dex4er/asdf-nsc (⭐0)](https://github.com/dex4er/asdf-nsc)                                                             |
| oapi-codegen                  | [dylanrayboss/asdf-oapi-codegen (⭐1)](https://github.com/dylanrayboss/asdf-oapi-codegen)                               |
| oc                            | [sqtran/asdf-oc (⭐0)](https://github.com/sqtran/asdf-oc)                                                               |
| oci                           | [yasn77/asdf-oci (⭐0)](https://github.com/yasn77/asdf-oci)                                                             |
| OCaml                         | [asdf-community/asdf-ocaml (⭐26)](https://github.com/asdf-community/asdf-ocaml)                                        |
| Odin                          | [jtakakura/asdf-odin (⭐6)](https://github.com/jtakakura/asdf-odin)                                                     |
| odo                           | [rm3l/asdf-odo (⭐1)](https://github.com/rm3l/asdf-odo)                                                                 |
| okta-aws-cli                  | [bennythejudge/asdf-plugin-okta-aws-cli (⭐0)](https://github.com/bennythejudge/asdf-plugin-okta-aws-cli)               |
| Okteto                        | [BradenM/asdf-okteto (⭐1)](https://github.com/BradenM/asdf-okteto)                                                     |
| om                            | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| Onyx                          | [jtakakura/asdf-onyx (⭐0)](https://github.com/jtakakura/asdf-onyx)                                                     |
| OPA                           | [tochukwuvictor/asdf-opa (⭐5)](https://github.com/tochukwuvictor/asdf-opa)                                             |
| Opam                          | [asdf-community/asdf-opam (⭐13)](https://github.com/asdf-community/asdf-opam)                                          |
| openfaas-faas-cli             | [zekker6/asdf-faas-cli (⭐0)](https://github.com/zekker6/asdf-faas-cli)                                                 |
| OpenResty                     | [smashedtoatoms/asdf-openresty (⭐5)](https://github.com/smashedtoatoms/asdf-openresty)                                 |
| opensearch                    | [randikabanura/asdf-opensearch (⭐4)](https://github.com/randikabanura/asdf-opensearch)                                 |
| opensearch-cli                | [iul1an/asdf-opensearch-cli (⭐2)](https://github.com/iul1an/asdf-opensearch-cli)                                       |
| openshift-install             | [hhemied/asdf-openshift-install (⭐1)](https://github.com/hhemied/asdf-openshift-install)                               |
| opentofu                      | [virtualroot/asdf-opentofu (⭐10)](https://github.com/virtualroot/asdf-opentofu)                                        |
| Operator SDK                  | [Medium/asdf-operator-sdk (⭐6)](https://github.com/Medium/asdf-operator-sdk)                                           |
| Opsgenie-lamp                 | [ORCID/asdf-opsgenie-lamp (⭐0)](https://github.com/ORCID/asdf-opsgenie-lamp)                                           |
| oras                          | [bodgit/asdf-oras (⭐0)](https://github.com/bodgit/asdf-oras)                                                           |
| Osm                           | [nlamirault/asdf-osm (⭐0)](https://github.com/nlamirault/asdf-osm)                                                     |
| osqueryi                      | [davidecavestro/asdf-osqueryi (⭐1)](https://github.com/davidecavestro/asdf-osqueryi)                                   |
| pachctl                       | [abatilo/asdf-pachctl (⭐0)](https://github.com/abatilo/asdf-pachctl)                                                   |
| Packer                        | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| Pandoc                        | [Fbrisset/asdf-pandoc (⭐0)](https://github.com/Fbrisset/asdf-pandoc)                                                   |
| patat                         | [airtonix/asdf-patat (⭐1)](https://github.com/airtonix/asdf-patat)                                                     |
| peco                          | [asdf-community/asdf-peco (⭐5)](https://github.com/asdf-community/asdf-peco)                                           |
| pdm                           | [1oglop1/asdf-pdm (⭐8)](https://github.com/1oglop1/asdf-pdm)                                                           |
| Perl                          | [ouest/asdf-perl (⭐25)](https://github.com/ouest/asdf-perl)                                                            |
| PHP                           | [asdf-community/asdf-php (⭐194)](https://github.com/asdf-community/asdf-php)                                           |
| pint                          | [sam-burrell/asdf-pint (⭐0)](https://github.com/sam-burrell/asdf-pint)                                                 |
| pipectl                       | [pipe-cd/asdf-pipectl (⭐0)](https://github.com/pipe-cd/asdf-pipectl)                                                   |
| pipelight                     | [kogeletey/asdf-pipelight (⭐1)](https://github.com/kogeletey/asdf-pipelight)                                           |
| pipx                          | [yozachar/asdf-pipx (⭐4)](https://github.com/yozachar/asdf-pipx)                                                       |
| pivnet                        | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| Please                        | [asdf-community/asdf-please (⭐5)](https://github.com/asdf-community/asdf-please)                                       |
| Pluto                         | [FairwindsOps/asdf-pluto (⭐4)](https://github.com/FairwindsOps/asdf-pluto)                                             |
| pnpm                          | [jonathanmorley/asdf-pnpm (⭐46)](https://github.com/jonathanmorley/asdf-pnpm)                                          |
| Poetry                        | [asdf-community/asdf-poetry (⭐64)](https://github.com/asdf-community/asdf-poetry)                                      |
| Polaris                       | [particledecay/asdf-polaris (⭐0)](https://github.com/particledecay/asdf-polaris)                                       |
| Popeye                        | [nlamirault/asdf-popeye (⭐0)](https://github.com/nlamirault/asdf-popeye)                                               |
| Postgres                      | [smashedtoatoms/asdf-postgres (⭐183)](https://github.com/smashedtoatoms/asdf-postgres)                                 |
| powerline-go                  | [dex4er/asdf-powerline-go (⭐0)](https://github.com/dex4er/asdf-powerline-go)                                           |
| PowerShell                    | [daveneeley/asdf-powershell-core (⭐0)](https://github.com/daveneeley/asdf-powershell-core)                             |
| pre-commit                    | [jonathanmorley/asdf-pre-commit (⭐2)](https://github.com/jonathanmorley/asdf-pre-commit)                               |
| promtool                      | [asdf-community/asdf-promtool (⭐0)](https://github.com/asdf-community/asdf-promtool)                                   |
| protoc                        | [paxosglobal/asdf-protoc (⭐18)](https://github.com/paxosglobal/asdf-protoc)                                            |
| protoc-gen-connect-go         | [dylanrayboss/asdf-protoc-gen-connect-go (⭐1)](https://github.com/dylanrayboss/asdf-protoc-gen-connect-go)             |
| protoc-gen-grpc-web           | [pbr0ck3r/asdf-protoc-gen-grpc-web (⭐0)](https://github.com/pbr0ck3r/asdf-protoc-gen-grpc-web)                         |
| protoc-gen-go-grpc            | [pbr0ck3r/asdf-protoc-gen-go-grpc (⭐0)](https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc)                           |
| protoc-gen-go                 | [pbr0ck3r/asdf-protoc-gen-go (⭐0)](https://github.com/pbr0ck3r/asdf-protoc-gen-go)                                     |
| protoc-gen-js                 | [pbr0ck3r/asdf-protoc-gen-js (⭐0)](https://github.com/pbr0ck3r/asdf-protoc-gen-js)                                     |
| protolint                     | [spencergilbert/asdf-protolint (⭐2)](https://github.com/spencergilbert/asdf-protolint)                                 |
| Proton GE                     | [augustobmoura/asdf-protonge (⭐1)](https://github.com/augustobmoura/asdf-protonge)                                     |
| psc-package                   | [nsaunders/asdf-psc-package (⭐0)](https://github.com/nsaunders/asdf-psc-package)                                       |
| Pulumi                        | [canha/asdf-pulumi (⭐9)](https://github.com/canha/asdf-pulumi)                                                         |
| purerl                        | [GoNZooo/asdf-purerl (⭐1)](https://github.com/GoNZooo/asdf-purerl)                                                     |
| PureScript                    | [jrrom/asdf-purescript (⭐0)](https://github.com/jrrom/asdf-purescript)                                                 |
| Purty                         | [nsaunders/asdf-purty (⭐1)](https://github.com/nsaunders/asdf-purty)                                                   |
| Python                        | [danhper/asdf-python (⭐592)](https://github.com/danhper/asdf-python)                                                   |
| q                             | [moritz-makandra/asdf-plugin-qdns (⭐0)](https://github.com/moritz-makandra/asdf-plugin-qdns)                           |
| Quarkus CLI                   | [asdf-community/asdf-quarkus (⭐2)](https://github.com/asdf-community/asdf-quarkus)                                     |
| R                             | [asdf-community/asdf-r (⭐24)](https://github.com/asdf-community/asdf-r)                                                |
| RabbitMQ                      | [w-sanches/asdf-rabbitmq (⭐7)](https://github.com/w-sanches/asdf-rabbitmq)                                             |
| Racket                        | [asdf-community/asdf-racket (⭐12)](https://github.com/asdf-community/asdf-racket)                                      |
| Raku                          | [m-dango/asdf-raku (⭐9)](https://github.com/m-dango/asdf-raku)                                                         |
| Rancher                       | [abinet/asdf-rancher (⭐2)](https://github.com/abinet/asdf-rancher)                                                     |
| Rbac-lookup                   | [looztra/asdf-rbac-lookup (⭐0)](https://github.com/looztra/asdf-rbac-lookup)                                           |
| Rclone                        | [johnlayton/asdf-rclone (⭐1)](https://github.com/johnlayton/asdf-rclone)                                               |
| Rebar                         | [Stratus3D/asdf-rebar (⭐28)](https://github.com/Stratus3D/asdf-rebar)                                                  |
| Reckoner                      | [FairwindsOps/asdf-reckoner (⭐2)](https://github.com/FairwindsOps/asdf-reckoner)                                       |
| Redis                         | [smashedtoatoms/asdf-redis (⭐37)](https://github.com/smashedtoatoms/asdf-redis)                                        |
| Redis-cli                     | [NeoHsu/asdf-redis-cli (⭐2)](https://github.com/NeoHsu/asdf-redis-cli)                                                 |
| redo                          | [chessmango/asdf-redo (⭐2)](https://github.com/chessmango/asdf-redo)                                                   |
| redskyctl                     | [sudermanjr/asdf-redskyctl (⭐0)](https://github.com/sudermanjr/asdf-redskyctl)                                         |
| Reg                           | [looztra/asdf-reg (⭐0)](https://github.com/looztra/asdf-reg)                                                           |
| regal                         | [asdf-community/asdf-regal (⭐0)](https://github.com/asdf-community/asdf-regal)                                         |
| regctl                        | [ORCID/asdf-regctl (⭐0)](https://github.com/ORCID/asdf-regctl)                                                         |
| regsync                       | [rsrchboy/asdf-regsync (⭐1)](https://github.com/rsrchboy/asdf-regsync)                                                 |
| restic                        | [xataz/asdf-restic (⭐0)](https://github.com/xataz/asdf-restic)                                                         |
| revive                        | [bjw-s/asdf-revive (⭐0)](https://github.com/bjw-s/asdf-revive)                                                         |
| richgo                        | [paxosglobal/asdf-richgo (⭐0)](https://github.com/paxosglobal/asdf-richgo)                                             |
| Riff                          | [abinet/asdf-riff (⭐0)](https://github.com/abinet/asdf-riff)                                                           |
| ripgrep                       | [wt0f/asdf-ripgrep](https://gitlab.com/wt0f/asdf-ripgrep)                                                              |
| RKE                           | [particledecay/asdf-rke (⭐0)](https://github.com/particledecay/asdf-rke)                                               |
| rome                          | [kichiemon/asdf-rome (⭐1)](https://github.com/kichiemon/asdf-rome)                                                     |
| rstash                        | [carlduevel/asdf-rstash (⭐0)](https://github.com/carlduevel/asdf-rstash)                                               |
| rlwrap                        | [asdf-community/asdf-rlwrap (⭐3)](https://github.com/asdf-community/asdf-rlwrap)                                       |
| Ruby                          | [asdf-vm/asdf-ruby (⭐590)](https://github.com/asdf-vm/asdf-ruby)                                                       |
| Rust                          | [code-lever/asdf-rust (⭐137)](https://github.com/code-lever/asdf-rust)                                                 |
| rust-analyzer                 | [Xyven1/asdf-rust-analyzer (⭐3)](https://github.com/Xyven1/asdf-rust-analyzer)                                         |
| rye                           | [Azuki-bar/asdf-rye (⭐0)](https://github.com/Azuki-bar/asdf-rye)                                                       |
| saml2aws                      | [elementalvoid/asdf-saml2aws (⭐5)](https://github.com/elementalvoid/asdf-saml2aws)                                     |
| SBT                           | [bram2000/asdf-sbt (⭐0)](https://github.com/bram2000/asdf-sbt)                                                         |
| Scala                         | [asdf-community/asdf-scala (⭐17)](https://github.com/asdf-community/asdf-scala)                                        |
| Scala CLI                     | [asdf-community/asdf-scala-cli (⭐3)](https://github.com/asdf-community/asdf-scala-cli)                                 |
| scaleway-cli                  | [albarralnunez/asdf-plugin-scaleway-cli (⭐0)](https://github.com/albarralnunez/asdf-plugin-scaleway-cli)               |
| scalingo-cli                  | [brandon-welsch/asdf-scalingo-cli (⭐1)](https://github.com/brandon-welsch/asdf-scalingo-cli)                           |
| Scarb                         | [software-mansion/asdf-scarb (⭐5)](https://github.com/software-mansion/asdf-scarb)                                     |
| sccache                       | [emersonmx/asdf-sccache (⭐1)](https://github.com/emersonmx/asdf-sccache)                                               |
| Scenery                       | [skyzyx/asdf-scenery (⭐0)](https://github.com/skyzyx/asdf-scenery)                                                     |
| schemacrawler                 | [davidecavestro/asdf-schemacrawler (⭐0)](https://github.com/davidecavestro/asdf-schemacrawler)                         |
| Seed7                         | [susurri/asdf-seed7 (⭐0)](https://github.com/susurri/asdf-seed7)                                                       |
| Semgrep                       | [brentjanderson/asdf-semgrep (⭐2)](https://github.com/brentjanderson/asdf-semgrep)                                     |
| semtag                        | [junminahn/asdf-semtag (⭐0)](https://github.com/junminahn/asdf-semtag)                                                 |
| semver                        | [mathew-fleisch/asdf-semver (⭐3)](https://github.com/mathew-fleisch/asdf-semver)                                       |
| Sentinel                      | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| Serf                          | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| serverless                    | [pdemagny/asdf-serverless (⭐2)](https://github.com/pdemagny/asdf-serverless)                                           |
| shell2http                    | [ORCID/asdf-shell2http (⭐2)](https://github.com/ORCID/asdf-shell2http)                                                 |
| Shellcheck                    | [luizm/asdf-shellcheck (⭐22)](https://github.com/luizm/asdf-shellcheck)                                                |
| Shellspec                     | [poikilotherm/asdf-shellspec (⭐0)](https://github.com/poikilotherm/asdf-shellspec)                                     |
| Shfmt                         | [luizm/asdf-shfmt (⭐11)](https://github.com/luizm/asdf-shfmt)                                                          |
| Shorebird                     | [valian-ca/asdf-shorebird (⭐0)](https://github.com/valian-ca/asdf-shorebird)                                           |
| Sinker                        | [elementalvoid/asdf-sinker (⭐0)](https://github.com/elementalvoid/asdf-sinker)                                         |
| Skaffold                      | [nklmilojevic/asdf-skaffold (⭐1)](https://github.com/nklmilojevic/asdf-skaffold)                                       |
| skate                         | [chessmango/asdf-skate (⭐3)](https://github.com/chessmango/asdf-skate)                                                 |
| Sloth                         | [slok/asdf-sloth (⭐2)](https://github.com/slok/asdf-sloth)                                                             |
| smithy                        | [aws/asdf-smithy (⭐3)](https://github.com/aws/asdf-smithy)                                                             |
| SML/NJ                        | [samontea/asdf-smlnj (⭐2)](https://github.com/samontea/asdf-smlnj)                                                     |
| Snyk                          | [nirfuchs/asdf-snyk (⭐2)](https://github.com/nirfuchs/asdf-snyk)                                                       |
| soft-serve                    | [chessmango/asdf-soft-serve (⭐3)](https://github.com/chessmango/asdf-soft-serve)                                       |
| Solidity                      | [diegodorado/asdf-solidity (⭐4)](https://github.com/diegodorado/asdf-solidity)                                         |
| Sonobuoy                      | [Nick-Triller/asdf-sonobuoy (⭐0)](https://github.com/Nick-Triller/asdf-sonobuoy)                                       |
| Sops                          | [feniix/asdf-sops (⭐8)](https://github.com/feniix/asdf-sops)                                                           |
| sopstool                      | [elementalvoid/asdf-sopstool (⭐0)](https://github.com/elementalvoid/asdf-sopstool)                                     |
| soracom-cli                   | [grimoh/asdf-soracom (⭐2)](https://github.com/grimoh/asdf-soracom)                                                     |
| Sourcery                      | [younke/asdf-sourcery (⭐1)](https://github.com/younke/asdf-sourcery)                                                   |
| spacectl                      | [bodgit/asdf-spacectl (⭐0)](https://github.com/bodgit/asdf-spacectl)                                                   |
| Spago                         | [jrrom/asdf-spago (⭐0)](https://github.com/jrrom/asdf-spago)                                                           |
| Spark                         | [joshuaballoch/asdf-spark (⭐1)](https://github.com/joshuaballoch/asdf-spark)                                           |
| Spectral                      | [vbyrd/asdf-spectral (⭐0)](https://github.com/vbyrd/asdf-spectral)                                                     |
| Spin                          | [pavloos/asdf-spin (⭐0)](https://github.com/pavloos/asdf-spin)                                                         |
| Spring Boot CLI               | [joschi/asdf-spring-boot (⭐2)](https://github.com/joschi/asdf-spring-boot)                                             |
| Spruce                        | [woneill/asdf-spruce (⭐0)](https://github.com/woneill/asdf-spruce)                                                     |
| sqldef                        | [cometkim/asdf-sqldef (⭐3)](https://github.com/cometkim/asdf-sqldef)                                                   |
| SQLite                        | [cLupus/asdf-sqlite (⭐9)](https://github.com/cLupus/asdf-sqlite)                                                       |
| sshuttle                      | [xanmanning/asdf-sshuttle (⭐0)](https://github.com/xanmanning/asdf-sshuttle)                                           |
| Stack                         | [sestrella/asdf-ghcup (⭐13)](https://github.com/sestrella/asdf-ghcup)                                                  |
| starboard                     | [zufardhiyaulhaq/asdf-starboard (⭐0)](https://github.com/zufardhiyaulhaq/asdf-starboard)                               |
| Starknet Foundry              | [foundry-rs/asdf-starknet-foundry (⭐2)](https://github.com/foundry-rs/asdf-starknet-foundry)                           |
| starport                      | [nikever/asdf-starport (⭐0)](https://github.com/nikever/asdf-starport)                                                 |
| starship                      | [grimoh/asdf-starship (⭐11)](https://github.com/grimoh/asdf-starship)                                                  |
| Staticcheck                   | [pbr0ck3r/asdf-staticcheck (⭐0)](https://github.com/pbr0ck3r/asdf-staticcheck)                                         |
| steampipe                     | [carnei-ro/asdf-steampipe (⭐5)](https://github.com/carnei-ro/asdf-steampipe)                                           |
| Steel Bank Common Lisp (sbcl) | [smashedtoatoms/asdf-sbcl (⭐20)](https://github.com/smashedtoatoms/asdf-sbcl)                                          |
| step                          | [log2/asdf-step (⭐1)](https://github.com/log2/asdf-step)                                                               |
| Stern                         | [looztra/asdf-stern (⭐4)](https://github.com/looztra/asdf-stern)                                                       |
| stripe-cli                    | [offbyone/asdf-stripe (⭐0)](https://github.com/offbyone/asdf-stripe)                                                   |
| stylua                        | [jc00ke/asdf-stylua (⭐2)](https://github.com/jc00ke/asdf-stylua)                                                       |
| svu                           | [asdf-community/asdf-svu (⭐1)](https://github.com/asdf-community/asdf-svu)                                             |
| swag                          | [behoof4mind/asdf-swag (⭐0)](https://github.com/behoof4mind/asdf-swag)                                                 |
| Swift                         | [fcrespo82/asdf-swift (⭐9)](https://github.com/fcrespo82/asdf-swift)                                                   |
| SwiftFormat                   | [younke/asdf-swiftformat (⭐2)](https://github.com/younke/asdf-swiftformat)                                             |
| SwiftGen                      | [younke/asdf-swiftgen (⭐0)](https://github.com/younke/asdf-swiftgen)                                                   |
| Swiftlint                     | [klundberg/asdf-swiftlint (⭐0)](https://github.com/klundberg/asdf-swiftlint)                                           |
| SWIProlog                     | [mracos/asdf-swiprolog (⭐8)](https://github.com/mracos/asdf-swiprolog)                                                 |
| syft                          | [davidgp1701/asdf-syft (⭐0)](https://github.com/davidgp1701/asdf-syft)                                                 |
| syncher                       | [nwillc/syncher (⭐7)](https://github.com/nwillc/syncher)                                                               |
| talhelper                     | [bjw-s/asdf-talhelper (⭐2)](https://github.com/bjw-s/asdf-talhelper)                                                   |
| Talos                         | [particledecay/asdf-talos (⭐3)](https://github.com/particledecay/asdf-talos)                                           |
| talosctl                      | [bjw-s/asdf-talosctl (⭐0)](https://github.com/bjw-s/asdf-talosctl)                                                     |
| Tanka                         | [trotttrotttrott/asdf-tanka (⭐1)](https://github.com/trotttrotttrott/asdf-tanka)                                       |
| Tanzu CLI (tanzu)             | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| Task                          | [particledecay/asdf-task (⭐2)](https://github.com/particledecay/asdf-task)                                             |
| tctl                          | [eko/asdf-tctl (⭐0)](https://github.com/eko/asdf-tctl)                                                                 |
| Tekton-cli                    | [johnhamelink/asdf-tekton-cli (⭐0)](https://github.com/johnhamelink/asdf-tekton-cli)                                   |
| Teleport Enterprise           | [highb/asdf-teleport-ent (⭐4)](https://github.com/highb/asdf-teleport-ent)                                             |
| Teleport Community            | [MaloPolese/asdf-teleport-community (⭐1)](https://github.com/MaloPolese/asdf-teleport-community)                       |
| telepresence                  | [pirackr/asdf-telepresence (⭐1)](https://github.com/pirackr/asdf-telepresence)                                         |
| teller                        | [pdemagny/asdf-teller (⭐0)](https://github.com/pdemagny/asdf-teller)                                                   |
| temporal                      | [asdf-community/asdf-temporal (⭐0)](https://github.com/asdf-community/asdf-temporal)                                   |
| temporalite                   | [eko/asdf-temporalite (⭐1)](https://github.com/eko/asdf-temporalite)                                                   |
| terradozer                    | [chessmango/asdf-terradozer (⭐2)](https://github.com/chessmango/asdf-terradozer)                                       |
| Terraform                     | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| Terraform-docs                | [looztra/asdf-terraform-docs (⭐3)](https://github.com/looztra/asdf-terraform-docs)                                     |
| terraform-ls                  | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| terraform-lsp                 | [bartlomiejdanek/asdf-terraform-lsp (⭐2)](https://github.com/bartlomiejdanek/asdf-terraform-lsp)                       |
| Terraform-validator           | [looztra/asdf-terraform-validator (⭐1)](https://github.com/looztra/asdf-terraform-validator)                           |
| Terraformer                   | [grimoh/asdf-terraformer (⭐1)](https://github.com/grimoh/asdf-terraformer)                                             |
| Terragrunt                    | [ohmer/asdf-terragrunt (⭐9)](https://github.com/ohmer/asdf-terragrunt)                                                 |
| Terramate                     | [martinlindner/asdf-terramate (⭐3)](https://github.com/martinlindner/asdf-terramate)                                   |
| Terrascan                     | [hpdobrica/asdf-terrascan (⭐1)](https://github.com/hpdobrica/asdf-terrascan)                                           |
| tfctl                         | [deas/asdf-tfctl (⭐0)](https://github.com/deas/asdf-tfctl)                                                             |
| tfc-agent                     | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| tfenv                         | [carlduevel/asdf-tfenv (⭐3)](https://github.com/carlduevel/asdf-tfenv)                                                 |
| TFLint                        | [skyzyx/asdf-tflint (⭐3)](https://github.com/skyzyx/asdf-tflint)                                                       |
| tfmigrate                     | [dex4er/asdf-tfmigrate (⭐0)](https://github.com/dex4er/asdf-tfmigrate)                                                 |
| tfnotify                      | [jnavarrof/asdf-tfnotify (⭐0)](https://github.com/jnavarrof/asdf-tfnotify)                                             |
| TFSec                         | [woneill/asdf-tfsec (⭐6)](https://github.com/woneill/asdf-tfsec)                                                       |
| tfstate-lookup                | [carnei-ro/asdf-tfstate-lookup (⭐0)](https://github.com/carnei-ro/asdf-tfstate-lookup)                                 |
| tfswitch                      | [iul1an/asdf-tfswitch (⭐0)](https://github.com/iul1an/asdf-tfswitch)                                                   |
| tfupdate                      | [yuokada/asdf-tfupdate (⭐0)](https://github.com/yuokada/asdf-tfupdate)                                                 |
| tf-summarize                  | [adamcrews/asdf-tf-summarize (⭐1)](https://github.com/adamcrews/asdf-tf-summarize)                                     |
| Thrift                        | [alisaifee/asdf-thrift (⭐2)](https://github.com/alisaifee/asdf-thrift)                                                 |
| Tilt                          | [eaceaser/asdf-tilt (⭐1)](https://github.com/eaceaser/asdf-tilt)                                                       |
| Timoni                        | [Smana/asdf-timoni (⭐1)](https://github.com/Smana/asdf-timoni)                                                         |
| Tinytex                       | [Fbrisset/asdf-tinytex (⭐0)](https://github.com/Fbrisset/asdf-tinytex)                                                 |
| Titan                         | [gabitchov/asdf-titan (⭐0)](https://github.com/gabitchov/asdf-titan)                                                   |
| tlsg-cli                      | [0ghny/asdf-tlsgcli (⭐1)](https://github.com/0ghny/asdf-tlsgcli)                                                       |
| Tmux                          | [aphecetche/asdf-tmux (⭐15)](https://github.com/aphecetche/asdf-tmux)                                                  |
| Tokei                         | [gasuketsu/asdf-tokei (⭐0)](https://github.com/gasuketsu/asdf-tokei)                                                   |
| tomcat                        | [mbutov/asdf-tomcat (⭐3)](https://github.com/mbutov/asdf-tomcat)                                                       |
| tonnage                       | [elementalvoid/asdf-tonnage (⭐0)](https://github.com/elementalvoid/asdf-tonnage)                                       |
| tool-versions-to-env          | [smartcontractkit/tool-versions-to-env-action (⭐5)](https://github.com/smartcontractkit/tool-versions-to-env-action)   |
| Traefik                       | [Dabolus/asdf-traefik (⭐0)](https://github.com/Dabolus/asdf-traefik)                                                   |
| Trdsql                        | [johnlayton/asdf-trdsql (⭐0)](https://github.com/johnlayton/asdf-trdsql)                                               |
| tree-sitter                   | [ivanvc/asdf-tree-sitter (⭐1)](https://github.com/ivanvc/asdf-tree-sitter)                                             |
| tridentctl                    | [asdf-community/asdf-tridentctl (⭐1)](https://github.com/asdf-community/asdf-tridentctl)                               |
| Trivy                         | [zufardhiyaulhaq/asdf-trivy (⭐3)](https://github.com/zufardhiyaulhaq/asdf-trivy)                                       |
| tsuru                         | [virtualstaticvoid/asdf-tsuru (⭐0)](https://github.com/virtualstaticvoid/asdf-tsuru)                                   |
| tttyd                         | [ivanvc/asdf-ttyd (⭐0)](https://github.com/ivanvc/asdf-ttyd)                                                           |
| tuist                         | [asdf-community/asdf-tuist (⭐2)](https://github.com/asdf-community/asdf-tuist)                                         |
| tx                            | [ORCID/asdf-transifex (⭐1)](https://github.com/ORCID/asdf-transifex)                                                   |
| typos                         | [aschiavon91/asdf-typos (⭐2)](https://github.com/aschiavon91/asdf-typos)                                               |
| uaa-cli                       | [vmware-tanzu/tanzu-plug-in-for-asdf (⭐4)](https://github.com/vmware-tanzu/tanzu-plug-in-for-asdf)                     |
| Unison                        | [susurri/asdf-unison (⭐0)](https://github.com/susurri/asdf-unison)                                                     |
| updatecli                     | [updatecli/asdf-updatecli (⭐3)](https://github.com/updatecli/asdf-updatecli)                                           |
| upt                           | [ORCID/asdf-upt (⭐0)](https://github.com/ORCID/asdf-upt)                                                               |
| upx                           | [jimmidyson/asdf-upx (⭐1)](https://github.com/jimmidyson/asdf-upx)                                                     |
| usql                          | [itspngu/asdf-usql (⭐0)](https://github.com/itspngu/asdf-usql)                                                         |
| V                             | [jthegedus/asdf-v (⭐6)](https://github.com/jthegedus/asdf-v)                                                           |
| vale                          | [pdemagny/asdf-vale (⭐0)](https://github.com/pdemagny/asdf-vale)                                                       |
| vals                          | [dex4er/asdf-vals (⭐0)](https://github.com/dex4er/asdf-vals)                                                           |
| Vault                         | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| Velero                        | [looztra/asdf-velero (⭐4)](https://github.com/looztra/asdf-velero)                                                     |
| vendir                        | [vmware-tanzu/asdf-carvel (⭐1)](https://github.com/vmware-tanzu/asdf-carvel)                                           |
| Venom                         | [aabouzaid/asdf-venom (⭐0)](https://github.com/aabouzaid/asdf-venom)                                                   |
| vcluster                      | [wt0f/asdf-vcluster](https://gitlab.com/wt0f/asdf-vcluster)                                                            |
| vela                          | [pdemagny/asdf-vela (⭐2)](https://github.com/pdemagny/asdf-vela)                                                       |
| velad                         | [pdemagny/asdf-velad (⭐0)](https://github.com/pdemagny/asdf-velad)                                                     |
| vhs                           | [chessmango/asdf-vhs (⭐2)](https://github.com/chessmango/asdf-vhs)                                                     |
| Viddy                         | [ryodocx/asdf-viddy (⭐0)](https://github.com/ryodocx/asdf-viddy)                                                       |
| Vim                           | [tsuyoshicho/asdf-vim (⭐9)](https://github.com/tsuyoshicho/asdf-vim)                                                   |
| vlt                           | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| vultr-cli                     | [ikuradon/asdf-vultr-cli (⭐0)](https://github.com/ikuradon/asdf-vultr-cli)                                             |
| watchexec                     | [nyrst/asdf-watchexec (⭐3)](https://github.com/nyrst/asdf-watchexec)                                                   |
| WASI SDK                      | [coolreader18/asdf-wasi-sdk (⭐4)](https://github.com/coolreader18/asdf-wasi-sdk)                                       |
| WASM-4                        | [jtakakura/asdf-wasm4 (⭐3)](https://github.com/jtakakura/asdf-wasm4)                                                   |
| wasm3                         | [tachyonicbytes/asdf-wasm3 (⭐1)](https://github.com/tachyonicbytes/asdf-wasm3)                                         |
| wasmer                        | [tachyonicbytes/asdf-wasmer (⭐3)](https://github.com/tachyonicbytes/asdf-wasmer)                                       |
| wasmtime                      | [tachyonicbytes/asdf-wasmtime (⭐4)](https://github.com/tachyonicbytes/asdf-wasmtime)                                   |
| Waypoint                      | [asdf-community/asdf-hashicorp (⭐209)](https://github.com/asdf-community/asdf-hashicorp)                               |
| weave-gitops                  | [deas/asdf-weave-gitops (⭐0)](https://github.com/deas/asdf-weave-gitops)                                               |
| Websocat                      | [bdellegrazie/asdf-websocat (⭐0)](https://github.com/bdellegrazie/asdf-websocat)                                       |
| Wren CLI                      | [jtakakura/asdf-wren-cli (⭐1)](https://github.com/jtakakura/asdf-wren-cli)                                             |
| wrk                           | [ivanvc/asdf-wrk (⭐0)](https://github.com/ivanvc/asdf-wrk)                                                             |
| Wtfutil                       | [NeoHsu/asdf-wtfutil (⭐0)](https://github.com/NeoHsu/asdf-wtfutil)                                                     |
| XCTestHTMLReport              | [younke/asdf-xchtmlreport (⭐1)](https://github.com/younke/asdf-xchtmlreport)                                           |
| XcodeGen                      | [younke/asdf-xcodegen (⭐1)](https://github.com/younke/asdf-xcodegen)                                                   |
| xc                            | [airtonix/asdf-xc (⭐0)](https://github.com/airtonix/asdf-xc)                                                           |
| xcodes                        | [younke/asdf-xcodes (⭐2)](https://github.com/younke/asdf-xcodes)                                                       |
| xh                            | [NeoHsu/asdf-xh (⭐1)](https://github.com/NeoHsu/asdf-xh)                                                               |
| yadm                          | [particledecay/asdf-yadm (⭐0)](https://github.com/particledecay/asdf-yadm)                                             |
| yamlfmt                       | [kachick/asdf-yamlfmt (⭐0)](https://github.com/kachick/asdf-yamlfmt)                                                   |
| yamllint                      | [ericcornelissen/asdf-yamllint (⭐0)](https://github.com/ericcornelissen/asdf-yamllint)                                 |
| Yarn                          | [twuni/asdf-yarn (⭐130)](https://github.com/twuni/asdf-yarn)                                                           |
| yay                           | [aaaaninja/asdf-yay (⭐1)](https://github.com/aaaaninja/asdf-yay)                                                       |
| Yor                           | [ordinaryexperts/asdf-yor (⭐1)](https://github.com/ordinaryexperts/asdf-yor)                                           |
| youtube-dl                    | [iul1an/asdf-youtube-dl (⭐1)](https://github.com/iul1an/asdf-youtube-dl)                                               |
| yj                            | [ryodocx/asdf-yj (⭐0)](https://github.com/ryodocx/asdf-yj)                                                             |
| yq                            | [sudermanjr/asdf-yq (⭐9)](https://github.com/sudermanjr/asdf-yq)                                                       |
| yt-dlp                        | [duhow/asdf-yt-dlp (⭐0)](https://github.com/duhow/asdf-yt-dlp)                                                         |
| ytt                           | [vmware-tanzu/asdf-carvel (⭐1)](https://github.com/vmware-tanzu/asdf-carvel)                                           |
| zbctl                         | [camunda-community-hub/asdf-zbctl (⭐0)](https://github.com/camunda-community-hub/asdf-zbctl)                           |
| zellij                        | [chessmango/asdf-zellij (⭐6)](https://github.com/chessmango/asdf-zellij)                                               |
| Zephyr                        | [nsaunders/asdf-zephyr (⭐1)](https://github.com/nsaunders/asdf-zephyr)                                                 |
| Zig                           | [cheetah/asdf-zig (⭐22)](https://github.com/cheetah/asdf-zig)                                                          |
| zigmod                        | [kachick/asdf-zigmod (⭐2)](https://github.com/kachick/asdf-zigmod)                                                     |
| Zola                          | [salasrod/asdf-zola (⭐4)](https://github.com/salasrod/asdf-zola)                                                       |
| zoxide                        | [nyrst/asdf-zoxide (⭐5)](https://github.com/nyrst/asdf-zoxide)                                                         |
| zprint                        | [carlduevel/asdf-zprint (⭐1)](https://github.com/carlduevel/asdf-zprint)                                               |

