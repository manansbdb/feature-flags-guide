<p align="center">
  <img src="docs/banner.svg" alt="Feature Flags Guide banner" width="100%" />
</p>

<h1 align="center">feature-flags-guide</h1>

<p align="center">
  <strong>EN</strong> Feature-flag patterns & rollout checklist<br/>
  <strong>PT</strong> Padrões de feature flags e checklist de rollout
</p>

<p align="center">
  <a href="https://github.com/manansbdb/feature-flags-guide/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-feature--flags-a855f7?style=for-the-badge" alt="feature-flags" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Patterns for **feature flags** (boolean, percentage, targeting) plus a rollout checklist. | Padrões de **feature flags** (boolean, percentagem, targeting) e checklist de rollout. |
| Adopt before shipping risky changes behind a toggle. | Adota antes de publicar mudanças arriscadas atrás de um toggle. |

```mermaid
flowchart LR
  A["🚩 Flag define"] --> B["🧪 % rollout"]
  B --> C["📊 Observe"]
  C --> D["✅ Full on / ⏪ Off"]
  style A fill:#9333ea,stroke:#6b21a8,color:#fff
  style B fill:#2563eb,stroke:#1d4ed8,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/feature-flags-guide.git
cd feature-flags-guide
```

### 2) Copy / Copia

```bash
mkdir -p docs/feature-flags
cp patterns.md docs/feature-flags/
cp checklist.md docs/feature-flags/
```

### Requirements / Requisitos

- `git`
- Optional: self-hosted Unleash, GrowthBook, or a homemade flag store (no paid SaaS required)

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/feature-flags-guide.git
# read patterns.md → use checklist.md on every risky release
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `patterns.md` | Flag strategies |
| `checklist.md` | Rollout checklist |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
feature-flags-guide/
├── docs/banner.svg
├── patterns.md
├── checklist.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
