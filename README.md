# CZ-DPF-Paper

Minimal project page for:

**DPF: Differentiable Polyphase Filtering for Large-Kernel Approximation**

## Website

The public project page is:

https://huakaifugui2.github.io/CZ-DPF-Paper/

The page is served by GitHub Pages from this repository.

## Paper PDF

The full paper PDF is stored in this repository at:

```text
static/pdfs/dpf-paper.pdf
```

The public PDF URL is:

https://huakaifugui2.github.io/CZ-DPF-Paper/static/pdfs/dpf-paper.pdf

The `Paper` button in `index.html` points to that full PDF.

## Local Files

Local repository path:

```text
E:\Paper_Web\CZ-DPF-Paper
```

Main files:

```text
index.html                  # project page
static/pdfs/dpf-paper.pdf   # full paper PDF
```

## Update And Publish

After editing `index.html` or replacing the PDF, publish changes with:

```powershell
cd E:\Paper_Web\CZ-DPF-Paper
git status
git add index.html static/pdfs/dpf-paper.pdf
git commit -m "Update project page"
git push
```

GitHub Pages can take a few minutes to refresh after pushing.

## GitHub Pages Settings

In the GitHub repository, use:

```text
Settings -> Pages
Source: Deploy from a branch
Branch: main
Folder: /root
```

## Notes

- Keep this repository public if the website and PDF should be publicly accessible.
- The current PDF is about 45 MB, so loading speed depends on GitHub Pages/CDN and the visitor's network.
- For faster full-paper downloads, host the PDF on a stronger file server such as arXiv, ACM DL, a university server, or another CDN-backed storage service, then update the `Paper` link in `index.html`.

## Template Credit

This page was originally based on the Academic Project Page Template:

https://github.com/eliahuhorwitz/Academic-project-page-template
