# Signal story of Myasthenia Gravis

An expanded interactive learning game about normal neuromuscular transmission and myasthenia gravis (MG). It replaces the earlier Little Matches game while adding a vibrant violet, teal and coral visual style. The standalone download keeps its existing filename, `mg_little_matches.html`; its contents are now Signal Story. The GitHub entry file is `index.html`.

## The four chapters

1. **Normal transmission:** send a nerve impulse; release ACh after calcium enters the nerve; bind ACh to muscle receptors; trigger the muscle’s electrical signal; contract the muscle; clear ACh.
2. **What MG changes:** reveal the immune attack, receptor blockade, receptor removal and complement-mediated surface damage; test the weakened connection.
3. **Activity & rest:** send six repeated messages, compare the received signal with and without MG, take a break, and test temporary recovery.
4. **Build the story:** reconstruct the normal pathway in order, then answer three questions about MG and the phone analogy. Mistakes provide clues and allow retries.

Every step includes a plain-language explanation. **The scientific terms** expands the technical detail. The **Phone analogy / In the body** switch changes the illustration without resetting progress. Completed chapters remain available for review.

The phone comparison maps the nerve ending to a sender and the muscle receiving system to a receiver. It does not equate MG to poor Wi-Fi, a flat battery, or lack of effort. The game explicitly explains the limits of the comparison.

## Play locally

Extract the ZIP and open `index.html` in a modern browser with JavaScript enabled. No installation, account, API key, build command, or internet connection is needed to play. Source links require internet access.

- Use the large action button to reveal each step, then select **Next step** when ready.
- Use **Previous step** or an unlocked chapter to review completed material.
- Keyboard: Tab moves between controls; Enter or Space activates buttons; Escape closes the guide.
- **Reduce motion** removes animations; the system preference is also respected.
- There is no timer, score penalty, login, tracking, or saved progress. Reloading starts again.

## Upload to GitHub Pages

1. Extract the ZIP. Upload the extracted files, not the ZIP itself.
2. In your game repository, replace `index.html` at the top level. Include this `README.md` and `.nojekyll` if visible. Commit to `main`.
3. For a new repository, open **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**, and save.
4. Use the published address shown in Pages settings after deployment finishes. An existing Pages site updates after the new commit deploys.

GitHub Free supports Pages in public repositories. Official setup instructions: [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

To embed the published game, use your website editor’s iframe feature with the game URL, 100% width, sufficient height, and scrolling enabled. A direct link gives phone users more room.

## Scientific scope

The MG mechanism illustration represents **AChR-antibody MG**, not every MG subtype. The three antibody effects can overlap; presenting them sequentially does not imply a fixed biological order. Each pictured receptor represents many receptors. The response bars use invented values and a teaching threshold, not clinical measurements or percentages. They represent the signal that may trigger an action potential; action potentials themselves are all-or-none.

The normal pathway separates rapid, overlapping processes for learning. ACh breakdown occurs quickly during activation. A real movement involves many impulses and muscle fibres. Calcium entering the nerve ending and calcium released inside the muscle are different steps. Rest may temporarily improve transmission but does not instantly repair receptors, remove the immune attack, or cure MG. Symptoms vary.

## Sources

The in-game guide links to these sources and includes the full pathway, an analogy mapping table, and model limitations:

- [NINDS: Myasthenia Gravis](https://www.ninds.nih.gov/health-information/disorders/myasthenia-gravis)
- [UTHealth: Synaptic transmission at the skeletal neuromuscular junction](https://nba.uth.tmc.edu/neuroscience/s1/chapter04.html)
- [Rodríguez Cruz et al. (2020): The neuromuscular junction in health and disease](https://pmc.ncbi.nlm.nih.gov/articles/PMC7744297/)
- [OpenStax: Skeletal muscle](https://openstax.org/books/anatomy-and-physiology-2e/pages/10-2-skeletal-muscle)
- [OpenStax: Muscle contraction and relaxation](https://openstax.org/books/anatomy-and-physiology-2e/pages/10-3-muscle-fiber-contraction-and-relaxation)
- [Kaminski et al. (2024): Myasthenia gravis — the future is here](https://www.jci.org/articles/view/179742)
- [Conti-Fine et al. (2006): Myasthenia gravis — past, present, and future](https://www.jci.org/articles/view/29894)

## Files and editing

| File | Purpose |
| --- | --- |
| `index.html` | The complete game, including styles, JavaScript, and original SVG illustrations. |
| `README.md` | These instructions. |
| `.nojekyll` | Optional plain static-file marker for GitHub Pages. |

No third-party fonts, images, libraries, or analytics are loaded. The CSS colour variables appear near the top; the `normal`, `mg`, `sequence`, and `questions` arrays hold the learning content. Keep the scientific qualifications and source links when editing.

Created with AI assistance. Record its use if required by your assessment.

Version 2 (Signal Story expansion) · 25 October 2026.
