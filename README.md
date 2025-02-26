<br>
<p align="center">
  <img width="220" height="100" src="./docs/assets/logos/logo.svg">
</p>


<h3 align="center">Homelab</h3>


<p align="center">
  <img src="https://img.shields.io/github/last-commit/gruberdev/homelab?color=black&labelColor=black&label=last%20commit&logo=github&logoColor=cyan&style=flat-square">
</p>

<br>

---

<details>

<summary> <b>Implemented applications</b> </summary>
<br>

> |             **Application**            |   **Category**  |                       **Info**                      |     **Deployment Status**    | **Latest Semver**
> |:--------------------------------------:|:---------------:|:---------------------------------------------------:|:----------------------------:|:----------------------:|
> |          [ArgoCD][argocd-uri]          |             `Git`    |      <sub>[More details][homelab-argocd]</sub>      |       ![][argocd-core]       | ![][argo-badge]        |
> |   [CertManager][service-certmanager] |               `Networking`   |  <sub>[More details][homelab-certmanager]</sub>    |  ![][argocd-certmanager] | ![][certmanager-badge]    |
> |   [Changedetection.io][change-uri]     |             `Services`   |       <sub>[More details][homelab-change]</sub>      |        ![][argocd-change]    |  ![][change-badge]   |
> | [External-DNS][service-externaldns] |               `Networking`   |  <sub>[More details][homelab-externaldns]</sub>    |  ![][argocd-externaldns] | ![][externaldns-badge]    |
> |     [Hashicorp's Vault][vault-uri]     |            `Security`   |       <sub>[Chart values][homelab-vault]</sub>      |       ![][argocd-vault]      |  ![][vault-badge]    |
> |      [Home Assistant][service-ha]      |            `Smart Home`   |        <sub>[More details][homelab-ha]</sub>        |        ![][argocd-ha]        |    ![][ha-badge]     |
> | [Kube-vip][kubevip-uri]            |            `Networking`  |      <sub>[More details][homelab-kubevip]</sub>      |      ![][argocd-kubevip]      | ![][kubevip-badge]    |
> |     [kube-prometheus][service-kube]    |            `Monitoring`  |  <sub>[More details][homelab-kube]</sub>            |       ![][argocd-kube]       |   ![][kube-badge]    |
> |          [Gitea][gitea-uri]          |             `GitOps`     |      <sub>[More details][homelab-gitea]</sub>      |       ![][argocd-gitea]       | ![][gitea-badge]        |
> |            [n8n][n8n-uri]              |            `Services`   |        <sub>[More details][homelab-n8n]</sub>       |        ![][argocd-n8n]       |  ![][n8n-badge]      |
> | [Redis Operator][redis-uri]            |            `Databases`   |       <sub>[More details][homelab-redis]</sub>      |       ![][argocd-redis]      |  ![][redis-badge]    |
> |    [Unifi Controller][unifi-uri]      |            `Networking`  |      <sub>[More details][homelab-unifi]</sub>      |      ![][argocd-unifi]      | ![][unifi-badge]    |
> | [Uptime Kuma][kuma-uri]            |            `Monitoring`  |      <sub>[More details][homelab-kuma]</sub>          |      ![][argocd-kuma]      | ![][kuma-badge]      |
> |     [Tailscale-operator][tail-uri]        |         `Networking`  | <sub>[More details][homelab-tailscale]</sub>         |    ![][argocd-tailscale]     |![][tailscale-badge]  |

<!-- >
> | [<sub>Zalando PostgreSQL Operator</sub>][p-uri] |   `Databases`   |      <sub>[More details][homelab-zalando]</sub>     |      ![][argocd-zalando]     | ![][zalando-badge]  |
> |           [Beets][service-beets]       |   `Media`       |  <sub>[More details][homelab-beets]</sub>           |       ![][argocd-beets]      |   ![][beets-badge]   |
> |           [Lidarr][service-lidarr]     |   `Media`       |  <sub>[More details][homelab-lidarr]</sub>          |  ![][argocd-lidarr]          |  ![][lidarr-badge]   |
> |    [Metabase][service-metabase]        |   `Analytics`   |       <sub>[More details][homelab-metabase]</sub>   |   ![][argocd-metabase]       | ![][metabase-badge] |
> |          [Agones][agones-uri]             |            `Services`   |        <sub>[More details][homelab-agones]</sub>    |        ![][argocd-agones]    |  ![][agones-badge]   |
> |       [Matrix Synapse][matrix-uri]     |    `Services`   |        <sub>[More details][homelab-matrix]</sub>    |        ![][argocd-matrix]    |  ![][matrix-badge]   |
> |         botdarr         |                    | `Utilities` |                   |                       |
> |    [Milvus][service-milvus]            |            `Databases`  |        <sub>[More details][homelab-milvus]</sub>    |        ![][argocd-milvus]   | ![][milvus-badge]    |
> | [Nvidia GPU Exporter][nvidia-exp-uri]  |   `Monitoring`  | <sub>[Chart values][homelab-gpu-exporter]</sub>     | ![][argocd-gpu-exporter]  | ![][gpu-exporter-badge] |
> |[<sub>Nvidia integration for k8s</sub>][nvidia-uri]|    `Driver`     |      <sub>[More details][homelab-nvidia]</sub>      |       ![][argocd-nvidia] | ![][nvidia-badge]  |
> |       [Jellyfin][service-jellyfin]     |   `Media`       |  <sub>[More details][homelab-jellyfin]</sub>        |  ![][argocd-jellyfin]        |  ![][jellyfin-badge]   |
> |           [Sonarr][service-sonarr]     |   `Media`       |  <sub>[More details][homelab-sonarr]</sub>          |  ![][argocd-sonarr]          |  ![][sonarr-badge]   |
> |       [Prowlarr][service-prowlarr]     |   `Media`       |  <sub>[More details][homelab-prowlarr]</sub>        |  ![][argocd-prowlarr]       |  ![][prowlarr-badge]   |
> |    [RSS Hub][service-rsshub]           |    `Services`   |        <sub>[More details][homelab-rsshub]</sub>    |        ![][argocd-rss-hub]   | ![][rsshub-badge]    |
> |    [Feedpushr][service-feedpushr]      |    `Services`   |        <sub>[More details][homelab-feedpushr]</sub>    |        ![][argocd-feedpushr]   | ![][feedpushr-badge]    |
> |   [Wallabag][wallabag-uri]             |   `Services`   |        <sub>[More details][homelab-wyze]</sub>      |        ![][argocd-wallabag]  |  ![][wallabag-badge] |
> |   [Wavy][wavy-uri]                     |   `Services`   |        <sub>[More details][homelab-wavy]</sub>      |        ![][argocd-wavy]       |  ![][wavy-badge] |
> |   [Grocy][grocy-uri]                   |   `Services`   |        <sub>[More details][homelab-grocy]</sub>      |        ![][argocd-grocy]  |  ![][grocy-badge] |
> | <sub>[ChatGPT Discord Bot][service-chatgpt]</sub> |  `Services`   |  <sub>[More details][homelab-chatgpt]</sub>    |  ![][argocd-chatgpt] | ![][chatgpt-badge]    |
> | <sub>[ChatGPT Retrieval Plugin][service-p-chatgpt]</sub> |  `Services`   |  <sub>[More details][homelab-p-chatgpt]</sub>    |  ![][argocd-p-chatgpt] | ![][chatgpt-p-badge]    |
> | [<sub>MongoDB Community Operator</sub>][service-mongo] | `Databases` | <sub>[More details][homelab-mongo]</sub> |       ![][argocd-mongo]     | ![][mongo-badge]     |

<-->

---

</details>

<details>

<summary> <b>Cluster Utilities</b>
</summary>

<br>

> - [argocd-image-updater][argocd-updater-uri] &nbsp; <sub>Automatically update a deployment's image version tag and write it back to a Github repository. [Example.][argocd-updater-ex]</sub>
> - [Reflector][reflector-uri] &nbsp; <sub>Replicate a `Secret` or `configMap` between namespaces automatically.</sub>
> - [Descheduler][descheduler-uri] &nbsp; <sub>Monitors if workloads are evenly distributed through nodes and cleans failed pods that remained as orphans/stuck.</sub>
> - [Eraser][eraser-uri] &nbsp; <sub>A daemonset responsible for cleaning up outdated images stored in the cluster nodes.</sub>
> - [Kube-fledged][kube-fledged-uri] &nbsp; <sub>Allows for image caching on every node in the cluster, in order to speed up deployments of already existing applications.</sub>
> - [Kured][kured-uri] &nbsp; <sub>All the cluster's nodes will be properly drained before rebooting cordoned back once they're online.</sub>
> - [Reloader][reloader-uri] &nbsp; <sub>Everytime a `configMap` or a `Secret` resource is created or changed, the pods that use them will be reloaded.</sub>
> - [Democratic-CSI][democratic-uri] &nbsp; <sub>[A CSI implementation][csi-uri] for multiple ZFS-based storage systems.</sub>
> - [node-problem-detector][node-problem-uri] &nbsp; <sub>Detects if a node has been affected by an issue such as faulty hardware or kernel deadlocks, preventing scheduling.</sub>
> - [Wavy][wavy-uri] &nbsp; <sub>Patches Kubernetes resources with a VNC access using annotations to provide a GUI to any container.</sub>

---

</details>

<details>

<summary> <b>Repository Stats</b> </summary>

<br>

![Alt](https://repobeats.axiom.co/api/embed/576d4457404c7c5ba81a07cecd2b440163eebd63.svg "Repobeats analytics image")

</details>

<!-- Misc -->
[csi-uri]: https://kubernetes-csi.github.io/docs/
<!-- Tech tools URIs -->

[drone-uri]: https://www.drone.io/
[crossplane-uri]: https://www.crossplane.io/
[nvidia-uri]: https://github.com/NVIDIA/k8s-device-plugin
[nfs-uri]: https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner
[argocd-uri]: https://argoproj.github.io/cd/
[homeassistant-uri]: https://www.home-assistant.io/
[adguard-uri]: https://adguard.com/en/adguard-home/overview.html
[kuma-uri]: https://github.com/louislam/uptime-kuma
[service-rssgen]: https://github.com/damoeb/rss-proxy
[service-rsshub]: https://github.com/DIYgod/RSSHub
[service-feedpushr]: https://github.com/ncarlier/feedpushr
[service-beets]: https://github.com/beetbox/beets
[service-lidarr]: https://github.com/Lidarr/Lidarr
[service-metabase]: https://www.metabase.com/
[service-mongo]: https://github.com/mongodb/mongodb-kubernetes-operator
[service-kube]: https://github.com/prometheus-operator/kube-prometheus
[service-ha]: https://www.home-assistant.io/
[change-uri]: https://github.com/dgtlmoon/changedetection.io/
[service-adguard]: https://adguard.com/en/adguard-home/overview.html
[service-unifi]: https://github.com/jacobalberty/unifi-docker
[service-chatgpt]: https://github.com/Zero6992/chatGPT-discord-bot
[service-p-chatgpt]: https://github.com/openai/chatgpt-retrieval-plugin
[service-milvus]: https://milvus.io/
[tail-uri]: https://tailscale.com/kb/1151/what-is-tailscale/
[matrix-uri]: https://matrix.org/
[service-n8n]: https://n8n.io/
[service-certmanager]: https://github.com/cert-manager/cert-manager
[service-externaldns]: https://github.com/kubernetes-sigs/external-dns
[service-wyze]: https://github.com/mrlt8/docker-wyze-bridge
[change-uri]: https://github.com/dgtlmoon/changedetection.io
[redis-uri]: https://github.com/spotahome/redis-operator
[redis-uri]: https://github.com/spotahome/redis-operator
[democratic-csi-uri]: https://longhorn.io/
[agones-uri]: https://github.com/googleforgames/agones
[n8n-uri]: https://n8n.io/
[vault-uri]: https://github.com/hashicorp/vault
[grocy-uri]: https://github.com/grocy/grocy
[flame-uri]: https://github.com/pawelmalak/flame
[kubevip-uri]: https://github.com/kube-vip/kube-vip
[wavy-uri]: https://github.com/wavyland/wavy
[unifi-uri]: https://github.com/jacobalberty/unifi-docker
[poller-uri]: https://github.com/unpoller/unpoller
[gitea-uri]: https://about.gitea.com
[cf-uri]: https://github.com/cloudflare/cloudflared
[service-sonarr]: https://github.com/Sonarr/Sonarr
[service-prowlarr]: https://github.com/Prowlarr/Prowlarr
[service-jellyfin]: https://github.com/jellyfin/jellyfin
[wallabag-uri]: https://github.com/wallabag/wallabag
[nvidia-exp-uri]: https://github.com/utkuozdemir/nvidia_gpu_exporter
[crossplane-uri]: https://github.com/crossplane/crossplane
[democratic-uri]: https://github.com/democratic-csi/democratic-csi

<!-- Cluster Utilities/Internal Tooling -->

[argocd-updater-ex]: https://github.com/gruberdev/homelab/commit/75c00de5eba89b9978ed241e67e638e4d838fae4
[argocd-updater-uri]: https://argocd-image-updater.readthedocs.io/en/stable/
[descheduler-uri]: https://github.com/kubernetes-sigs/descheduler
[kube-fledged-uri]: https://github.com/senthilrch/kube-fledged
[kured-uri]: https://github.com/kubereboot/charts/tree/main/charts/kured
[reflector-uri]: https://github.com/emberstack/kubernetes-reflector
[reloader-uri]: https://github.com/stakater/Reloader
[botkube-uri]: https://botkube.io/
[argocd-notifications-uri]: https://argocd-notifications.readthedocs.io/en/stable/
[node-problem-uri]: https://github.com/kubernetes/node-problem-detector
[feature-discovery-uri]: https://github.com/kubernetes-sigs/node-feature-discovery
[chaos-mesh-uri]: https://chaos-mesh.org/
[trivy-uri]: https://github.com/aquasecurity/trivy-operator
[eraser-uri]: https://github.com/azure/eraser
[wavy-uri]: https://github.com/wavyland/wavy

<!-- Project Folders -->

[homelab-argocd]: https://github.com/gruberdev/homelab/tree/main/apps/argocd
[homelab-drone]: https://github.com/gruberdev/homelab/tree/main/apps/drone
[homelab-ha]: https://github.com/gruberdev/homelab/tree/main/apps/home/ha
[homelab-wyze]: https://github.com/gruberdev/homelab/tree/main/apps/home/wyze
[homelab-nvidia]: https://github.com/gruberdev/homelab/blob/main/docs/nvidia.md
[homelab-nfs]: https://github.com/gruberdev/homelab/blob/main/apps/argocd/base/core/nfs.yaml
[homelab-kube]: https://github.com/gruberdev/homelab/tree/main/apps/monitoring/kube-prometheus
[homelab-kuma]: https://github.com/gruberdev/homelab/tree/main/apps/monitoring/uptime-kuma
[homelab-crossplane]: https://github.com/gruberdev/homelab/tree/main/apps/utilities/crossplane
[homelab-adguard]: https://github.com/gruberdev/homelab/tree/main/apps/networking/adguard
[homelab-mongo]: https://github.com/gruberdev/homelab/blob/main/apps/argocd/base/apps/mongodb.yaml
[homelab-wavy]: https://github.com/gruberdev/homelab/tree/main/apps/services/wavy
[homelab-unifi-controller]: https://github.com/gruberdev/homelab/tree/main/apps/networking/unifi/controller
[homelab-gitea]: https://github.com/gruberdev/homelab/blob/main/apps/argocd/base/services/gitea.yaml
[homelab-change]: https://github.com/gruberdev/homelab/tree/main/apps/services/changedetection
[homelab-redis]: https://github.com/gruberdev/homelab/tree/main/apps/data/redis
[homelab-grocy]: https://github.com/gruberdev/homelab/tree/main/apps/services/grocy
[homelab-mysql]: https://github.com/gruberdev/homelab/blob/main/docs/mysql.md
[homelab-tailscale]: https://github.com/gruberdev/homelab/tree/main/apps/networking/tailscale
[homelab-vault]: https://github.com/gruberdev/homelab/blob/main/apps/argocd/base/apps/vault.yaml
[homelab-matrix]: https://github.com/gruberdev/homelab/tree/main/apps/matrix
[homelab-n8n]: https://github.com/gruberdev/homelab/tree/main/apps/services/n8n
[homelab-flame]: https://github.com/gruberdev/homelab/tree/main/apps/monitoring/flame
[homelab-poller]: https://github.com/gruberdev/homelab/tree/main/apps/networking/unifi/poller
[homelab-cloudflared]: https://github.com/gruberdev/homelab/tree/main/apps/networking/cloudflared
[homelab-kubevip]: https://github.com/gruberdev/homelab/tree/main/apps/networking/kube-vip
[homelab-rssgen]: https://github.com/gruberdev/homelab/tree/main/apps/services/rss/gen
[homelab-chatgpt]: https://github.com/gruberdev/homelab/tree/main/apps/services/chatgpt/discord-bot
[homelab-sonarr]: https://github.com/gruberdev/homelab/tree/main/apps/services/media/sonarr
[homelab-prowlarr]: https://github.com/gruberdev/homelab/tree/main/apps/services/media/prowlarr
[homelab-rsshub]: https://github.com/gruberdev/homelab/tree/main/apps/services/rss/hub
[homelab-feedpushr]: https://github.com/gruberdev/homelab/tree/main/apps/services/rss/feedpushr
[homelab-beets]: https://github.com/gruberdev/homelab/tree/main/apps/services/media/beets
[homelab-lidarr]: https://github.com/gruberdev/homelab/tree/main/apps/services/media/lidarr
[homelab-metabase]: https://github.com/gruberdev/homelab/tree/main/apps/data/metabase
[homelab-certmanager]: https://github.com/gruberdev/homelab/tree/main/apps/networking/certmanager
[homelab-externaldns]: https://github.com/gruberdev/homelab/tree/main/apps/argocd/base/networking/external-dns
[homelab-jellyfin]: https://github.com/gruberdev/homelab/tree/main/apps/services/media/jellyfin
[homelab-agones]: https://github.com/gruberdev/homelab/tree/main/apps/services/agones
[homelab-gpu-exporter]: https://github.com/gruberdev/homelab/blob/main/apps/argocd/base/monitoring/nvidia.yaml
[homelab-unifi]: https://github.com/gruberdev/homelab/tree/main/apps/networking/unifi/controller

<!-- ArgoCD Status Badges -->

[argocd-kube]: https://argo.raptor-beta.ts.net/api/badge?name=kube-prometheus
[argocd-nvidia]: https://argo.raptor-beta.ts.net/api/badge?name=nvidia
[argocd-nfs]: https://argo.raptor-beta.ts.net/api/badge?name=nfs-provisioner
[argocd-crossplane]: https://argo.raptor-beta.ts.net/api/badge?name=crossplane
[argocd-ha]: https://argo.raptor-beta.ts.net/api/badge?name=homeassistant
[argocd-kuma]: https://argo.raptor-beta.ts.net/api/badge?name=uptime-kuma
[argocd-grocy]: https://argo.raptor-beta.ts.net/api/badge?name=grocy
[argocd-adguard]:https://argo.raptor-beta.ts.net/api/badge?name=adguard
[argocd-unifi-controller]: https://argo.raptor-beta.ts.net/api/badge?name=unifi-controller
[argocd-core]: https://argo.raptor-beta.ts.net/api/badge?name=argocd
[argocd-n8n]: https://argo.raptor-beta.ts.net/api/badge?name=n8n-service
[argocd-vault]: https://argo.raptor-beta.ts.net/api/badge?name=vault
[argocd-ha]: https://argo.raptor-beta.ts.net/api/badge?name=homeassistant
[argocd-wyze]: https://argo.raptor-beta.ts.net/api/badge?name=wyze
[argocd-redis]: https://argo.raptor-beta.ts.net/api/badge?name=redis
[argocd-matrix]: https://argo.raptor-beta.ts.net/api/badge?name=synapse
[argocd-mysql]: https://argo.raptor-beta.ts.net/api/badge?name=mysql-operator
[argocd-changedetection]: https://argo.raptor-beta.ts.net/api/badge?name=changedetection
[argocd-tailscale]: https://argo.raptor-beta.ts.net/api/badge?name=tailscale-operator
[argocd-chatgpt]: https://argo.raptor-beta.ts.net/api/badge?name=discord-bot-gpt
[argocd-gitea]: https://argo.raptor-beta.ts.net/api/badge?name=gitea
[argocd-p-chatgpt]: https://argo.raptor-beta.ts.net/api/badge?name=memory-plugin-gpt
[argocd-milvus]: https://argo.raptor-beta.ts.net/api/badge?name=milvus-operator
[argocd-mongo]: https://argo.raptor-beta.ts.net/api/badge?name=mongodb-operator
[argocd-wavy]: https://argo.raptor-beta.ts.net/api/badge?name=wavy
[argocd-poller]: https://argo.raptor-beta.ts.net/api/badge?name=unifi-poller
[argocd-rss-gen]: https://argo.raptor-beta.ts.net/api/badge?name=rss-gen
[argocd-rss-hub]: https://argo.raptor-beta.ts.net/api/badge?name=rss-hub
[argocd-feedpushr]: https://argo.raptor-beta.ts.net/api/badge?name=feedpushr
[argocd-change]: https://argo.raptor-beta.ts.net/api/badge?name=changedetection
[argocd-beets]: https://argo.raptor-beta.ts.net/api/badge?name=beets
[argocd-lidarr]: https://argo.raptor-beta.ts.net/api/badge?name=lidarr
[argocd-metabase]: https://argo.raptor-beta.ts.net/api/badge?name=metabase
[argocd-kubevip]: https://argo.raptor-beta.ts.net/api/badge?name=kubevip
[argocd-prowlarr]: https://argo.raptor-beta.ts.net/api/badge?name=prowlarr
[argocd-sonarr]: https://argo.raptor-beta.ts.net/api/badge?name=sonarr
[argocd-jellyfin]: https://argo.raptor-beta.ts.net/api/badge?name=jellyfin
[argocd-wallabag]: https://argo.raptor-beta.ts.net/api/badge?name=wallabag
[argocd-crossplane]: https://argo.raptor-beta.ts.net/api/badge?name=crossplane
[argocd-tailscale]: https://argo.raptor-beta.ts.net/api/badge?name=tailscale-operator
[argocd-agones]: https://argo.raptor-beta.ts.net/api/badge?name=agones
[argocd-gpu-exporter]: https://argo.raptor-beta.ts.net/api/badge?name=nvidia-exporter
[argocd-externaldns]: https://argo.raptor-beta.ts.net/api/badge?name=external-dns-cloudflare
[argocd-certmanager]: https://argo.raptor-beta.ts.net/api/badge?name=certmanager
[argocd-unifi]: https://argo.raptor-beta.ts.net/api/badge?name=unifi-controller

<!-- Badge Images -->

[argo-badge]: https://img.shields.io/github/v/release/argoproj/argo-cd?label=Github&logo=github&style=flat-square
[gitea-badge]: https://img.shields.io/github/v/release/go-gitea/gitea?label=Github&logo=github&style=flat-square
[kubevip-badge]: https://img.shields.io/github/v/release/kube-vip/kube-vip?label=Github&logo=github&style=flat-square
[kube-badge]: https://img.shields.io/github/v/release/prometheus-operator/kube-prometheus?label=Github&logo=github&style=flat-square
[democratic-csi-badge]: https://img.shields.io/github/v/tag/longhorn/longhorn?label=Github&logo=github&style=flat-square
[redis-badge]: https://img.shields.io/github/v/tag/spotahome/redis-operator?label=Github&logo=github&style=flat-square
[tailscale-badge]: https://img.shields.io/github/v/release/tailscale/tailscale?label=Github&logo=github&style=flat-square
[nvidia-badge]: https://img.shields.io/github/v/release/NVIDIA/k8s-device-plugin?label=Github&logo=github&style=flat-square
[unifi-badge]: https://img.shields.io/github/v/release/jacobalberty/unifi-docker?label=Github&logo=github&style=flat-square
[adguard-badge]: https://img.shields.io/docker/v/adguard/adguardhome?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[ha-badge]: https://img.shields.io/github/v/release/home-assistant/core?label=Github&logo=github&style=flat-square
[wyze-badge]: https://img.shields.io/github/v/release/mrlt8/docker-wyze-bridge?label=Github&logo=github&style=flat-square
[change-badge]: https://img.shields.io/github/v/release/dgtlmoon/changedetection.io?label=Github&logo=github&style=flat-square
[grocy-badge]: https://img.shields.io/github/v/release/grocy/grocy?label=Github&logo=github&style=flat-square
[n8n-badge]: https://img.shields.io/docker/v/n8nio/n8n?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[vault-badge]: https://img.shields.io/github/v/release/hashicorp/vault?label=Github&logo=github&style=flat-square
[flame-badge]: https://img.shields.io/github/v/release/pawelmalak/flame?label=Github&logo=github&sort=semver&style=flat-square
[poller-badge]: https://img.shields.io/github/v/release/unpoller/unpoller?label=Github&logo=github&sort=semver&style=flat-square
[cfd-badge]: https://img.shields.io/docker/v/erisamoe/cloudflared?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[rssgen-badge]: https://img.shields.io/github/v/tag/damoeb/rss-proxy?label=Github&logo=github&style=flat-square
[nfs-badge]: https://img.shields.io/github/v/tag/kubernetes-sigs/nfs-subdir-external-provisioner?label=Github&logo=github&style=flat-square
[matrix-badge]: https://img.shields.io/github/v/release/matrix-org/synapse?label=Github&logo=github&style=flat-square
[crossplane-badge]: https://img.shields.io/github/v/release/crossplane/crossplane?label=Github&logo=github&style=flat-square
[prowlarr-badge]: https://img.shields.io/github/v/release/Prowlarr/Prowlarr?label=Github&logo=github&style=flat-square
[sonarr-badge]: https://img.shields.io/github/v/release/linuxserver/docker-sonarr?label=Github&logo=github&style=flat-square
[beets-badge]: https://img.shields.io/github/v/tag/beetbox/beets?label=Github&logo=github&style=flat-square
[lidarr-badge]: https://img.shields.io/github/v/release/lidarr/lidarr?label=Github&color=blue&logo=github&sort=semver&style=flat-square
[crossplane-badge]: https://img.shields.io/github/v/release/crossplane/crossplane?label=Github&color=blue&logo=github&sort=semver&style=flat-square
[metabase-badge]: https://img.shields.io/docker/v/metabase/metabase?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[wallabag-badge]: https://img.shields.io/docker/v/wallabag/wallabag?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[rsshub-badge]: https://img.shields.io/static/v1?label=No&message=version%20provided&color=gray&labelColor=gray&style=flat-square
[feedpushr-badge]: https://img.shields.io/github/v/release/ncarlier/feedpushr?label=Github&color=blue&logo=github&sort=semver&style=flat-square
[jellyfin-badge]: https://img.shields.io/github/v/release/jellyfin/jellyfin?label=Github&logo=github&style=flat-square
[agones-badge]: https://img.shields.io/github/v/release/googleforgames/agones?label=Github&color=blue&logo=github&sort=semver&style=flat-square
[gpu-exporter-badge]: https://img.shields.io/github/v/release/utkuozdemir/nvidia_gpu_exporter?label=Github&logo=github&style=flat-square
[kuma-badge]: https://img.shields.io/github/v/release/louislam/uptime-kuma?label=Github&logo=github&style=flat-square
[chatgpt-badge]: https://img.shields.io/github/v/tag/Zero6992/chatGPT-discord-bot?label=Github&logo=github&style=flat-square
[chatgpt-p-badge]: https://img.shields.io/docker/v/grubertech/chatgpt-plugin?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[milvus-badge]: https://img.shields.io/docker/v/milvusdb/milvus?label=Docker&color=blue&logo=docker&sort=semver&style=flat-square
[wavy-badge]: https://img.shields.io/static/v1?label=No&message=version%20provided&color=gray&labelColor=gray&style=flat-square
[mongo-badge]: https://img.shields.io/github/v/tag/mongodb/mongodb-kubernetes-operator?label=Github&logo=github&style=flat-square
[certmanager-badge]: https://img.shields.io/github/v/release/cert-manager/cert-manager?label=Github&logo=github&style=flat-square
[externaldns-badge]: https://img.shields.io/github/v/release/kubernetes-sigs/external-dns?label=Github&logo=github&style=flat-square
