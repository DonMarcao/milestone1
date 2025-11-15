# 🚀 Deployment Guide - ABI Insight

This guide details the steps required to deploy the ABI Insight website using GitHub Pages, assuming the main branch contains the final production-ready files.

---

## 1. Prerequisites

* All project code must be pushed to the main branch on GitHub.
* A stable, working version of the website must be confirmed via local testing (Commit 60).

## 2. GitHub Pages Deployment Steps

### A. Access Repository Settings
1.  Navigate to the project repository on GitHub.
2.  Click the 'Settings' tab.
3.  In the left sidebar, select 'Pages' (under Code and automation).

### B. Configure Source
1.  Under the 'Source' heading, set the 'Branch' dropdown to `main`.
2.  Ensure the folder is set to `/(root)`.
3.  Click 'Save'.

### C. Wait for Build
1.  GitHub Actions will automatically trigger a build process. You can monitor the progress under the 'Actions' tab.
2.  Once the build is complete, GitHub Pages will provide the live URL (e.g., `https://[username].github.io/abi-insight-final/`).

## 3. Post-Deployment QA

* Verify the site loads correctly on the public URL.
* Test all internal and external links.
* Test responsiveness on a live mobile device.