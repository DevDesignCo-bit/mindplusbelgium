# Mind+ Belgium — local review build

Confirmed offer: MOBYRION / Mind+; EUR 4.00 VAT included; one-off purchase; 1 calendar month of access; 18+.

Open index.html for French, or nl/index.html for Dutch. The language links retain the current page. Mobile and desktop share the same responsive stylesheet; desktop has no outer frame.

## Required before launch

- Replace [MOT-CLÉ] / [TREFWOORD] and [NUMÉRO COURT] / [VERKORT NUMMER] with the assigned SMS keyword and shortcode in both landing pages. Replace the requested visual-example number 3456 in both pictograms and update their accessible labels. 3456 is an explicitly requested visual example, not an assigned shortcode. No real SMS keyword has been invented.
- Pictogram uses the supplied Price.png once per landing, at its original 101 x 69 aspect ratio. No SVG or HTML price stamp is layered over it. Validate the final supplied artwork and assigned shortcode with the provider.
- This build has no payment API, SMS sending, SMS URI, MSISDN web form, user tracking, affiliate tracking or fake payment confirmation. The main button links directly to https://mindplus.store as requested. activation.html remains an unlinked draft manual-SMS instruction page with activation details still pending. The PSMS provider must supply the real single opt-in activation, charge, access link and transaction records.
- Configure the actual provider-side EUR 10 spending reminder for one-off purchases as required in the brief. A browser timer or local-storage counter cannot implement that requirement. Verify thresholds, aggregation and SMS content with the provider.
- Put the SAME General Terms and Impressum links at the bottom of the actual content portal. The live portal was not modified. Use its real deployed Belgium URLs; portal-footer-fr.html and portal-footer-nl.html are integration snippets with an explicit base URL placeholder.
- The legal pages are review drafts adapted to this confirmed one-off offer; they do not reuse the German subscription terms. MOBYRION's SIREN, registered office, SAS status, capital and president were checked against the INPI/RNE record of 20 November 2026. The French VAT identifier FR51934316720 is corroborated by public company records. This is not proof of OSS enrollment; confirm any Belgium-specific tax identifier with Finance/provider. Confirm the consumer information, withdrawal process, final privacy page and launch URLs with the business owner.
- No promotional banner was requested in a specific format. When making one: use content-specific cognitive-game graphics, the same real shortcode/price pictogram at top right, Mind+ by MOBYRION, EUR 4 incl. VAT one-off, 1 month access and telecom invoice payment. Affiliate marketing is forbidden per the supplied brief.

## Sources

- Provider brief supplied in the conversation.
- MNO Message Service guidelines, December 2023, sections 1.2, 3.3 and 3.13–3.13.2: https://www.orange.be/sites/b2c/files/2024-01/Directives%20MNO%20Services%20messagerie_FR%20V2%20DEC%202023%20FINAL.pdf
- Dutch guidelines: https://www.scarlet.be/dam/jcr%3A4bec5cd1-b9c0-4234-bb3a-61d2a424c6b8/cdn/sites/iportal/documents/pdfs/common/GOF_Guidelines_NL_Final_08082011~2024-02-12-09-42-27~cache.pdf

The setup fees, service-ID fees and VAT settlement instructions are business matters and are not shown to consumers on the landing page.

## Supplied PDF reviewed on 20 November 2026

AAA_NEW_GOF_MNO Message Service guidelines_December 2023_v2(1).pdf, page 18, section 3.13.1: graphical diagram shows horizontal units 1 + 22 + 1 and vertical units 1 + 2 + 6 + 2 + 4 + 1. The earlier SVG implementation used this diagram; it has now been replaced by the user-supplied Price.png artwork. The assigned shortcode remains pending. This graphical adjustment does not constitute full legal or provider approval.

## Confirmed service URL and pending fiscal identifier

The service URL https://mindplus.store/ was confirmed by the user and added visibly to both language versions and their legal pages. EU372075222 was supplied tentatively as a possible MOSS identifier; ownership/applicability has not been confirmed and it has not been inserted into consumer-facing pages. Confirm with Finance or Suzana before publishing that identifier.

## Provider changed to MOBYRION — 20 November 2026

User confirmed MOBYRION as the supplier. Verified INPI/RNE: MOBYRION; SIREN 934 316 720; SAS; capital EUR 1,000; registered office 14 bis rue Daru, 75008 Paris, France; president Michel Guillemot. French VAT number listed by Pappers: FR51934316720. Updated all six FR/NL landing and legal HTML pages, provider labels and copyright. Belgian customer-care contacts and service URL remain as supplied. The tentative EU372075222 MOSS number has not been assigned to MOBYRION without verification. SIREN and French VAT identification do not establish OSS registration.

Sources:
- INPI/RNE: https://data.inpi.fr/export/companies?format=pdf&ids=%5B934316720%5D
- https://www.pappers.fr/entreprise/mobyrion-934316720

## Simplified reference layout — 20 November 2026

- Rebuilt the landing to match the supplied simple reference: image, language switch at top left, logo centred, blue number/price pictogram at top right, short CTA, one price line, one plain disclaimer paragraph and four footer links.
- Retained MOBYRION and its current identifiers instead of the old Playwing data visible in the screenshot. No unconfirmed MOSS identifier was published.
- Uses Hero Image FR.png and Hero Image NL.png unchanged, with a CSS fade. Labels are baked into the supplied artwork; no HTML skill labels are overlaid. A single supplied Price.png appears at the top right.
- CTA: Accéder (FR) / Doorgaan (NL). It links directly to https://mindplus.store. The landing does not send or prefill any SMS.
- Footer: local terms.html, impressum.html, faq.html, contact.html, also in nl/. Auxiliary pages use the Mind+ dark teal style. FAQ content is adapted to one-off purchases. Contact includes the supplied support channels and a link to the live Mind+ contact form.
- Live https://mindplus.store/info/terms and /info/faq were reviewed: they still describe recurring subscriptions and Playwing, so those generic pages were not used as the Belgian legal/FAQ destinations. The live site itself was not edited.
- The real portal https://mindplus.store/ remains linked from the logo/disclaimer, and the privacy page is linked from the local terms. The portal footer integration is still a separate required provider-side change.

## Supplied final artwork and requested edits - 20 November 2026

The FR/NL hero images and price pictogram are used unchanged, with no duplicate graphic labels or price stamps. Main CTA destination: https://mindplus.store. Removed the RCS, legal-form and share-capital rows from both Impressum pages as requested; SIREN and the other company/contact details remain.

Latest presentation update: centre the hero heading and offer on desktop and mobile; display the price summary in semibold (font-weight: 600) in both languages.

CTA animation: gentle 2.8-second pulse, maximum scale 1.025 and subtle blue glow; disabled with prefers-reduced-motion.

## Expanded Belgian terms and high-resolution artwork - 20 November 2026

Expanded both terms pages to 14 original sections, covering the offer, eligibility, duration, order, payment, access, support, use, conformity, intellectual property, privacy, withdrawal, updates and supplier. The live terms were used for comparison; subscription language, placeholders and Playwing details were not imported. The one-off Belgian offer remains EUR 4 VAT included for one month, 18+, supplied by MOBYRION. No automatic withdrawal waiver is asserted. The provider must implement the actual purchase confirmation and applicable withdrawal process; these static pages do not implement a transaction backend.

Sources checked:
- https://mindplus.store/info/terms
- https://economie.fgov.be/fr/themes/ventes/reglementation/delais-de-retractation/droit-de-retractation-lors-de
- https://economie.fgov.be/fr/themes/entreprises/guidance/pratiques-commerciales/obligations-dinformation-dans/questions-frequemment-posees

The supplied FR/NL hero PNG files are now 1176 x 1347 pixels. They are kept unchanged at full resolution, with matching intrinsic HTML dimensions and the existing responsive display sizes. Price.png remains a single separate pictogram.

Landing disclaimer simplification: removed the SIREN/RCS, VAT identifier and president from both landing pages at the user’s request. Those details remain in the legal pages; the supplier name, address and customer-care details remain on the landing.

Desktop pictogram positioning: the single supplied price image is now a direct child of the landing and sits at its top-right corner (20 px top, 24 px right) at widths of 800 px and above. Mobile retains its existing 10 px top/right offsets within the centred landing. It is no longer constrained or clipped by the hero image column.

Desktop pictogram placement refined to the annotated reference: the single price image now anchors to the top-right of the hero content grid, above the text column, rather than the viewport edge. At widths below 800 px, the same 10 px top/right mobile offsets apply.
