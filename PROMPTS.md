# Build this website yourself: 1 brief + 4 prompts

Used in the Urdu tutorial on the Boring Work, Automated YouTube channel. Paste each prompt into Claude Code (claude.ai/code) on your own GitHub repository, one after the other, in the same chat. Change the business details to yours.

## The one-page brief (fill this in first)
- What the business is:
- Who the customer is:
- What the customer should do on the site (e.g. WhatsApp you):
- Sections:
- Colours (take them from your logo):
- Facts only: no fake reviews, no invented numbers or client names.

## PROMPT 1 · BUILD
Build a one-page website for Vintage Tech Solutions (VTS), an "AI Agent Factory" in Karachi that builds AI agents for businesses.

Make ONE index.html with inline CSS and JS. No frameworks, no CDNs. Use the files in /assets (logo vts-mark-96.webp, fonts Syne.woff2 for headings and SpaceGrotesk.woff2 for text).

Colours: dark background #0B0C0E, cyan #2EC8F2 to violet #7B5CF0 gradient (from the logo), orange #E85D20 only for buttons.

Sections:
1. Small floating nav: logo, How we build, Agents, Showcase, FAQ, button "Build my agent"
2. Hero: "We build AI agents that work." + one line + 2 buttons + stats: 50+ automations shipped, 24/7, as low as $50 a month
3. Problem: 4 cards (leads go cold, missed calls, wasted hours, costly errors)
4. How we build: 4 steps (map the boring work, design the agent, build and test, deploy and watch)
5. Agents: 6 cards (WhatsApp Lead Agent, AI Receptionist, Inbox Assistant, Finance Back-Office, Sales Follow-up, Ops and HR Workflows)
6. Showcase: tabs for AI Receptionist, Inbox Assistant, WhatsApp Lead Bot, Kitchen OS (leave space, videos come later)
7. Two ways to work with us: Done for you / Done with you
8. FAQ (5 short questions)
9. Final call to action with two WhatsApp buttons: Abdul Yousuf +92 318 4832979 (wa.me/923184832979) and Ahsan Danish Rind +92 336 2616921 (wa.me/923362616921)

Rules: no testimonials, no invented numbers or client names. Mobile-first.
Test it in a headless browser, then commit and push to main.

## PROMPT 2 · DESIGN + ANIMATION
Make it feel premium and alive:
- Hero: headline lines rise in one by one. On the right, a canvas "agent factory": small task pills (email, invoice, lead, call, order) float into a spinning glowing core and fly out as dots to a network of agent nodes that light up.
- Scroll reveal: sections fade up as you scroll.
- Hover: agent cards get a cursor spotlight and a slight 3D tilt.
- Marquee: a moving strip of problems under the hero.
- Sticky: in "How we build", the heading stays put while a line fills as you scroll through the 4 steps.
- Respect prefers-reduced-motion (turn animations off).
Test, then commit and push to main.

## PROMPT 3 · VIDEOS + SPEED
Add the product videos:
- Hero: a floating card with assets/robot.mp4 and a green "AGENT ONLINE" badge.
- Showcase tabs: AI Receptionist = assets/receptionist.mp4, Inbox Assistant = assets/inbox.mp4, each with its .webp poster.
- WhatsApp Lead Bot tab: an animated chat that types itself (customer asks for 40 lunch boxes, the agent qualifies and sends a quote), ending with a "Qualified lead → CRM" card.
- Kitchen OS tab: a live order board moving New → Cooking → Out for delivery, labelled demo data.
Videos: muted, looped, playsinline, preload none, only load and play when visible. Keep the page fast on a slow phone.
Test, then commit and push to main.

## PROMPT 4 · TEST + FIX
Check the page at 390px (phone) and 1440px (desktop). Fix anything that overlaps, is cut off or makes the page scroll sideways. Make sure every WhatsApp button opens the right number. Report what you checked, then commit and push to main.

## Go live
Repository → Settings → Pages → Deploy from a branch → main → / (root) → Save. Every push to main updates the live site.
