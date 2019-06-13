# ovirt-vm-monitoring

Deploy Prometheus/Alertmanager with file based VM service discovery for RHEV, using `igou/ovirt-vm-prometheus-bridge`

This repository is scoped to ovirt/rhev, but can be modified to fit other platforms. In the provided template it assumes port 9100 to discover node-exporter endpoints.

To-do: Add additional configuration to `engine-vars.yml` to easily support TLS, multiple services, etc. 
