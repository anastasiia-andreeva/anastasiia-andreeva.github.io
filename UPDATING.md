# Updating this site

You can make every change below directly on GitHub, in the browser — no software to install. Go to the repository, click the file you want, click the pencil icon to edit, then scroll down and click "Commit changes." The live site updates automatically about 2 minutes after you commit.

## Add a new paper

Open `data/papers.yaml` and add a new entry at the bottom, following the pattern of the existing ones:

```yaml
- title: "Your Paper Title"
  authors: ["Anastasiia Andreeva", "Coauthor Name"]
  year: 2027
  status: "working paper"   # or "under review", "revise and resubmit", "published"
  venue: ""                  # journal name, once published
  pdf: "files/your-paper.pdf" # if you're hosting the PDF yourself
  link: ""                   # external link (journal, SSRN, etc.)
  abstract: ""
  job_market_paper: false
  tags: ["your", "keywords"]
```

If you're attaching a PDF, upload it to `static/files/` first, then reference it as `files/your-paper.pdf`.

## Mark a paper as published

In `data/papers.yaml`, change that paper's `status` to `"published"` and fill in `venue` and `link`.

## Set your job market paper

Set `job_market_paper: true` on that entry in `data/papers.yaml`. It will automatically get the highlighted card treatment at the top of the Research section.

## Update your bio

Edit `content/_index.md`. The text at the bottom of the file (below the `---` divider) is your bio. The `education` and `experience` lists near the top of that same file are what populate the "About" section's two columns.

## Add a teaching entry

Open `data/teaching.yaml` and add a new entry following the existing pattern.

## Update your CV

Replace `static/files/cv.pdf` with your new file — keep the filename `cv.pdf` so the "CV" link in the nav keeps working.

## Change your photo

Replace `static/images/photo.jpg` with a new image — keep the filename `photo.jpg`.

## Add an award or fellowship

Edit `data/awards.yaml`.

## Add a talk or presentation

Edit `data/presentations.yaml`.
