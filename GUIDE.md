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

## Delivery (changed 2026-11-25 at the user's request)
- Do NOT send any email (no Blogger post-by-email, no email to Gmail).
- Deliver each article in the chat: the COMPLETE HTML in one html code block (with the jsDelivr images), then below it Title, Labels, Permalink slug and Search description (≤155 chars), each in its own code block. The user pastes the HTML into Blogger's HTML view.
- Also send the featured <slug>.jpg as a file in the chat; the user replaces the first image with it via Insert image → Upload (Seoplus homepage thumbnail).
- Avoid bare brand names that look like web addresses (e.g. "hide.me"): Blogger auto-links them.
- Mark the topic [x] in TOPICS.md and push.
