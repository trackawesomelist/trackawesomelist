# Track Awesome Kustomize Updates Weekly

A curated and collaborative list of awesome Kustomize resources

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/aabouzaid/awesome-kustomize/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 aabouzaid/awesome-kustomize](https://github.com/DevOpsHiveHQ/awesome-kustomize) · ⭐ 104 · 🏷️ DevOps

[ [Daily](/content/aabouzaid/awesome-kustomize/README.md) / Weekly / [Overview](/content/aabouzaid/awesome-kustomize/readme/README.md) ]

## [May 12 - May 18, 2025](/content/2025/19/README.md)

### Guides / Intermediate

*   📰 [Using Kustomize Components with Cluster API](https://blog.scottlowe.org/2021/11/01/using-kustomize-components-with-cluster-api/) - A clear use case of using Kustomize Components.

## [Sep 11 - Sep 17, 2023](/content/2023/37/README.md)

### Plugins / Generators

*   [Merger (⭐32)](https://github.com/aabouzaid/kustomize-plugin-merger) - Generating manifests seamlessly by extending Kustomize merge strategies using schemaless StrategicMerge (Containerized KRM, Exec KRM).

## [Sep 04 - Sep 10, 2023](/content/2023/36/README.md)

### Plugins / Generators

*   [KRMFfnBuiltin (⭐5)](https://github.com/kaweezle/krmfnbuiltin) - Running builtin generators transformers (Exec).

### Guides / Intermediate

*   🧪 [ArgoCD GitOps Tutorial - Working with Kustomize](https://redhat-scholars.github.io/argocd-tutorial/argocd-tutorial/03-kustomize.html) - A hands-on lab covers using Kustomize in GitOps and it goes through the Kustomize syntax and deploying a Kustomized application.

## [Aug 07 - Aug 13, 2023](/content/2023/32/README.md)

### Plugins / Generators

*   [Secretize (⭐70)](https://github.com/bbl/secretize) - Generating Kubernetes Secret from various sources. It's like a swiss army knife, but for Kubernetes secrets (Exec).
*   [SopsSecretGenerator (⭐114)](https://github.com/goabout/kustomize-sopssecretgenerator/) - Generating Secrets from sops-encrypted files (Exec, Exec KRM).
*   [KSops (⭐705)](https://github.com/viaduct-ai/kustomize-sops) - Generating Secrets from sops-encrypted files (Exec).
*   [PolicyGenerator (⭐29)](https://github.com/open-cluster-management-io/policy-generator-plugin) - Generating Open Cluster Management policies (Exec).

### Plugins / Transformers

*   [HelmValuesTransformer (⭐14)](https://github.com/openinfradev/kustomize-helm-transformer) - Transforming values in HelmRelease CustomResource. It helps to manage a lot of HelmRelease's value in single transformer file (Exec).
*   [TemplateTransformer (⭐12)](https://github.com/joshdk/template-transformer) - Providing a set of KRM Functions to run builtin transformers in place (Containerized KRM, Exec KRM).

### Plugins / Validators

*   [KubeconformValidator (⭐8)](https://github.com/aabouzaid/kustomize-kubeconformvalidator) - Validating Kubernetes manifests using embedded Kubeconform (Containerized KRM, Exec KRM).

### Misc / Tips & Tricks

*   [Asdf-kustomize (⭐23)](https://github.com/Banno/asdf-kustomize) - Kustomize plugin for asdf version manager.

### Related lists / Tips & Tricks

*   [Awesome Kubernetes (⭐15k)](https://github.com/ramitsurana/awesome-kubernetes) - A curated list of awesome Kubernetes resources.
*   [Awesome Kubectl plugins (⭐954)](https://github.com/ishantanu/awesome-kubectl-plugins) - A curated list of awesome Kubectl plugins.
*   [Awesome Helm (⭐1k)](https://github.com/cdwv/awesome-helm) - A curated list of awesome Helm charts and resources.

## [Apr 10 - Apr 16, 2023](/content/2023/15/README.md)

### Guides / Novice

*   📰 [Declarative Management of Kubernetes Objects Using Kustomize](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/) - The official Kubernetes documentation task for Kustomize.
*   📰 [Configure Kubernetes with Kustomize](https://cloud.google.com/anthos-config-management/docs/concepts/kustomize) - A guide helps to get started with Kustomize, understand its intended use cases, and find resources for using it with other Google Cloud tools.
*   📺 [Organizing the YAML mess with Kustomize](https://www.youtube.com/watch?v=1fCAwFGX38U) - A talk shows how Kustomize could help to manage Kubernetes YAML files with a growing number of services and environments.
*   📺 [Kustomize: Deploy Your App with Template Free YAML](https://www.youtube.com/watch?v=ahMIBxufNR0) - A talk introduces Kustomize, a declarative application management system, that allows deployments to be described as template free YAML.

### Guides / Intermediate

*   📰 [3 ways to customize off-the-shelf Helm charts with Kustomize](https://tech.aabouzaid.com/2020/09/3-ways-to-customize-off-the-shelf-helm-charts-with-kustomize-kubernetes.html) - A guide covers 3 different ways to use Kustomize and Helm together.

### Guides / Advanced

*   📰 [Advanced Kustomize features](https://www.innoq.com/en/blog/advanced-kustomize-features/) - A guide covers more than 5 advanced Kustomize capabilities.
*   📰 [Set OpenAPI patch strategy for Kubernetes Custom Resources](https://tech.aabouzaid.com/2022/11/set-openapi-patch-strategy-for-kubernetes-custom-resources-kustomize.html) - A guide shows how to provide schema to control the patch strategy of the CRDs.
*   📺 [Customizing Kustomize with Client-Side Custom Resources](https://www.youtube.com/watch?v=YlFUv4F5PYc) - A talk covers extending Kustomize via plugins to address common yet idiosyncratic application needs.
*   📺 [Own your YAML: extending Kustomize via Plugins](https://www.youtube.com/watch?v=Xoh_OpLoVtI) - A talk shows how to create custom resources using Kustomize external plugins.
*   📰 [Kustomize Enhancement with KRM Functions](https://www.innoq.com/en/blog/kustomize-enhancement-with-krm-functions/) - A detailed guide covers KRM concept and how to use it in Kustomize plugins.

### Guides / Tips & Tricks

*   📰 [Delete a manifest from a Kustomize base](https://tech.aabouzaid.com/2021/05/delete-a-manifest-from-kustomize-base.html) - A handy way to delete named manifest using Kustomize patch.
*   📰 [Apply Kustomize builtin transformers on a single resource](https://tech.aabouzaid.com/2022/04/apply-kustomize-builtin-transformers-on-a-single-resource.html) - A way to use internal transformers on specific resources.
*   📰 [Pass extra data to the Containerized KRM function](https://tech.aabouzaid.com/2022/12/pass-extra-data-to-the-containerized-krm-function.html) - Different cases of share data with Containerized KRM function.