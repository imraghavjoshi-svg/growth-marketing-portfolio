# Newsletter Article – Kevin Indig

**Name:** Kevin Indig
**Source:** Growth Memo Newsletter
**URL:** https://www.growth-memo.com/p/the-science-of-what-ai-actually-rewards
**Date:** 30 March 2026

---

## Article Title: The Science of What AI Actually Rewards

Most AI SEO writing advice doesn't hold at scale. This memo breaks down what AI actually rewards inside the content it reads and across verticals.

This Memo was sent to 25,823 subscribers. In The science of how AI pays attention, I analyzed 1.2 million ChatGPT responses to understand exactly how AI reads a page. In The science of how AI picks its sources, I analyzed 98,000 citation rows to understand which pages make it into the reading pool at all.

This is Part 3.

Where Part 1 told you where on a page AI looks, and Part 2 told you which pages AI routinely considers, this one tells you what AI actually rewards inside the content it reads.

The data clarifies:

Most AI SEO writing advice doesn't hold at scale. There is no universal "write like this to get cited" formula - the signals that lift one industry's citation rates can actively hurt another.

The entity types that predict citation are not the ones being targeted. DATE and NUMBER are universal positives. PRICE suppresses citation in 5 of 6 verticals and KG-verified entities are a negative signal.

The one writing signal that holds across all 7 verticals: Declarative language in your intro, +14% aggregate lift.

Heading structure is binary. Commit to the right number for your vertical or use none. 3-4 headings is worse than zero in every vertical.

Corporate content dominates. Reddit doesn't. AI citation behavior does not mirror what happened to organic search in 2023-2024.

---

## 1/ Specific writing signals influence citation, while others harm it.

While The science of how AI pays attention covers parts of the page and types of writing that influences ChatGPT visibility, I wanted to understand which writing-level signals - word count, structure, language style - predict higher AI citation rates across verticals.

Approach
I compared high-cited pages (3+ unique prompt citations) vs low-cited across 7 writing metrics: word count, definitive language, hedging, list items, named entity density, and intro-specific signals.

I analyzed the first 1000 words for list item count, named entity density, intro definitive language token density, and intro number count.

Results: Across all verticals, definitive phrasing and including relevant entities matter. But most signals are flat.

What the industry patterns showed:
- Total word count was strongest in CRM/SaaS (1.59x).
- Finance was an anomaly with word count: Shorter pages win (0.86x word count).
- Definitive phrases in the first 1K characters was positive for most verticals.
- Education is a signal void. Writing style explains almost nothing about citation likelihood there.

Top takeaways:
1/ There is no universal 'write like this to get cited' formula. For example, the signals that lift CRM/SaaS citation rates actively hurt Finance. Instead, match content format to vertical norms.

2/ The one universal rule: open with a direct declarative statement. Not a question, not context-setting, not preamble. The form is "[X] is [Y]" or "[X] does [Z]." This is the only writing instruction that holds regardless of vertical, content type, or length.

3/ LLMs "penalize" hedging in your intro. "This may help teams understand" performs worse than "Teams that do X see Y." Remove qualifiers from your opening paragraph before any other optimization.

---

## 2/ The entity types that predict citation are not the ones being targeted.

Most AEO advice focuses on named entities as a category: pack in more known brand names, tool names, numbers. The cross-vertical entity type analysis below tells a more specific (and more useful) story.

Approach
Ran Google's Natural Language API on the first 1,000 characters (about 200-250 words) of each unique URL.
Computed lift per entity type: % of high-cited pages with that type / % of low-cited pages.
Analyzed 5,000 pages across 7 verticals.

Results: DATE and NUMBER are the most universal positive signals. Interestingly, PRICE is the strongest universal negative.

What the industry patterns showed:
- DATE is the most universal positive signal, with the exception of Finance (0.65x).
- NUMBER is the second most universal. Specific counts, metrics, and statistics in the intro consistently predict higher citation rates. Finance (0.98x) and Product Analytics (1.10x) mark the floor and ceiling of that range.
- PRICE is the strongest universal negative. Pages that open with pricing signal commercial intent. Finance is the sole exception at 1.16x, likely because price here means fee percentages and rate comparisons, which are the actual reference data financial queries are looking for.
- CONSUMER_GOOD (software/product entities) is mixed. In Healthcare, product entities signal established brands and tools. In Crypto, naming specific protocols and products is core to answering technical queries.
- PHONE_NUMBER is a positive signal in Healthcare (1.41x) and Education (1.40x). In both cases, it is almost certainly a proxy for established brands/institutions/providers with real physical presence, not a literal signal to add phone numbers to your pages.

The Knowledge Graph inversion:
The data showed that high-cited pages average 1.42 KG-verified entities vs. 1.75 for low-cited pages (lift: 0.81x).
Pages built around well-known, KG-verified entities (major brands, institutions, famous people) tend toward generic coverage, which isn't preferred by ChatGPT.
High-cited pages are dense with specific, niche entities: a particular methodology, a precise statistic, a named comparison. Many of those niche entities have no KG entries at all. That specificity is what AI reaches for.

Top takeaways:
1/ Add the publish date to your pages and aim to use at least one specific number in your content. That combination is the closest thing to a universal AI citation signal this dataset produced.

2/ Avoid opening with pricing in non-Finance verticals. Price-dominant intros correlate with lower citation rates.

3/ KG presence and brand authority do not translate to AI citation advantage. Chasing Wikipedia entries, brand panels, or KG verification is the wrong lever. Specific, niche entities (even ones without KG entries) outperform famous ones.

---

## 3/ Heading structure: Commit to one or don't bother.

Approach
Counted total headings per page (H1+H2+H3) across all cited URLs.
Grouped pages into 7 heading-count buckets: 0, 1-2, 3-4, 5-9, 10-19, 20-49, 50+.
Computed high-cited rate (% of URLs that are high-cited) per bucket per vertical.

Results: Including more headings in your content is not universally better. The sweet spot depends on vertical and content type. One finding holds everywhere: 3-4 headings are worse than zero.

What the industry patterns showed:
- CRM/SaaS is the only vertical where the 20+ heading lift is confirmed: 12.7% high-cited rate at 20-49 headings vs. a 5.9% baseline. The 50+ bucket reaches 18.2%.
- Healthcare inverts most sharply. The high-cited rate drops from 15.1% at zero headings to 2.5% at 20-49 headings.
- Finance peaks at 10-19 headings (29.4% high-cited rate).
- Crypto peaks at 5-9 headings (34.7% high-cited rate).
- Education is flat across all heading counts.
- The 3-4 heading dead zone holds across every vertical without exception.

Top takeaways:
1/ The 20+ heading finding from Part 1 is a CRM/SaaS finding, not a universal one.

2/ The principle that holds everywhere: Commit to structure or don't use it. The middle ground costs you in every vertical.

3/ Use the optimal heading range for your vertical:
- Crypto: 5-9
- Finance and Education: 10-19
- CRM/SaaS: 20+ (with H3s)
- Healthcare: 0 or 5-9 at most

---

## 4/ UGC doesn't dominate

Approach
Classified cited URLs as UGC (Reddit, Quora, Stack Overflow, forum subdomains, Medium, Substack, Product Hunt, Tumblr) or corporate/editorial by domain.
Computed citation share per category per vertical.
Dataset: 98,217 citations across 7 verticals.

Results: Corporate content accounts for 94.7% of all citations. UGC is nearly invisible.

What the industry patterns showed:
- Finance is the most corporate-locked vertical at 0.5% UGC.
- Healthcare sits at 1.8% UGC.
- Crypto has the highest UGC penetration in the dataset at 9.2%.
- Product Analytics and HR Tech sit at 6.9% and 5.8% UGC.

Top takeaways:
1/ The "Reddit effect" in SEO has not translated proportionally to AI citations. In most verticals, reddit.com captures 2-5% of total citations.

2/ For Finance and Healthcare: UGC has near-zero AI citation value.

3/ For Crypto, Product Analytics, and HR Tech: Community presence has measurable citation value.

---

## What this means for how you strategize for LLM visibility

Across all 3 parts of this study, the consistent finding is that AI citation is not primarily a writing quality problem.

Part 2 showed it is a content architecture problem: Thin single-intent pages are structurally locked out regardless of how well they're written. This piece shows the same logic applies inside the content itself.

The aggregate writing signals table is the most important chart in this analysis. Not because it shows you what to do, but because it shows how much of what the AI SEO/GEO/AEO industry is telling you doesn't survive cross-vertical scrutiny. Word count, list density, named entity counts all flat or negative at the aggregate. The signals that work are vertical-specific and smaller than our industry's consensus implies.

The meta-lesson from this analysis is that findings are vertical and probably topic specific, which is no different in SEO.

---

## Methodology

We analyzed ~98,000 ChatGPT citation rows pulled from approximately 1.2 million ChatGPT responses from Gauge.

Because AI behaves differently depending on the topic, we isolated the data across 7 distinct, verified verticals:
- B2B SaaS
- Finance
- Healthcare
- Education
- Crypto
- HR Tech
- Product Analytics