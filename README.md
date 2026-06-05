# Kubernetes Manifests for Netology DevOps Diploma

Этот репозиторий содержит конфигурационные файлы для развёртывания:
- Мониторинга (Prometheus + Grafana + Alertmanager)
- Тестового приложения (Nginx)
- Ingress-контроллера

## Структура
- `monitoring/` — Helm values для kube-prometheus-stack
- `app/` — Deployment и Service для тестового приложения
- `ingress/` — Ingress-ресурсы для доступа на 80 порту
