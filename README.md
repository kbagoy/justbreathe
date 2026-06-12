# Just Breathe Therapeutic Massage — Launch Instructions

---

## Part 1: Get Your Site Live on justbreathmassage.com

**Step 1 — Turn on GitHub Pages**

1. Go to github.com and sign in to Kate's account (or have Kate do this part)
2. Click the **justbreathe** repository
3. Click **Settings** (top menu)
4. Click **Pages** (left sidebar)
5. Under "Branch", select **main** and click **Save**
6. Under "Custom domain", type `justbreathmassage.com` and click **Save**

**Step 2 — Point your domain to GitHub**

Log in to wherever you bought your domain (GoDaddy, Namecheap, Squarespace, etc.) and find the **DNS Settings**.

Add these records:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | kbagoy.github.io |

> DNS changes can take up to 24 hours to kick in. Once it works, go back to GitHub Pages settings and check **"Enforce HTTPS"** — this gives you the padlock in the browser.

---

## Part 2: Google Search Console (helps Google find your site)

1. Go to **search.google.com/search-console**
2. Sign in with your Google account
3. Click **Add property** → choose **URL prefix** → enter `https://justbreathmassage.com`
4. Google will ask you to verify ownership — choose **HTML tag**, copy the code it gives you, and send it to Kate to add to the site
5. Once verified, click **Sitemaps** in the left menu
6. Enter `sitemap.xml` and click **Submit**

That's it — Google will now crawl and index your site.

---

## Part 3: Google Business Profile (shows up on Google Maps)

This is one of the most important things you can do for local visibility.

1. Go to **business.google.com**
2. Sign in with your Google account
3. Click **Add your business**
4. Enter **Just Breathe Therapeutic Massage**
5. Category: **Massage Therapist**
6. When asked for a location, select **"I deliver goods and services to my customers"** (since you're mobile) — enter **Tucson, AZ** as your service area
7. Add your phone number: **(520) 496-8180**
8. Add your website: **justbreathmassage.com**
9. Google will verify you — usually by a phone call or postcard to confirm you're a real business

**Once your profile is live, make sure to:**
- Upload photos (use the flyer images and any client-approved massage photos)
- Add your services (Therapeutic, Pulmonary Support, Oncology-Sensitive)
- Ask happy clients to leave a Google review — this is the #1 thing that helps you show up in local search

> **Tip:** Once Search Console and Google Business Profile are both set up and your site is indexed, go back into Search Console and link it to your Google Business Profile — it gives you even more data about how people find you.
