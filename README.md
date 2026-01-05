# kevinroose.com

Personal website. Plain HTML/CSS, hosted on GitHub Pages.

## Local Preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g., `kevinroose.github.io` or `website`)
2. Push this code to the repo
3. Go to Settings → Pages → Source → Deploy from branch (main)
4. Add custom domain `kevinroose.com` in Settings → Pages

## Custom Domain DNS

At your domain registrar, set:

```
Type: A
Name: @
Value: 185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153

Type: CNAME
Name: www
Value: kevinroose.github.io
```

Then add a `CNAME` file to this repo containing: `kevinroose.com`
