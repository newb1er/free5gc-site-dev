<!-- Google tag (gtag.js) --> <script async src="https://www.googletagmanager.com/gtag/js?id=G-JETJ7TJ805"></script> <script> window.dataLayer = window.dataLayer || []; function gtag(){dataLayer.push(arguments);} gtag('js', new Date()); gtag('config', 'G-JETJ7TJ805'); </script>

# User Guide

## Information

- [Hardware tested](./hardware.md)
- [Supported features](./features.md)

## Roadmap

Here are the features on the roadmap. These items are planned to be supported in the near future:

* Charging Function (CHF)
* OAuth on SBA
* Session AMBR in Data Plane
* Network Exposure Function (NEF)

If you're interested in more details, please visit the [GitHub Dashboard](https://github.com/users/ianchen0119/projects/4/views/5)

## free5GC Installation Guide

>[!NOTE]
> If you have to develop a new feature on free5GC, please check the links below to install the free5GC.
> Otherwise, for normal use/test purposes, we recommend you use the [free5GC Compose](https://github.com/free5gc/free5gc-compose) to launch the free5GC without complicated configuration settings.

### [Recommended] free5GC compose
- [Installing free5GC Core Network with free5GC-Compose](./0-compose.md)

### [Advanced] Build free5GC from scratch

For people who are not familiar with virtual machines and Linux installation, here are some example demonstrations:

- [Creating a Ubuntu VM using VirtualBox](./1-vm-en.md)
- [Creating and Configuring a free5GC VM](./2-config-vm-en.md)
- [Build and Install free5GC](./3-install-free5gc.md) from source code and [Test](./4-test-free5gc.md) free5GC
- [Installing a UE/RAN Simulator](./5-install-ueransim.md)
- [free5GC Simple Apps](./6-simple-app.md)
- All of tutorial videos are available at our Youtube channel:
    - [English](https://www.youtube.com/watch?v=R-9vH_6VJ2Q&list=PLeDUIabcS2_rQd3yVJrBAYb-MbcqNgjC9)
    - [Chinese](https://www.youtube.com/watch?v=lD5iYvCB4CQ&list=PLeDUIabcS2_pdhCN3sz5gFdT-mTukyX-v)
    - [Environment setup of multiple SMF, DNN, and UPF](https://www.youtube.com/watch?v=AEMrjKRWarw)

## Configuration
- [Environment](./Environment.md)
- [Basic](./Configuration.md)
- [SMF](./SMF-Config.md)
- [Webconsole](./Webconsole/Create-Subscriber-via-webconsole.md)
- [Select UPF based on S-NSSAI](https://github.com/s5uishida/free5gc_ueransim_snssai_upf_sample_config)
- [Select nearby UPF according to the connected gNodeB](https://github.com/s5uishida/free5gc_ueransim_nearby_upf_sample_config)
- [ULCL](https://github.com/s5uishida/free5gc_ueransim_ulcl_sample_config)
- [Netns5g - A free5gc and UERANSIM deployment using Linux network namespaces](https://github.com/konradkar2/netns5g)

## Deployment

For Container deployment:

- [free5GC Compose](https://github.com/free5gc/free5gc-compose) (Docker Compose)
- [Towards5gs-helm](https://github.com/Orange-OpenSource/towards5gs-helm) (Kubernetes)

## Others
- [Release Note](https://github.com/free5gc/free5gc/releases)
- [Trouble Shooting](./Trouble_Shooting.md)
- [Appendix](./Appendix.md)
