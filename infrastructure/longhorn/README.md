# Longhorn Storage

Distributed block storage for Kubernetes.

## Access Longhorn UI

The UI is available internally. To access it:

```bash
kubectl port-forward -n longhorn-system svc/longhorn-frontend 8080:80
```

Then open: http://localhost:8080

## Storage Class
- Name: longhorn
- Default: yes
- Replicas: 3 (when multiple nodes available)
