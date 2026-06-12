<div align="center">

<!-- Animated header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f62fe,100:00b4d8&height=200&section=header&text=Hey,%20I'm%20[TonPrénom]%20👋&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Junior%20DevOps%20Engineer&descAlignY=58&descSize=20" width="100%"/>

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00B4D8&center=true&vCenter=true&width=600&lines=Infrastructure+as+Code+enthusiast+%F0%9F%9B%A0%EF%B8%8F;CI%2FCD+pipeline+builder+%F0%9F%94%84;Go+%26+TypeScript+developer+%F0%9F%90%B9;Always+learning%2C+always+shipping+%F0%9F%9A%80" alt="Typing SVG" />
</a>

</div>

---

## 🧑‍💻 À propos de moi

```yaml
name: "[TonPrénom TonNom]"
role: "Junior DevOps Engineer"
location: "France 🇫🇷"
currently_learning: ["Kubernetes", "Terraform", "GitOps"]
interests:
  - Automatisation & CI/CD
  - Infrastructure as Code
  - Conteneurisation & orchestration
  - Developer Experience (DX)
quote: "Ship fast, fail safe, learn always."
```

---

## 🛠️ Stack & Outils

### Langages
<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
</p>

### DevOps & Cloud
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
</p>

---

## 🚀 Projet phare

### 🔧 [quota-operator](https://github.com/MaloLelandais/quota-operator)

[![E2E Tests](https://github.com/MaloLelandais/quota-operator/actions/workflows/test-e2e.yml/badge.svg)](https://github.com/MaloLelandais/quota-operator/actions/workflows/test-e2e.yml)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

Un **opérateur Kubernetes** qui gère automatiquement les `ResourceQuota` des namespaces en fonction d'une simple annotation.

```bash
kubectl annotate namespace my-namespace quota-operator/tier=small
```

L'opérateur réconcilie en continu : si le tier change, le quota est mis à jour automatiquement.

**Points clés :**
- 🎯 CRD custom (`NamespaceQuotaPolicy`) pour définir des tiers de quotas configurables
- 📊 Métriques Prometheus exposées (`:8080/metrics`) + dashboard Grafana intégré
- ✅ Tests E2E avec `kind`, CI/CD via GitHub Actions
- 📦 Packagé en Helm chart, basé sur `controller-runtime` & `kubebuilder`
- 🐳 Containerisé (Docker)

➡️ [Voir le projet complet](https://github.com/MaloLelandais/quota-operator)

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=TON_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=0f62fe&text_color=ffffff" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TON_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00b4d8&text_color=ffffff" height="165"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=TON_USERNAME&theme=tokyonight&hide_border=true&background=0d1117&stroke=00b4d8&ring=0f62fe&fire=00b4d8&currStreakLabel=ffffff" width="500"/>

</div>

---

## 📬 Me contacter

<p>
  <a href="https://linkedin.com/in/TON_LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:TON_EMAIL">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://TON_PORTFOLIO">
    <img src="https://img.shields.io/badge/Portfolio-0f62fe?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
</p>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,100:0f62fe&height=100&section=footer" width="100%"/>
</div>