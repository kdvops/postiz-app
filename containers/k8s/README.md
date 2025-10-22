# Postiz SaaS Deployment (K3s)

Este despliegue instala Postiz completo en tu clúster K3s como servicio SaaS multiusuario.

## Componentes
- PostgreSQL (StatefulSet con PVC)
- Redis (Deployment)
- Postiz App (Deployment)
- Ingress con Traefik

## Despliegue
```bash
kubectl apply -f postiz-deploy/
