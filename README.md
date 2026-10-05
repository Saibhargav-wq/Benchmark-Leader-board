# AD Model Benchmark

Sortable benchmark table for autonomous driving models.

## Deploy to GitHub Pages (free hosting)

```bash
# 1. Create a new repo on GitHub: e.g. "ad-benchmark"
# 2. From this folder:
cd /data1/work/j0986861/benchmark-site
git init
git add index.html data.json
git commit -m "Initial benchmark"
git remote add origin https://github.com/<YOUR_USERNAME>/ad-benchmark.git
git push -u origin main

# 3. Go to repo Settings → Pages → Source: "main branch / root"
# 4. Site live at: https://<YOUR_USERNAME>.github.io/ad-benchmark/
```

## Add a new model

Edit `data.json` — add one entry to the `models` array, push.
Set `null` for unknown values. The table handles it automatically.
