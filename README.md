## argocd-apps
```
📦 РЕПОЗИТОРИЙ 1: argocd-infra (Инфраструктурный)
└── 📂 clusters/
    └── 📂 stage/
        └── 📂 apps/
            └── 📄 simple-app.yaml     # Здесь задаются только values для конкретного кластера.

──────────────────────────────────────────────────────────────────────────────────────────

📦 РЕПОЗИТОРИЙ 2: argocd-apps (Прикладной)
└── 📂 apps/
    └── 📂 lib/
        └── 📂 simple-app/             # Папка приложения
            ├── 📄 Chart.yaml
            ├── 📂 values/             # Базовые дефолтные values для приложения
            │   └── 📄 values.yaml
            └── 📂 templates/
                └── 📄 custom-res.yaml # Кастомные YAML-манифесты (ConfigMap, Ингрессы)
```
