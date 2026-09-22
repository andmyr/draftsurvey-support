# Draft Survey Calculator — support page

The support page for the **Draft Survey Calculator** mobile app
(`ua.od.and.draftsurvey`), served by GitHub Pages at <https://support.and.od.ua/>.

This is the URL given as the **Support URL** in App Store Connect, which requires a page
rather than an e-mail address. It has to stay reachable for as long as the listing exists;
if it ever moves, leave a redirect behind.

`index.html` is the whole page — English, Ukrainian, Russian and Spanish in one document,
with anchor navigation. There is no build step and nothing to install: the file is served
exactly as it is committed, and `.nojekyll` keeps Jekyll from touching it.

The source of truth for this page, along with the reasoning behind its content and the
publishing runbook, lives in the application repository as `docs/support-page.html` and
`docs/support-page.md`. **Edit it there and copy the result here**, rather than editing
this copy directly — otherwise the two drift apart and the answer sheet stops describing
the page people actually read.

The privacy policy is a separate repository on the same pattern:
[`andmyr/draftsurvey-privacy`](https://github.com/andmyr/draftsurvey-privacy), served at
<https://privacy.and.od.ua/>. The two are kept apart deliberately — both URLs are App Store
submission blockers, and one repository holding both would mean a single mistake could take
both down.

Contact: Draft_Survey@and.od.ua
