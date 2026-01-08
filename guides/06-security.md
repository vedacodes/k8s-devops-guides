# Kubernetes Security Best Practices

Essentials:
- Use RBAC least privilege, enable audit logging.
- Network policies to restrict pod-to-pod traffic.
- Image provenance: sign images, use admission controllers to block untrusted images.
- Secrets: use sealed-secrets or external secret stores (Vault, AWS Secrets Manager).
