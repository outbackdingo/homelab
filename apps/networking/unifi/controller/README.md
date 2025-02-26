<p align="center">
  <img width="350" height="250" src="https://www.logo.wine/a/logo/Ubiquiti_Networks/Ubiquiti_Networks-Logo.wine.svg" />
  <br />
  <a href="https://hub.docker.com/r/jacobalberty/unifi/tags">
    <img src="https://img.shields.io/github/v/release/jacobalberty/unifi-docker?label=Latest%20Version&logo=github&style=for-the-badge" />
  </a>
  <br />
  <a href="https://argo.raptor-beta.ts.net/applications/unifi-controller">
    <img src="https://argo.raptor-beta.ts.net/api/badge?name=unifi-controller&revision=true" alt="ArgoCD Status Badge" />
  </a>
</p>

### Reasons I chose Unifi as my local network hardware provider
> - Centralized network management: The Unifi Controller simplifies network management by providing a centralized platform for monitoring, configuring, and controlling Unifi devices. This is especially advantageous for users managing multiple network locations or larger networks with numerous devices.
> - Integration with Terraform: In addition to the controller's user interface, I can leverage a [Terraform module][terraform-uri] to manage all my devices and configurations using infrastructure-as-code. This allows me to maintain centralized control over both the cluster running my applications and the underlying physical network from one location.
> - Affordability: Enterprise-grade hardware typically outperforms consumer-grade alternatives, resulting in faster data transfer speeds, improved coverage, and more reliable connections, ensuring a seamless network experience for users. Unifi offers affordable, enterprise-grade devices that are readily available in my country.

## Additional resources

- [Website][website-uri]
- [Homelab's Unifi module Terraform code][homelab-terraform]
- [Controller's docker image Github repo][docker-uri]

### Instructions for deployment

```bash
kubectl apply -k github.com/gruberdev/homelab/apps/networking/unifi/controller
```

[website-uri]: https://www.ui.com/
[docker-uri]: https://github.com/jacobalberty/unifi-docker
[terraform-uri]: https://registry.terraform.io/providers/paultyng/unifi/latest/docs
[homelab-terraform]: https://github.com/gruberdev/homelab/tree/main/terraform/modules/unifi
