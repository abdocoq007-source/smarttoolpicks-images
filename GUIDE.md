# How to produce a SmartToolPicks article

Blog: https://anchor2024.blogspot.com (SmartToolPicks — honest reviews & comparisons of AI tools, design apps and software; English; audience US/UK/CA).

## Content rules
- 1,300–1,800 words, English, simple language, honest pros AND cons, no invented personal testing claims.
- Research current prices/limits with web search before writing (prices change often). State "USD, <Month Year>, check official pages".
- Structure: featured image → intro (2 paras) → "⚡ Quick verdict" box → numbered H2 sections (one winner line each) → image(s) → "Who should choose which?" table → "🏆 Final verdict" box → "Frequently Asked Questions" (questions as bold paragraphs, NOT h3 — keeps the theme's TOC short) → comment prompt.
- Use h2 for main sections, h3 sparingly.
- No health/finance supplement promotion, no affiliate links.

## Images (3 per article)
- Render 1200x630 with headless Chrome from templates/ (featured-vs.html or featured-list.html, table.html, winner.html), change texts/colors. Crop empty space. Save JPG quality 85.
- Commit to posts/YYYY-MM/<slug>*.jpg and push to main.
- Use in HTML as: https://cdn.jsdelivr.net/gh/abdocoq007-source/smarttoolpicks-images@main/posts/YYYY-MM/<file>.jpg with width="640", centered <p>.

## Delivery
1. Email the article HTML (subject = article title) to the Blogger post-by-email address; Blogger saves it as a draft. The Gmail connector strips <img> tags with external URLs, and emails with attachments get blocked, so send without attachments; the user adds the 3 images in Blogger with Insert image → By URL. Wait ~60s and check Gmail for a mailer-daemon bounce.
2. ALWAYS also email abdocoq007@gmail.com a message "[SmartToolPicks] Ready: <title>" containing: title, labels, permalink slug, search description (≤155 chars), the 3 jsDelivr image URLs as plain text (for Blogger's Insert image → By URL), and the full HTML code inside a <pre> block (HTML-escaped) so it can be copy-pasted into Blogger's HTML view if the draft didn't arrive.
3. Mark the topic [x] in TOPICS.md and push.
