# Shanthan K Portfolio — GitHub Pages

This is a static portfolio website for **Shanthan K**.

GitHub username already configured:

`shanthan97`

GitHub profile link:

`https://github.com/shanthan97`

## Before you publish

Open `index.html` and replace these two placeholders:

- `YOUR_LINKEDIN_USERNAME`
- `shanthankothuru@gmail.com`

The portfolio already includes:

- SLK America
- Fifth Third Bank client engagement
- FR 2052a regulatory reporting
- Treasury Management Billing modernization
- Loan consolidation data product
- DataNav analytics
- Cloud ingestion framework
- Commercial-loan semantic layer
- Snowflake
- dbt
- Python
- SQL
- Airflow
- AWS
- GCP
- Databricks
- DataStage
- Power BI
- PostgreSQL
- Docker
- Kubernetes
- Terraform
- data governance and lineage

## Preview locally

You can simply double-click:

`index.html`

or open the folder in VS Code and use the **Live Server** extension.

---

# Host it on GitHub Pages

## Recommended repository name

Because your username is `shanthan97`, create this repository:

`shanthan97.github.io`

Your final website URL will then be:

`https://shanthan97.github.io`

## Option A — easiest: GitHub website

1. Log into GitHub.
2. Click **New repository**.
3. Repository name: `shanthan97.github.io`
4. Set it to **Public**.
5. Create the repository.
6. Click **Add file → Upload files**.
7. Upload:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `.nojekyll`
   - `assets` folder
8. Commit the files.
9. Open **Settings → Pages**.
10. Under **Build and deployment** choose:
    - Source: `Deploy from a branch`
    - Branch: `main`
    - Folder: `/ (root)`
11. Click **Save**.

After GitHub deploys it, visit:

`https://shanthan97.github.io`

## Option B — Git command line

```bash
git init
git add .
git commit -m "Launch Shanthan portfolio"
git branch -M main
git remote add origin https://github.com/shanthan97/shanthan97.github.io.git
git push -u origin main
```

Then enable Pages from:

`Settings → Pages → Deploy from a branch → main → / (root)`

---

# Customize

## LinkedIn

Search for:

`YOUR_LINKEDIN_USERNAME`

and replace it with your LinkedIn profile slug.

## Email

Search for:

`YOUR_EMAIL@example.com`

and replace it with your email address.

## Add another client

Copy a block inside `.client-work` in `index.html` and add the client/project information.

Only publish client names and project details that you are allowed to make public.

## Add resume

Put your PDF inside:

`assets/Shanthan_K_Resume.pdf`

Then add this button in the hero or contact section:

```html
<a class="button ghost" href="assets/Shanthan_K_Resume.pdf" target="_blank">
  View Resume ↗
</a>
```
