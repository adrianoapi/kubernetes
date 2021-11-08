# Configuração

## Subir a máquina de Nginx
```bash
kubectl apply -f .\svc-primeiro-pod.yaml
```

## Subir a máquina de MySQL
```bash
kubectl apply -f .\svc-mysqldb.yaml
```

## Exibir estado das máquinas
```bash
kubectl get all
```