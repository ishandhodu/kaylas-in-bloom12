# Client Feedback

## First conversation — September 27, 2026

**Format:** Kayla reviewed the deployed site and gave verbal feedback, relayed and recorded below.

- Loved that her own brand assets — the swans and florals she'd had made — carried through into the site.
- Loved the pink color palette and the color contrast.
- Said the site was "exactly tailored to the vision she wanted."
- Specifically wanted the site to be simple, and felt that came through.
- Liked the navigation bar — felt every item was well thought out.
- Liked the Contact form and where it's placed on the page.
- Liked the overall aesthetic and appeal.
- Called out the Menu page specifically — said it looked aesthetic and made ordering easy to understand.

No changes requested in this round.

## Second conversation — October 1, 2026 (after the 9/29 showcase)

**Format:** Verbal conversation with Kayla about the version she'd already seen (the one reviewed above and shown at the showcase), relayed and recorded below.

### What she said about the first version

- The biggest thing she liked was the use of her own elements and assets. She'd been afraid we would change too much, but felt we implemented her assets, her color palette, and her branding "perfectly."
- She did not want major changes — she likes the way the website is. It fits her simple vibe and her "college dorm business" vibe.
- She did want two specific things added:
  1. A fully functional Stripe checkout, instead of the current contact-and-confirm flow.
  2. An About Me section with a picture of her, her background, and her history — she wants the brand to be founder-led, with her as the main persona of the company, not just a generic shop front.

### One item, AI options, and what I picked

For the real-photography question, my AI agent laid out adding more real flower/bouquet images across the whole site. I dropped that — it went against what Kayla actually wanted. She wants real photos of flowers/bouquets scoped to the shop (Menu/Subscriptions) section only; everywhere else on the site should stay her own hand-drawn brand assets (swans, florals, motifs), not stock or real photography.

### What changed because of this conversation

Built the founder-led About section she asked for — her photo (a placeholder until she sends a real one), her background, and her story, in `about.html`. Live on the site: commit [`8d7b252`](https://github.com/ishandhodu/kaylas-in-bloom12/commit/8d7b252fda362af952cae441bc74483517fff67).

The Stripe checkout ask is tracked in `PRD.md`'s Later list (ranked #1, per her priority) but not built here — it's out of scope for this course deliverable and belongs to the separate paid Ivy Devs engagement.
