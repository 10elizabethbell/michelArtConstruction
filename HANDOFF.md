# MichelArt Construction — handoff at ~60%

**Live:** https://10elizabethbell.github.io/michelArtConstruction/ · **Repo:** https://github.com/10elizabethbell/michelArtConstruction · **Built:** 2026-10-19 from Muse brief (Muse run 2026-10-19, found via FB group "NJ Seeking Contractors")

## What's built
- One page, phone first: header (M logo + wordmark, `(718) 909-8060` top-right as tap-to-call), hero, What we build (6 service rows, each opens a pre-written text to Mike naming the service), Recent work (6 photos + Facebook button + Instagram link), How a job goes (3 steps + one care line), "Ready for a real quote?" form (composes a text to Mike, with copy-message fallback), footer (name, tagline, phone, North Jersey, Facebook, Instagram).
- **World:** a North Jersey roof at dusk. Slate-blue ground (not black), amber from the MichelArt M, fresh-drywall light sections, white gutters closing the dark sections, photo corners cut at the angle of the logo's strokes.
- **Signature element:** the hero roof (canvas). A tired tan roof with black algae streaks, curled tabs, moss and a few missing shingles gets re-shingled course by course (bottom course first, like a real roofer) with new pewter architectural shingles. Drag a finger or mouse over it to re-shingle it yourself; new tabs lift and wobble under the finger and flutter in passing gusts; old granules shake loose. A finished roof holds ~5s, tears off from the ridge down, and starts again. Works on vertical drags too (`touch-action:none` on the roof, pull-to-refresh off). Eave strips (one course + gutter) at the bottom of Recent work and the top of the footer react the same way.
- Tunables are the `ROOF` object at the top of the second script (speeds, reach, lift, rows, wind). `ROOF.STILL = true` freezes everything into one finished roof if you decide this audience skews older.
- Contact: everything goes to +1 (718) 909-8060 by `sms:` (texts accepted per the ad) or `tel:` (header and footer only).

## Assumptions I made
- **Phone number:** used (718) 909-8060 from the brief's FB ad ("Call or Text Mike"). The Instagram reel caption (2025-10-10) lists a **different number, (973) 259-5010**. Confirm which one Mike wants on the site.
- **Voice:** "we" (the IG caption speaks as "we" and the reel shows a crew), with Mike named as the person you text.
- **Colors:** amber `#F4A21C` and white sampled from the FB profile logo; the logo's charcoal ground became slate-blue `#1D2530` (house rule: no black grounds).
- **Headline:** their own tagline "Construction with Certainty". Footer tagline: their own "Quality workmanship from start to finish".
- **"Clear timelines" and "clean job sites"** are the owner's own ad claims; I used them as promises in step 3 ("On the timeline we agreed, with a clean job site"). The brief flags them "verify before publishing" — confirm with Mike.
- **"Free estimate"** is from the IG caption ("Message or call us right now for a free estimate").
- **Licensed / insured ($1M/$2M) is NOT on the page** — unverified per the brief. "Licensed" from the IG caption also left off.
- **Service names** shortened from the brief's verbatim list; detail lines kept verbatim only where the brief had them (roofing, drywall & painting). "Full renovations" comes from "From roofing to full home renovations".
- **Step 2 copy** ("We look at the job and give you a real quote before any work starts") is inferred from "Ready for a real quote?" + "free estimate".
- **Audience** treated as general homeowners (motion on). The brief doesn't say 40+; if Ellie thinks it does, set `ROOF.STILL = true` and follow `older-audience.md`.

## Placeholders and gaps
- **Photos:** all six are stills pulled from their one Instagram reel (1080x1920 video frames, so a little soft). Exterior photo has the house number "363" painted out. No before/after pairs. Their IG has 49 posts / 7.6k followers — real stills from there would be sharper.
- **Logo:** from the FB profile picture (720px raster, background keyed out). An SVG of the M would be crisper; worth redrawing or asking Mike for the file.
- **No email** anywhere (none found). Footer email slot left out.
- **No hours, no towns** beyond "North Jersey" (the reel shows a job in Little Falls, NJ; not named on the page).
- No reviews anywhere, so no reviews section.

## Questions for the owner
- Which number: (718) 909-8060 or (973) 259-5010? Does it take texts?
- Licensed and insured: can he share the license number / COI so we can show it? (Big trust win for roofing.)
- Which towns does he serve? Hours?
- Original photos (and any before/afters), especially roofs: the site leads with roofing but has no roof photo.
- An email for the footer?
- Does he do new construction / additions? (The reel shows new-house framing and says "houses", "apartments".)

## Ideas not built (yours to pick)
- **Runner-up world:** laser level and bubble vial ("Construction with certainty") — an amber laser line across the page the finger drags, a level bubble that settles. Other candidates: blueprint linework drawing itself; setting tile in a walk-in shower; sawdust in a work-light beam; framing lumber with grade stamps.
- **Impeccable's roll** assigned the framing-lumber world (my #7); I overrode it with the pitch-site rule (best brand + touchable material). Seed key 9bd3f77a if you want to revisit.
- Before/after slider once Mike sends pairs (roof before/after would be perfect under the roof hero).
- Tap-to-enlarge photos; a roof photo as the first work image.
- A "Roofing" deep page with the same roof hero.
- A tiny drag hint on the roof ("drag to re-roof") if testers don't discover it.

## Not verified
- Real-device touch (iPhone Safari, Android Chrome, Facebook in-app browser) — only simulated touch in headless Chrome.
- Real SMS handoff on iOS/Android (body pre-fill with `?&body=`).
- Frame rate on older phones (phone roof ≈ 300 tabs drawn per frame).
