## argocd-apps
```
📦 main-repo 1: argocd
└── 📂 clusters/
    └── 📂 stage/
        └── 📂 apps/
            └── 📄 simple-app.yaml     # vaules here

──────────────────────────────────────────────────────────────────────────────────────────

📦 repo with apps 2: argocd-apps
└── 📂 apps/
    └── 📂 lib/                        # apps here
        └── 📂 simple-app/             
            ├── 📄 Chart.yaml
            │   📄 values.yaml
            │   📄 custom-res.yaml # custom YAML-manifests (ConfigMap, ingresses etc)
```
