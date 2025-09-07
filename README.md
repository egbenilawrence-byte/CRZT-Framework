├─ k8s/           → manifests (kind config, rbac, netpol, attacker, gatekeeper)  
├─ services/      → inference_service.py, controller.py, model_train.py  
├─ docker/        → Dockerfiles for inference + controller  
├─ dashboards/    → Grafana JSON configs  
├─ datasets/      → (place external NB15/CICIDS/preprocessed logs)  
└─ docs/          → PDF / Thesis report  
mkdir CRZT-Framework && cd CRZT-Framework
nano README.md
git init
git add .
git commit -m "initial CRZT Framework commit"
git branch -M main
git remote add origin https://github.com/egbenilawrence-byte/CRZT-Framework.git
git push -u origin main
