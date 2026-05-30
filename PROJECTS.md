# Project Repositories

All repositories for the yshop / ice-polar ecosystem.

## Repository List

| Repository | Platform | URL | Branch |
|-----------|----------|-----|--------|
| `yshop-drink` | Gitee | `https://gitee.com/icepolar/yshop-drink.git` | `V2` |
| `yshop-drink-vue` | Gitee | `https://gitee.com/icepolar/yshop-drink-vue.git` | `master` |
| `icepolarminiapp` | Gitee | `https://gitee.com/icepolar/icepolarminiapp.git` | `main` |
| `ice-polar-governance` | GitHub | `https://github.com/maydaygjw/ice-polar-governance.git` | `main` |

## Quick Clone

```bash
#!/bin/bash
# clone-all.sh — Clone all project repositories

BASE_DIR="${1:-.}"
mkdir -p "$BASE_DIR"
cd "$BASE_DIR"

git clone -b V2     https://gitee.com/icepolar/yshop-drink.git
git clone -b master https://gitee.com/icepolar/yshop-drink-vue.git
git clone -b main   https://gitee.com/icepolar/icepolarminiapp.git
git clone -b main   https://github.com/maydaygjw/ice-polar-governance.git

echo "All repositories cloned to $(pwd)"
```

## Directory Layout After Clone

```
yshop-team/
├── yshop-drink/          ← Java Spring Boot backend
├── yshop-drink-vue/      ← Vue3 admin dashboard
├── icepolarminiapp/      ← Native WeChat Mini Program
└── governance/           ← AI team knowledge center (this repo)
```
