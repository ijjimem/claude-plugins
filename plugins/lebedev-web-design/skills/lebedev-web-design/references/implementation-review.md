# Implementation and review

These are this skill's implementation recommendations, not an official studio checklist. Apply checks to the requested task and its real risks. The studio evidence and reference-verification method are in [design-research.md](design-research.md); historical reasoning is in [mandership-guide.md](mandership-guide.md), and the complete website workflow is in [website-workflow.md](website-workflow.md).

## Make the concept executable

Use original, factually grounded copy, representative assets, and real states to refine the composition before turning it into reusable styles. Name colors and type styles by their roles; the quantity follows the design, not a fixed quota. Use the existing system for an explicitly limited edit; a broader rebuild can establish a new system.

For a larger website, prove the direction on the homepage and a relevant internal page or task, such as a catalog/detail pair, article, audience section, or booking form. Identify needed navigation, data, and content states. Do not invent backend functionality to make a mockup appear complete.

For media and motion, identify the intended experience, required assets, crop behavior, loading strategy, and fallback. Prototype uncertain behavior early. Reserve space for loading assets, keep content accessible while optional resources load, and make reduced-motion alternatives preserve the useful information. Do not silently replace a requested animated concept with a still because it is easier.

## Preserve the scope of edits

Inspect how touched controls obtain data and trigger actions. Keep routes, form names and validation, destinations, commerce behavior, consent requirements, and tracking hooks outside the requested change intact. Use scoped styles when shared selectors could affect other pages or third-party widgets. Preserve the CMS's editable structure and requested publication state.

Preserve facts and content the user explicitly requires. A broad website creation or reinvention brief includes writing and restructuring content; inherited wording is not immutable. Flag significant factual contradictions. Use original, supplied, or licensed assets. Do not present missing connections as successful actions.

For a complete rebuild, map retained and changed URLs, content records, forms, data flows, transaction states, and event meanings before replacing the old implementation. Verify redirects and important entry paths, data continuity, editable content, and integration results after migration. Scope preservation protects what is outside the assignment; it does not require keeping the old layout, narrative, or architecture within an authorized rebuild.

## Review the rendered result

| Dimension | What to inspect |
| --- | --- |
| Proposition and strategy | Does the site explain its real purpose and offer to the intended audiences? Does each important page or function support a useful journey? |
| Task fit | Can the relevant visitor find, understand, compare, or complete what the brief requires? If the task is aesthetic, assess the requested character directly. |
| Art direction | Does the composition have an intentional voice? Is its restraint or richness appropriate? Do supporting pages and states belong to the same project? |
| Information architecture | Is the current location clear? Are categories, audience paths, labels, and destinations understandable? Are detail and comparison views useful? |
| Typography | Inspect real title lengths, leading, tracking, punctuation, captions, prices, units, and glyph coverage. Catch accidental line breaks and orphaned labels. |
| Content and authorship | Verify claims and product details; review original copy for specificity, voice, and coherence across the journey. Check headings, links, dates, and interface messages. Distinguish factual gaps and placeholders from finished content. |
| Original assets | Inspect generated or commissioned media in the layout, including small crops and responsive variants. Check visual coherence, fidelity to real products where claimed, licensing, meaningful alternative text, and editable text. |
| Responsive behavior | Review desktop and narrow phone widths; inspect intermediate widths where the composition changes. Check relevant content beyond the hero and avoid accidental horizontal overflow. |
| Interaction and accessibility | Test relevant keyboard and touch paths, visible focus, labels, menu/dialog behavior, and contrast. Inspect loading, empty, selection, validation, success, and error states where relevant. |
| Media and motion | Check cropping, loading, layout stability, touch alternatives, and reduced motion. Keep actions available without a compulsory introduction; sound requires user action. |
| Conversion and measurement | Check the complete intended action, comprehensible costs and terms, relevant proof, and confirmation. Verify that events distinguish clicks from successful outcomes; exclude test activity where appropriate. Record hypotheses separately from measured gains. |
| Discoverability | Verify relevant titles, descriptions, headings, internal links, canonical URLs, indexing state, redirects, sitemap entries, and structured data against actual content and publication status. |
| Edit regressions | Compare the same route and viewport before and after; inspect adjacent components affected by shared styles. |
| Operations and ownership | Check that the owner can edit and publish the required content, affected integrations work, and any migration or release has an appropriate recovery path. |
| Delivery | Run appropriate project checks and build instructions. Distinguish design review, compiled output, connected integration, and deployment. |

Use safe test data; a visual verification is not permission to submit a real lead or purchase. If a browser, backend, or device check cannot be completed, state the precise limitation rather than claiming that a successful build proves it.

Keep reference inspection separate from testing the delivered site. Record the actual route, viewport, state, action, and result for significant checks. A supplied mobile image or an embedded studio demo cannot substitute for testing the new implementation at narrow widths. Do not copy historical essay measurements or libraries as current technical requirements; verify applicable platform documentation when needed.

## Language and optical details

For RTL sites, use the correct document direction and logical spacing. Inspect mixed-direction numbers, prices, phone numbers, emails, punctuation, and directional icons. Validate actual glyph coverage and avoid imposing Latin tracking rules.

Use optical adjustments where they improve the design and survive content changes. Do not hard-code line-specific offsets, indiscriminate nonbreaking spaces, or decorative clipping that damages reading, selection, reflow, or assistive access. Review the actual text at the target widths.

## Correct observed problems

- An interchangeable marketing hero needs a more relevant idea or structure, not automatically more decoration.
- An information site overwhelmed by imagery needs clearer access to its content, not necessarily a bland identity.
- A monotonous composition may need variation in scale, rhythm, or format; comparison tables may legitimately need repetition.
- A striking but confusing control needs clearer behavior, labels, or feedback while retaining useful expression.
- A small restyle spreading into other pages needs narrower component boundaries.

Stop when the requested result and appropriate checks are complete; do not add speculative polish cycles or unrelated infrastructure changes.
