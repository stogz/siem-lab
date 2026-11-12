# SIEM DEMO
by Sam Stogsdill

### Lab Setup and Build
I built an isolated lab on KVM with a NAT network (10.10.10.0/24). An Ubuntu Server VM at 10.10.10.10 runs the Elastic Stack (Elasticsearch + Kibana) as the SIEM. A Windows endpoint ships logs to it through Elastic Agent and Sysmon, and a Kali VM generates attack activity so I can build and test detections.
