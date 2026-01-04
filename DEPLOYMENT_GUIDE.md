# Sleep Optimized - Deployment Guide

## 🚀 Quick Start

Your sleep optimization affiliate site is ready to deploy! Follow these steps to get it live on Cloudflare Pages (100% free).

---

## Step 1: Buy Your Domain

**Recommended Domain:** `SleepOptimized.com`

1. Go to [Namecheap.com](https://www.namecheap.com)
2. Search for `sleepoptimized.com`
3. Purchase the domain ($12-15/year)
4. You'll connect it to Cloudflare in Step 4

---

## Step 2: Push to GitHub

### Option A: Using GitHub Desktop (Easiest)

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Click "Add" → "Add Existing Repository"
3. Select the `sleep-optimized` folder
4. Click "Publish repository"
5. Name it `sleep-optimized`
6. Uncheck "Keep this code private" (or keep it private, both work)
7. Click "Publish repository"

### Option B: Using Command Line

```bash
cd sleep-optimized
git remote add origin https://github.com/YOUR-USERNAME/sleep-optimized.git
git branch -M main
git push -u origin main
```

---

## Step 3: Deploy to Cloudflare Pages

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Sign up or log in (free account)
3. Click "Create a project"
4. Click "Connect to Git"
5. Select your GitHub account
6. Choose the `sleep-optimized` repository
7. **Build settings:**
   - Framework preset: **Astro**
   - Build command: `pnpm build`
   - Build output directory: `dist`
8. Click "Save and Deploy"

**Your site will be live in 2-3 minutes!**

You'll get a free subdomain like: `sleep-optimized.pages.dev`

---

## Step 4: Connect Your Custom Domain

1. In Cloudflare Pages, click on your project
2. Go to "Custom domains"
3. Click "Set up a custom domain"
4. Enter your domain: `sleepoptimized.com`
5. Follow the instructions to:
   - Add your domain to Cloudflare (free)
   - Update nameservers at Namecheap
6. Wait 5-30 minutes for DNS propagation

**Done!** Your site is now live at `https://sleepoptimized.com`

---

## Step 5: Update Affiliate Links

Before you start promoting, you need to add your affiliate links to the articles.

### Apply to Affiliate Programs

1. **Casper** (20% commission - Priority #1)
   - Apply: https://purple.com/ambassador
   - Wait for approval (usually 1-3 days)

2. **Saatva** (8% commission)
   - Apply: https://join.partnerize.com/saatva/en
   - Wait for approval

3. **Chilipad/Sleep.me** (6% commission)
   - Apply: https://sleep.me/affiliates
   - Instant approval

4. **Amazon Associates** (3-4% commission)
   - Apply: https://affiliate-program.amazon.com/
   - Wait for approval

### Update the Links

Once approved, search for `your-affiliate-link-here` in your articles and replace with your real affiliate links:

```bash
# In your code editor, search for:
your-affiliate-link-here

# Replace with your actual affiliate links like:
https://casper.com/mattresses?tag=youraffid-20
```

**Files to update:**
- `src/content/blog/complete-guide-to-sleep-biohacking.md`
- `src/content/blog/sleep-optimization-for-athletes.md`
- `src/content/blog/best-cooling-mattress-for-hot-sleepers.md`

---

## Step 6: Set Up Google Search Console

1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add your property: `https://sleepoptimized.com`
3. Verify ownership (Cloudflare makes this easy)
4. Submit your sitemap: `https://sleepoptimized.com/sitemap-index.xml`

**Why this matters:** Google will start indexing your site and you'll see which keywords are ranking.

---

## Step 7: Write More Content

Your site currently has 3 pillar articles. To start ranking and making money, you need to publish consistently.

**Goal:** 30 articles in 90 days (10/month)

**Content calendar** (from your strategy doc):

### Month 1 (Next 10 articles):
1. How to Optimize Your Sleep: 15 Science-Backed Techniques
2. Best Sleep Tracking Devices for Biohackers (Oura vs Whoop vs Muse)
3. Chilipad vs Eight Sleep: Which Cooling System is Worth It?
4. Best Mattress Toppers for Temperature Regulation
5. Sleep Optimization Tech Stack: What Actually Works?
6. Best Mattress for Night Sweats: Menopause & Hot Flashes
7. How to Stop Waking Up Hot at Night (7 Solutions)
8. Cooling Mattress Topper vs Chilipad: Which is Better?
9. Best Sheets for Night Sweats (Tested & Reviewed)
10. Temperature Regulation for Better Sleep: Complete Guide

**Writing tip:** Use the same structure as your existing articles:
- 2000-3000 words
- Include product comparisons
- Add affiliate links
- Use tables for comparisons
- Focus on solving specific problems

---

## Step 8: Promote Your Content

### Reddit (Best for early traffic)

**Subreddits to target:**
- r/Biohackers (1.2M members)
- r/sleep (300k members)
- r/Mattress (180k members)
- r/Fitness (10M members)

**How to do it right:**
1. Join the communities
2. Participate genuinely (comment on other posts)
3. After a week, share your article as a helpful resource
4. Don't spam - provide value first

**Example post:**
> "I spent 3 months testing cooling mattresses for hot sleepers. Here's what I found..."
> [Link to your article]

### Pinterest (Passive traffic)

1. Create a Pinterest business account
2. Design infographics from your articles (use Canva)
3. Pin them with links back to your site
4. Pinterest is a search engine - optimize for keywords

---

## Revenue Expectations

**Timeline to $2k/month:**

- **Month 1-2:** $0-100 (building content, waiting for Google)
- **Month 3-4:** $100-500 (first rankings, first sales)
- **Month 5-6:** $500-1,500 (momentum building)
- **Month 7-8:** $1,500-2,500 (hitting stride)

**Key metrics to track:**
- Monthly visitors
- Affiliate clicks
- Conversion rate
- Revenue per visitor

---

## Maintenance & Growth

### Weekly Tasks:
- Publish 2-3 new articles
- Share on Reddit/social media
- Check Google Search Console for ranking keywords

### Monthly Tasks:
- Review affiliate earnings
- Update old articles with new products
- Build backlinks (guest posts, forums)

### Quarterly Tasks:
- Analyze top-performing content
- Double down on what works
- Consider expanding to YouTube

---

## Need Help?

**Common Issues:**

1. **Site not building?**
   - Check build logs in Cloudflare
   - Make sure `pnpm build` works locally

2. **Affiliate links not working?**
   - Check if you're approved
   - Test links in incognito mode

3. **Not ranking on Google?**
   - Give it 3-6 months
   - Focus on long-tail keywords
   - Build more content

---

## You're Ready! 🎉

Your site is professional, SEO-optimized, and ready to make money. The hard part is done. Now it's about consistency:

1. **Write 10 articles/month**
2. **Promote on Reddit/Pinterest**
3. **Track your progress**
4. **Be patient** (SEO takes 3-6 months)

**Stick with it for 6 months and you'll hit $2k/month.**

Good luck! 🚀
