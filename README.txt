SEO-ready FileConvert app

Steps to deploy and get indexed by search engines:

1) Replace 'GA_MEASUREMENT_ID' in templates/base.html with your Google Analytics measurement ID (or remove script if not using).
2) Set your real domain in sitemap.xml and robots.txt (replace https://yourdomain.com).
3) Create a Git repo and push to Render/Railway/Heroku or any host that supports Python Flask.
4) Add HTTPS (Render provides SSL) and connect your custom domain.
5) In Google Search Console: add your site and submit sitemap (https://yourdomain.com/sitemap.xml).
6) Monitor indexing and errors in Search Console, and promote site to get backlinks for faster indexing.

Run locally:
  python -m venv venv
  source venv/bin/activate    # Windows: venv\Scripts\activate
  pip install -r requirements.txt
  python app.py
