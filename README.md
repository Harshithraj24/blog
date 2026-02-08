# Harshith's DevOps Blog

A technical blog covering cloud infrastructure, Kubernetes, and DevOps war stories.

## 🚀 Quick Setup — GitHub Pages

### Step 1: Create the repo
```bash
# Create a new repo on GitHub called "blog" (or any name you like)
# Then clone and push:
git init
git add .
git commit -m "feat: first blog post - VPC peering overlapping CIDRs"
git branch -M main
git remote add origin git@github.com:<YOUR_USERNAME>/blog.git
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Branch: `main` / Folder: `/ (root)`
4. Click **Save**

### Step 3: You're live! 🎉
Your blog will be available at:
```
https://<YOUR_USERNAME>.github.io/blog/
```

It takes ~1-2 minutes for the first deploy.

### Optional: Custom Domain
1. Buy a domain (Namecheap, Cloudflare, etc.)
2. Add a `CNAME` file to the repo root with your domain
3. In GitHub Pages settings, enter your custom domain
4. Add these DNS records at your registrar:
   - `A` records pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - `CNAME` for `www` → `<YOUR_USERNAME>.github.io`

## 📝 Adding New Posts
Just add new `.html` files and link them from `index.html`.
