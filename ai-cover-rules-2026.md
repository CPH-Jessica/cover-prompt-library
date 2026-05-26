# AI Book Cover Rules — A 2026 Reference Guide

*Compiled May 12, 2026 — Clark Publishing House / The Invisible Pen*

> **Plain-English bottom line:** You can legally make AI book covers with most major tools today. The catch is in three places: **(1) what you can disclose to KDP and other platforms, (2) whether you can actually copyright the cover, and (3) whether the image accidentally infringes on someone else's IP.** This guide walks through each tool and the rules around them.

---

## The Three Rules That Apply Everywhere

Before any specific tool: these three rules apply across every AI image generator you use.

**1. The platform license is not the same as copyright.**
Every major AI tool grants you a *license* to use the image commercially. That is not the same as you *owning* the copyright. As of the March 2026 Supreme Court denial of cert in *Thaler v. Perlmutter*, the law in the US is settled: a purely AI-generated image, made from a prompt alone, has **no human authorship** and therefore **cannot be copyrighted**. You can sell it. You just can't stop someone else from copying it.

**2. The platform license does not protect you from third-party claims.**
If the AI spits out something that looks like Disney's Elsa, or like a real celebrity's face, or like a real artist's signature style, you are the one who gets sued — not the AI company. Most tools say this explicitly in their TOS. The one big exception is Adobe Firefly (see below).

**3. KDP, IngramSpark, and Draft2Digital each have different disclosure rules.**
What's fine on Amazon may flag you on IngramSpark. Know the platform before you upload.

---

## Tool-by-Tool Breakdown

### Ideogram
**Commercial use:** Yes, on all tiers — including free.
**Ownership:** Ideogram explicitly does not claim ownership of your outputs and does not restrict commercial use. Their TOS assigns all rights in the output to you.
**Strength for covers:** Best-in-class for accurate **text on image** — useful for titles, subtitle text, and series banners that other tools mangle.
**Watch out for:** You are still responsible for not infringing on third-party IP. The free license is identical to paid in terms of usage rights — paid just gets you more generations and higher resolution.

### Grok / Aurora (xAI)
**Commercial use:** Yes, on all tiers — Free, X Premium, and SuperGrok.
**Ownership:** xAI's TOS assigns ownership of outputs to the user. No revenue cap.
**Strength for covers:** Will generate things other tools refuse (including stylized real-person likenesses, which is **a major legal risk, not a feature** — see "Likeness" section below).
**Watch out for:**
- **No IP indemnification.** If a copyright claim hits, you're on your own.
- xAI retains the right to train on your prompts and outputs.
- The more permissive content filter is a double-edged sword. Grok will happily generate a face that looks suspiciously like a known actor. That is your legal problem, not xAI's.

### Google Gemini / Imagen
**Commercial use:** Yes, on all tiers including free, per Google's terms.
**Ownership:** Google grants you commercial rights to outputs without royalties.
**Strength for covers:** Imagen 4 / Nano-Banana is very good at clean composition and photorealistic faces. Cheaper than Midjourney if you already have Google One / Gemini Advanced.
**Watch out for:**
- Same copyrightability problem as everyone else.
- Google's permission does not override third-party rights. If Gemini renders something that looks like a copyrighted character, you cannot use that.
- Enterprise (Vertex AI) tier has additional protections that consumer Gemini does not.

### Midjourney
**Commercial use:** **Paid plans only.** Basic ($10/mo), Standard ($30), Pro ($60), Mega ($120).
**Ownership:** Paid subscribers get a commercial license to use, sell, and build on outputs.
**The $1M Rule:** If your business grosses over $1 million USD a year, you must be on Pro or Mega to use the images commercially. (Most indie authors will not hit this.)
**Strength for covers:** Still considered top-tier for atmospheric, painterly, romance/fantasy aesthetics. Massive style range.
**Watch out for:**
- **Active Disney/Universal/DreamWorks lawsuit** (filed June 2025, still in litigation as of May 2026). Allegations include unlicensed training data and outputs that mimic copyrighted characters. No ruling yet, but the case is being watched as the one that may reshape AI cover rules.
- Public mode on lower tiers means your generations are visible to other users — and they can use them too. Use Stealth Mode (Pro/Mega) for client work.

### DALL-E (via ChatGPT)
**Commercial use:** Yes. OpenAI's terms assign all right, title, and interest in DALL-E outputs to the user.
**Ownership:** You own outputs and may use them for any legal purpose, including selling book covers.
**Strength for covers:** Easy to iterate on inside ChatGPT, no separate tool. Solid for stylized illustrative covers.
**Watch out for:**
- Content restrictions on real people and "living artist styles."
- Same copyright-of-AI-output limitation: you own the license, but pure AI output likely isn't copyrightable.

### Leonardo AI
**Commercial use:** **Paid plans only** ($10/mo and up). Free tier outputs cannot be used commercially.
**Ownership:** Paid subscribers retain full ownership of *private* generations. Public generations on free tier are not yours to sell.
**Strength for covers:** Strong style controls, character consistency tools, fine-tuned model picker — useful when you need a series to look like a series.
**Watch out for:**
- Make sure your generations are set to **Private** if you don't want them used to train models or shown to other users.
- Free tier is for play. Don't put a free-tier Leonardo image on a published book.

### Stable Diffusion / SDXL
**Commercial use:** Yes, with no revenue caps. Falls under the CreativeML Open RAIL++-M License.
**Ownership:** You own your outputs whether you self-host or use the API.
**Strength for covers:** Free if you run it locally. Massive ecosystem of fine-tuned models (romance, fantasy, horror, dark academia, etc.) on Civitai and elsewhere.
**Watch out for:**
- **Read the model card.** Base SDXL is permissive, but specific fine-tuned models on Civitai have their own licenses — some prohibit commercial use, some require credit, some are CC-non-commercial. The model you download is not automatically the same license as base SDXL.
- The RAIL license has use-based restrictions (no illegal/harmful content) but no royalty.
- Highest technical lift — running SDXL well takes a GPU and some setup.

### Canva AI (Magic Media)
**Commercial use:** Yes, on Canva Pro / Teams. Allowed for "any legal purpose, including personal or commercial projects" per Canva's terms.
**Ownership:** You own the images you create. Canva does not claim copyright over Magic Media output.
**Strength for covers:** Integrates with the rest of Canva — fonts, layouts, templates — so you can take an AI image and finish the cover in the same tool. Great for paperback wraparounds and KDP-spec sizing.
**Watch out for:**
- Canva explicitly says you may **not have exclusive rights** to your AI output. Two authors could prompt similar things and get similar covers.
- Canva does not guarantee outputs are cleared for use if the design resembles someone else's work.
- Same general copyrightability limitation.

### Adobe Firefly
**Commercial use:** Yes, on all paid Creative Cloud plans. **The only major tool with built-in IP indemnification.**
**Ownership:** You may use Firefly outputs for commercial purposes including book covers.
**The big difference:** Adobe trained Firefly exclusively on **licensed Adobe Stock, openly licensed content, and public domain material.** If someone claims a Firefly output infringes their IP, Adobe will defend you (on qualifying paid plans).
**Strength for covers:** Lowest legal risk of any tool on this list. Native integration with Photoshop and Express. If you have a Creative Cloud subscription, you may already be paying for it.
**Watch out for:**
- Quality is generally rated below Midjourney/Ideogram/Grok for atmospheric romance and fantasy covers. Improving fast in 2026 but not the top of the pack aesthetically.
- Indemnification applies through Adobe apps and qualifying plans only — **not** through third-party API wrappers.

---

## The KDP / Distributor Rules

This is where most authors get tripped up. The disclosure rules are different at each platform.

### Amazon KDP
- **You must disclose** AI-generated content, including cover images and interior artwork. There is a checkbox in the KDP publishing workflow when you set up or edit a title.
- AI-*generated* must be disclosed. AI-*assisted* (edits, touch-ups, prompts used as part of a human-designed cover) does **not** require disclosure.
- KDP says the disclosure is **confidential**, does **not** go public, and does **not** negatively affect approval.
- KDP will not reject a book for being AI-generated, but **failure to disclose** can get a book removed.

### IngramSpark
- IngramSpark's Catalog Integrity Guidelines list as prohibited content "created using automated means, including but not limited to content generated using artificial intelligence."
- In practice, IngramSpark treats this as a single binary: a book is either AI-generated or it is not. **There is no "AI cover only" option.** If your cover is AI, you must declare the whole book partially AI-generated.
- This is the strictest of the major distributors. If you use IngramSpark for paperback distribution, weigh this seriously.

### Draft2Digital
- Will not accept content "generated entirely by AI/LLMs that has not gone through extensive editing from a human."
- Their language focuses on the manuscript more than the cover, but human involvement is expected.

### Apple Books, Kobo, Barnes & Noble
- Less explicit policies as of May 2026. Standard practice: disclose AI generation where the platform asks; assume the KDP-style rule applies.

---

## The Copyright Problem (Read This Twice)

This is the single most important section.

In **Thaler v. Perlmutter**, the DC Circuit ruled in 2025 that purely AI-generated works do not meet the human-authorship requirement for US copyright. **On March 2, 2026, the Supreme Court declined to review the case.** That makes the rule settled law for now.

**What this means for your covers:**
- A cover generated purely from a prompt **cannot be registered** with the US Copyright Office.
- That does not mean you can't *use* the cover. You can. The platform license is real.
- It does mean **anyone else can also use a similar image without you being able to stop them.**

**How to get copyright protection on an AI cover:**
The Copyright Office has stated that copyright can attach to AI-involved works **where a human makes creative, expressive choices** — selecting, editing, arranging, modifying, or combining AI-generated elements in a way that reflects creative judgment.

**Practical translation for indie authors:**
- Generate the base image in AI.
- Bring it into Photoshop / Affinity / Canva.
- Do real human design work — composite multiple images, hand-paint adjustments, add custom typography, color-grade, retouch, layer.
- Document what you did (a "Creative Audit Trail").
- The *combined* cover — image + your human design work — has a much stronger copyright claim than the raw AI output alone.

> **The cleanest path:** Treat AI output as a stock image you have license to use. Then design the cover around it the way a human cover designer would. The design work is yours, and that is what gets copyright.

---

## The Likeness / Third-Party IP Problem

The platform license **does not** shield you from these.

**Real people (celebrities, models, anyone identifiable):**
Right of publicity is a legal right every person has — not just celebrities. Using AI to generate a cover that looks like a real person, without permission, is the same legal risk as photographing them and slapping their face on your book. **Don't do it.** Especially do not prompt for the names of actors, athletes, public figures, or BookTok-famous cover models.

**Copyrighted characters:**
No Marvel, Disney, Pixar, anime franchises, video game characters, or recognizable trademarked imagery. The Disney/Universal v. Midjourney lawsuit is still in court, but the lesson for authors is already clear: even if Midjourney loses, **you** are still liable for what you publish.

**Living artists' styles:**
Several tools (DALL-E most explicitly) prohibit prompts that name living artists. Even where the tool permits it, "in the style of [Living Artist Name]" is a fast path to trouble. Period-of-art styles ("art nouveau," "1920s pulp," "PreRaphaelite") are safer because they describe an era, not a person.

---

## The CPH Decision Matrix (Practical Use)

For making a real decision on a CPH/TIP cover, run through these in order:

1. **Where is this going to be sold?**
   If KDP only: most tools are fine, just disclose.
   If IngramSpark: be aware your book is flagged partially-AI overall.

2. **Do you need legal cover (pun intended)?**
   If yes — high-profile project, traditional review, or you want the lowest risk: **Adobe Firefly** on Creative Cloud. Indemnification is the only meaningful protection.

3. **What aesthetic do you need?**
   - Romance / fantasy / lush atmospheric: Midjourney, Grok, Ideogram, or fine-tuned SDXL.
   - Clean composition / faces / photorealistic: Gemini Imagen, DALL-E.
   - Title text rendered on the image: Ideogram (still the leader).
   - Character consistency across a series: Leonardo with model presets.
   - Inside an existing design workflow: Canva AI or Adobe Firefly.

4. **Will the cover be copyrighted?**
   If you want a registrable copyright: AI output is your *starting point*, not your finish line. Plan to do meaningful human design work after generation, and keep records of what you did.

5. **Will it look like anyone real?**
   If yes, change it before you publish. No exceptions.

6. **KDP disclosure box:**
   Click it. Failure to disclose is what gets books pulled, not the disclosure itself.

---

## Quick Reference Table

| Tool | Commercial use | IP indemnification | Best for | Biggest watch-out |
|---|---|---|---|---|
| Ideogram | All tiers, free OK | No | Text on image | Third-party IP is your problem |
| Grok / Aurora | All tiers, free OK | No | Permissive content filter | xAI trains on your prompts |
| Gemini / Imagen | All tiers, free OK | No | Realism, composition | Same copyright limits |
| Midjourney | Paid only | No | Atmospheric romance/fantasy | Active Disney lawsuit; $1M rule |
| DALL-E (ChatGPT) | Paid (Plus+) | No | Stylized illustration | No real people / living artist styles |
| Leonardo AI | Paid only | No | Character consistency | Free tier = no commercial use |
| SDXL (Stable Diffusion) | All uses, no caps | No | Free, ecosystem | Check fine-tuned model licenses |
| Canva AI (Magic Media) | Pro/Teams | No | Finish-cover-in-tool | No exclusivity to output |
| **Adobe Firefly** | **All paid CC plans** | **Yes (paid plans)** | **Lowest legal risk** | **Aesthetics weaker than Midjourney** |

---

## Open Questions / Things to Watch (May 2026)

These are not settled yet. Worth tracking:

- **Disney/Universal v. Midjourney** — first major studio test of AI training data. Outcome could reshape what these tools are even allowed to generate.
- **State-level publicity laws.** Tennessee's ELVIS Act and similar laws in CA and IL are expanding right-of-publicity to cover AI-generated likenesses specifically.
- **EU AI Act.** Disclosure requirements in the EU are stricter than US. If you sell in Europe, this matters.
- **KDP enforcement.** As of 2025–2026, Amazon has stepped up enforcement of the disclosure rule. Disclose, don't gamble.

---

## Sources

- [Amazon KDP Content Guidelines](https://kdp.amazon.com/en_US/help/topic/G200672390)
- [Amazon KDP AI Disclosure Policy 2026 — Inkfluence AI](https://www.inkfluenceai.com/blog/amazon-kdp-ai-disclosure-policy-2026)
- [Authors Guild on KDP AI Disclosure](https://authorsguild.org/news/amazons-new-disclosure-policy-for-ai-generated-book-content-is-a-welcome-first-step/)
- [Ideogram Terms of Service](https://ideogram.ai/legal/tos)
- [Ideogram Usage Policy](https://ideogram.ai/legal/usage-policy)
- [Grok / xAI Image Generation Commercial Use — LicenseOrg](https://www.licenseorg.com/blog/grok-xai-image-generation-commercial-use-policy)
- [xAI Grok Image Generation Release](https://x.ai/news/grok-image-generation-release)
- [Google Gemini Commercial Rights — Terms.Law](https://terms.law/ai-output-rights/gemini/)
- [Midjourney Terms of Service](https://docs.midjourney.com/hc/en-us/articles/32083055291277-Terms-of-Service)
- [Midjourney — Using Images & Videos Commercially](https://docs.midjourney.com/hc/en-us/articles/27870375276557-Using-Images-Videos-Commercially)
- [OpenAI Terms of Use](https://openai.com/policies/row-terms-of-use/)
- [DALL-E Commercial Rights — Terms.Law](https://terms.law/ai-output-rights/dall-e/)
- [Leonardo AI Terms of Service](https://leonardo.ai/terms-of-service)
- [Leonardo AI Commercial Usage Help](https://intercom.help/leonardo-ai/en/articles/8044018-commercial-usage)
- [Stability AI License](https://stability.ai/license)
- [SDXL License on Hugging Face](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/LICENSE.md)
- [Canva Content License Agreement](https://www.canva.com/policies/content-license-agreement/)
- [Canva AI Product Terms](https://www.canva.com/policies/ai-product-terms/)
- [Adobe Firefly Legal FAQs](https://www.adobe.com/content/dam/dx/us/en/products/sensei/sensei-genai/firefly-enterprise/Firefly_Legal_FAQs_Enterprise_Customers.pdf)
- [Adobe Firefly Indemnification — LicenseOrg](https://www.licenseorg.com/blog/adobe-firefly-indemnification-explained)
- [US Copyright Office on AI](https://www.copyright.gov/ai/)
- [Supreme Court Denies Cert in Thaler — Mayer Brown](https://www.mayerbrown.com/en/insights/publications/2026/03/supreme-court-denies-review-in-ai-authorship-case)
- [IngramSpark Catalog Integrity Guidelines](https://www.ingramspark.com/blog/ingramsparks-catalog-integrity-announcement)
- [Draft2Digital FAQ](https://draft2digital.com/faq/)
- [Disney & Universal v. Midjourney — Georgetown Tech Institute](https://www.law.georgetown.edu/tech-institute/research-insights/insights/disney-nbc-universal-and-dreamworks-file-major-ip-lawsuit-against-ai-image-generator-midjourney/)

---

*Compiled for Jessica Waldron / Clark Publishing House / The Invisible Pen — May 12, 2026. Verify any specific platform TOS before relying on this guide for a high-stakes publishing decision. This is research, not legal advice.*
