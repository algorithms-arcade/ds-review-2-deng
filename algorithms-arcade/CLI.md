---
layout: default
---
![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg)

# Code signal Arcade



```
rm -rf ds-review-1-chenyue
rm -rf ds-review-2-deng
rm -rf javascript-algorithms-and-data-structures
rm .gitmodules
rm -rf .git
git init
git branch -M main
git remote add origin https://github.com/algorithms-arcade/algorithms-arcade.git
git submodule add https://github.com/algorithms-arcade/ds-review-1-chenyue.git
git submodule add https://github.com/algorithms-arcade/ds-review-2-deng.git
git submodule add https://github.com/algorithms-arcade/javascript-algorithms-and-data-structures.git
git add .
git commit -m 'first commit'
git push --set-upstream origin main --force
```

