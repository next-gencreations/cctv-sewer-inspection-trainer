# Upload the full course (index.html)

The complete interactive course is a single ~62 KB file.

## Option A — GitHub website (easiest)

1. Open: https://github.com/next-gencreations/cctv-sewer-inspection-trainer
2. Click **Add file → Upload files**
3. Upload `index.html` from your local copy:
   - Path on the build machine: `/home/workdir/artifacts/cctv-simulator/index.html`
   - Or download the zip from the conversation artifacts: `cctv-course.zip`
4. Commit directly to `main`

## Option B — Command line

```bash
cd /path/to/your/copy
git clone https://github.com/next-gencreations/cctv-sewer-inspection-trainer.git
cp /path/to/index.html cctv-sewer-inspection-trainer/
cd cctv-sewer-inspection-trainer
git add index.html
git commit -m "Add full MSCC 5 CCTV training course"
git push
```

## After upload

Open `index.html` in any browser, or enable **Settings → Pages** for a live URL:
https://next-gencreations.github.io/cctv-sewer-inspection-trainer/
