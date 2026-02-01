# NWN Impact Report Request Form - Setup Guide

## 🎯 What This Is

A beautiful, simple form where your team can:
1. Fill in their info
2. Upload screenshots
3. Add report details
4. Submit request

**Result:** Downloads a ZIP file with everything organized. They email it to you. You process it using Claude. Done!

---

## 🚀 Super Quick Setup (3 Steps)

### Step 1: Upload to GitHub

1. Go to [GitHub.com](https://github.com) and create account (if needed)
2. Create new repository:
   - Name: `nwn-report-requests`
   - Public
   - Add README
3. Upload the file `nwn-report-request-form.html`
4. **Rename it to `index.html`** (important!)
5. Commit

### Step 2: Enable GitHub Pages

1. Repository Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: "main" → "/ (root)"
4. Save
5. Wait 2-3 minutes

### Step 3: Share Link

Your form is live at: `https://yourusername.github.io/nwn-report-requests/`

**Share this link with your team!**

---

## 💰 Cost: $0 (100% FREE!)

- ✅ GitHub Pages: FREE
- ✅ No API costs (you process manually)
- ✅ No server costs
- ✅ No subscriptions

**Total monthly cost: $0.00**

---

## 👥 How Your Team Uses It

### Step 1: Fill Out Form
- Name and email
- Select report type (monthly, event, alumni, snapshot)
- Upload screenshots (drag & drop)
- Add details (time period, purpose, notes)
- Select deadline (urgent, soon, this week, flexible)

### Step 2: Submit
- Click "Submit Request"
- ZIP file automatically downloads to their computer
- Named like: `NWN-Report-Request-Abiola-Elemikan-1738534523.zip`

### Step 3: Email You
Team member emails the ZIP file to you (or uploads to shared Google Drive)

### Step 4: You Process (5 Minutes)
1. Download ZIP file
2. Open it → See REQUEST-INFO.txt (all their details)
3. Come to our Claude project
4. Upload the screenshots from ZIP
5. Tell Claude: "Generate [report type] from these screenshots for [time period]"
6. Download generated report
7. Email back to requester

**Your time: ~5 minutes per request**

---

## 📦 What's in the ZIP File

```
NWN-Report-Request-Abiola-Elemikan-1738534523.zip
├── REQUEST-INFO.txt          ← All form details
└── screenshots/
    ├── screenshot1.png
    ├── screenshot2.png
    ├── screenshot3.png
    └── ...
```

### REQUEST-INFO.txt Contains:
```
NWN IMPACT REPORT REQUEST
========================

REQUESTER INFORMATION:
- Name: Abiola Elemikan
- Email: abiola@nwnfoundation.org
- Submitted: 2/1/2026, 3:45 PM

REPORT DETAILS:
- Type: Monthly/Quarterly Impact Report
- Time Period: January 2026
- Purpose/Audience: Board meeting
- Deadline: 2-3 business days

ADDITIONAL CONTEXT:
Focus on school outreach programs and 
highlight Ife's Acapella Studios work

SCREENSHOTS:
1. jan-5-school-visit.png (2.3 MB)
2. jan-12-alumni-update.png (1.8 MB)
3. jan-20-fundraising-post.png (2.1 MB)
...

Total Screenshots: 15

---
To Process:
1. Upload screenshots to Claude
2. Ask: "Generate Monthly/Quarterly Impact Report from these screenshots for January 2026"
3. Download generated .docx report
4. Email to: abiola@nwnfoundation.org
```

---

## ⚡ Your Processing Workflow

### When Request Comes In:

**1. Check Email/Drive** (wherever team sends ZIPs)

**2. Download ZIP, open REQUEST-INFO.txt**
   - Quick read: Who needs what, by when

**3. Come to Claude Project**
   - Upload all screenshots from ZIP
   
**4. Ask Claude:**
```
Generate [Monthly/Event/Alumni/Snapshot] Impact Report from these screenshots.

Time Period: [from REQUEST-INFO.txt]
Purpose: [from REQUEST-INFO.txt]
Additional Context: [from REQUEST-INFO.txt]

Use the NWN Impact Report Generator skill.
```

**5. Download Report**
   - Claude generates professional .docx

**6. Email to Requester**
```
Subject: Your NWN Impact Report - [Time Period]

Hi [Name],

Attached is your requested [report type] for [time period].

The report includes:
- Comprehensive metrics from your screenshots
- Professional formatting
- All standard NWN branding and narrative

Let me know if you need any adjustments!

Best,
[Your Name]
```

**Total Time: 5 minutes**

---

## 🎨 Customization (Optional)

### Add NWN Logo

1. Upload `nwn-logo.png` to GitHub repository
2. Edit `index.html`, find:
```html
<h1>📊 NWN Impact Report Request</h1>
```
3. Replace with:
```html
<img src="nwn-logo.png" alt="NWN" style="height: 60px; margin-bottom: 1rem;">
<h1>Impact Report Request</h1>
```

### Change Colors

Find this section in `index.html`:
```css
:root {
    --navy: #1F4E78;     /* Change to your primary color */
    --teal: #2E5C8A;     /* Change to your secondary color */
    --orange: #FF6600;   /* Change to your accent color */
}
```

### Change Email Instructions

In the success message section, edit:
```html
<p style="font-weight: 600;">
    Next Step: Email the downloaded ZIP file to reports@nwnfoundation.org
</p>
```

---

## 🔧 Alternative Submission Methods

### Option A: Email Submission (Current - Recommended)
Team emails ZIP to you manually
- ✅ Simplest
- ✅ No setup
- ✅ Works immediately

### Option B: Google Drive Upload (Advanced)
Integrate with Google Drive API so ZIP uploads automatically
- Requires: Google Cloud project, coding
- Benefit: Fully automated

### Option C: Email Service Integration (Advanced)
Use service like Formspree or Web3Forms to email ZIP automatically
- Requires: Third-party service account
- Cost: Usually free tier available
- Benefit: Requester doesn't have to email

**Recommendation:** Start with Option A (manual email). It's simple and works great!

---

## 📊 Expected Volume & Time Savings

### Monthly Report Requests (Example):
- 5 monthly/quarterly reports
- 3 event recaps
- 2 alumni compilations
- 2 quick snapshots

**Total: 12 reports/month**

### Time Comparison:

| Task | Old Way | New Way | Savings |
|------|---------|---------|---------|
| Team collecting screenshots | 30 min | 5 min | 25 min |
| Writing report from scratch | 4 hours | 5 min | 3h 55m |
| Formatting & polishing | 1 hour | 0 min | 1 hour |
| **Per Report** | **5.5 hours** | **10 min** | **5h 20m** |
| **12 Reports/Month** | **66 hours** | **2 hours** | **64 hours!** |

**You save 64 hours per month = 8 full work days!**

---

## ✅ Quality Control

### Before Sending Report to Requester:

Quick checklist:
- [ ] All screenshots referenced?
- [ ] Numbers look accurate?
- [ ] Names spelled correctly?
- [ ] Financial amounts correct (₦ vs $)?
- [ ] Report type matches request?
- [ ] Time period correct?
- [ ] Special requests addressed?

If anything looks off, ask Claude to fix it!

---

## 🐛 Troubleshooting

### "Download didn't work"
- Try different browser (Chrome works best)
- Check Downloads folder
- Disable pop-up blocker

### "ZIP file is too big to email"
- Upload to Google Drive instead
- Share link with you
- Or use file transfer service (WeTransfer, Dropbox)

### "Screenshots not showing in ZIP"
- Browser issue - try Chrome or Edge
- Or have them email screenshots directly as attachments

### "Form looks broken"
- Clear browser cache
- Try incognito/private window
- Check internet connection

---

## 📚 Training Your Team (10 Minutes)

### Quick Training Session:

**1. Demo (3 min)**
- Open the form link
- Fill out sample request
- Upload 2 screenshots
- Show ZIP download

**2. Practice (5 min)**
- Each person submits test request
- You process one live
- Show finished report

**3. Q&A (2 min)**
- Answer questions
- Share this guide
- Give them the link

### Training Materials to Share:

✅ Link to form  
✅ This setup guide (for reference)  
✅ Screenshot best practices  
✅ Sample ZIP file (so they know what to expect)  

---

## 📞 Team Support

### Common Questions:

**Q: How long will it take to get my report?**
A: Depends on deadline selected: Urgent (24h), Soon (2-3 days), This Week, or Flexible

**Q: Can I submit another request while waiting?**
A: Yes! Submit as many as needed

**Q: What if I made a mistake?**
A: Just submit a new request with correct info, mention it's a replacement

**Q: Can I see the report before you finalize it?**
A: Yes, ask for this in "Additional Context" field

**Q: How many screenshots should I upload?**
A: Depends on report type:
- Monthly: 10-20
- Event: 5-10
- Alumni: 3-8
- Snapshot: 2-4

---

## 🎉 Success Metrics to Track

After 1 month of using the form:

- ✅ Number of requests submitted
- ✅ Average processing time (should be ~5 min)
- ✅ Team satisfaction with results
- ✅ Time saved vs. manual process
- ✅ Report quality feedback
- ✅ Number of requests by type

**Goal:** Make impact documentation so easy that team does it consistently!

---

## 🚀 Next Level Enhancements (Future)

Once basic system is working:

### Phase 2:
- [ ] Automatic email integration (ZIP emails to you automatically)
- [ ] Google Drive integration (uploads directly to shared folder)
- [ ] Request tracking dashboard
- [ ] Template library for different report styles

### Phase 3:
- [ ] Full automation with backend server
- [ ] OCR text extraction from screenshots
- [ ] Report preview before finalizing
- [ ] Analytics on social media impact

**Start simple. Add features as needed!**

---

## 📋 Quick Reference Card (Print & Share)

```
┌─────────────────────────────────────────────────┐
│   NWN IMPACT REPORT REQUEST - QUICK GUIDE      │
├─────────────────────────────────────────────────┤
│                                                 │
│  1. Go to: https://yourusername.github.io/     │
│            nwn-report-requests/                 │
│                                                 │
│  2. Fill out form + upload screenshots         │
│                                                 │
│  3. Submit → Download ZIP file                 │
│                                                 │
│  4. Email ZIP to: reports@nwnfoundation.org    │
│                                                 │
│  5. Get professional report by deadline!       │
│                                                 │
│  Questions? Contact [Your Name/Email]          │
│                                                 │
└─────────────────────────────────────────────────┘
```

---

## ✅ Final Checklist

Before launching to team:

- [ ] Uploaded `index.html` to GitHub
- [ ] GitHub Pages enabled and working
- [ ] Tested form submission yourself
- [ ] Processed a test request through Claude
- [ ] Created email template for responses
- [ ] Shared link with team
- [ ] Provided this setup guide
- [ ] Scheduled quick training session
- [ ] Set up email/folder for receiving ZIPs
- [ ] Ready to process first real request!

---

**You're all set! This simple system will save you 60+ hours per month while maintaining professional quality reports.** 🎉

**Deploy today. Start saving time tomorrow!**

---

**NAVIGATING WITH NOEL FOUNDATION**  
*Learn & Earn • Building Sustainability • 100% Track Record*
