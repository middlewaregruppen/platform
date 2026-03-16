# Copilot Instructions

## Kubernetes Cluster Interaction

- Never use `kubectl` to interact with Kubernetes clusters.
- Always use the **Flux Operator MCP** tools for all cluster operations including:
  getting resources, reading logs, applying manifests, and debugging.
