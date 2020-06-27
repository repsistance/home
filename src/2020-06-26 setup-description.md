# Setup Description

* we run on k8s to easily scale up/be resilient and highly available
* we use remote block storage to ensure failing disks are not a problem
* we build from nixos source to ensure we run untainted software (no github, no hydra)
* we use an anti-ddos to protect our relays
