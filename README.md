# Monitoring Setup Project

This Ansible project will help us implement a monitoring setup for an organization using open source tools like Prometheus, Node Exporter, Grafana, Alertmanager, etc.

## Steps:
1. Install Prometheus on the target system.
2. Install Grafana on the target system.
3. Install Node Exporter for exposing system data.
4. Install Alertmanager for sending alerts to PagerDuty, Slack, Google Teams, etc.
5. Create all components as services to facilitate easy start, stop, and management.