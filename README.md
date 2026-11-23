# Product Messaging Studio

Drop in any content (clinical trial results, a white paper, competitive notes or an internal update) and get messages your team can use today: key messages ranked for each role, objection handling, an evidence infographic and a strategic battlecard.

**[Live demo](https://warisham.github.io/healthcare-messaging-studio/)** · One HTML file · No install, no build step

## The problem

Product marketing and sales teams sit on valuable content, but turning each piece into clear, compliant messages for every audience is slow, manual work. A trial readout becomes a deck for the CMO, a cost story for the CFO, an integration answer for the CIO and a talk track for reps, and each version gets rewritten by hand. Most teams have no dedicated tool for this, so messaging drifts, proof gets lost, and claims slip past Medical, Legal and Regulatory review.

## How it works

1. **Start from anything.** Pick a content type: clinical trial results, white paper, competitive intel or internal update. Each comes with a sample file, and you can add up to three of your own as supporting examples.
2. **Check the source and pick a role.** See the facts the studio found, then write for Clinicians, the CMO, the CEO / CFO, the CTO / CIO, the sales team or patients.
3. **Key messages, ranked for that role.** The same three facts are re-ordered by what the role is measured on, tagged "Best fit", "Strong" or "Supporting", with a "lead with" line on top.
4. **Messages by role.** One view shows how the same source is sorted for all six audiences side by side.
5. **Objection handling.** The two most likely objections for each role, a short answer and the proof that backs it up.
6. **Evidence infographic.** A one-page visual of the trial: study design, the primary endpoint chart, adherence and safety.
7. **Strategic battlecard.** For each competitor: their strategy, our strategy, why we win and where they win, three winning plays, and the question to ask on the call.

**Send to** copies the right format to your clipboard: key messages for a sales deck, an email, a CRM battlecard or a social post.

## Built-in checks

| Check | Benchmark |
| --- | --- |
| Reading grade (Flesch-Kincaid) | 10 or lower |
| Hype words | None ("revolutionary", "seamless", "best-in-class"...) |
| Regulatory claims | Flags language that doesn't fit the product's status, such as "FDA-approved" for a 510(k)-cleared device |
| Proof | Every message is tied to a fact from a source file; missing proof shows as a [placeholder] |

## Design

This is the friendly, image-led direction chosen from three design explorations (image-led, sales battlecard and simple dropdown builder). Illustrations are inline SVG, every control is a real button or link at least 44 px tall, and the layout works from phone to wide desktop.

## Testing

82 automated checks passed in a headless browser at 375, 768, 1280, 1440 and 1920 px wide:
- no JavaScript errors
- no horizontal scroll or content past the edge
- no clipped text and no unfilled template text
- every button and link at least 44 × 44 px
- every illustration rendered

Interaction tests cover all four content types, all six roles (lead line, ranking, objections), all three competitors, adding and removing a file, copying to the clipboard, and keyboard selection with focus kept in place.

## Run it

Open `index.html` in any browser, or publish it with GitHub Pages (Settings → Pages → `main` / root).

## Disclaimer

Portfolio demo. Product 1, Competitor A, B and C, the sample files and all figures are fictional. Review every message with Medical, Legal and Regulatory before use.

---
Built by Warisha Khan: product marketing and product management for digital health and AI.
