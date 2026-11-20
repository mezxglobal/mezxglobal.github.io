# MezX Website — V8.1

A responsive, static website and interactive concept playground for the proposed MezX product ecosystem. Built with HTML, CSS and vanilla JavaScript; no build step or package manager is required.

## Included
- `index.html` — main brand website, interactive four-ring orbit, product explorer, illustrative dashboard, MFS framework selector and contact composer.
- `prototype-lab.html` — four interactive product demonstrations: MAI ledger sorting, MCI control review, MFI scenario sandbox and MFS framework explorer.
- `products/mai.html`, `products/mci.html`, `products/mfi.html`, `products/mfs.html` — individual product concept pages.
- `about.html` and `architecture.html` — venture overview and conceptual architecture.
- `website-data-note.html` — static-site data handling note.
- `favicon.svg`, `404.html`, `robots.txt` — site identity and GitHub Pages support files.
- `SECURITY.md` — limitations and data-handling cautions.

## Orbital interaction
Four independently animated orbital planes represent MAI, MCI, MFI and MFS. The MFS ring uses a layered metallic-gold edge, moving highlight, glow and pulse. Its clickable MFS control is a child of the gold ring, so it follows the ring as it moves. Drag the stage to rotate the constellation, use the ring-mode controls for an individual plane, use arrow keys for keyboard movement, and select reset to restore the default orientation. The animation pauses when the page is hidden and respects the visitor’s reduced-motion preference.

## Product playground
- **MAI:** sort fictional ledger entries and reset the demonstration.
- **MCI:** review fictional obligations and track progress.
- **MFI:** change sales-growth and cost assumptions to see a simplified illustrative index.
- **MFS:** select among ten distinct framework families, specify jurisdiction and reporting period, filter the library, run a local preview, save the setup in browser storage, or export a JSON configuration.

The ten MFS reference families are IFRS; jurisdiction-specific GAAP; IFRS S1/S2 (ISSB); ISA; Basel; FATF Recommendations; IOSCO Principles; G20/OECD Principles; relevant World Bank/UNCITRAL materials; and regional tax/VAT/GST/customs rule modules. They are not interchangeable and are not all accounting standards.

## Deploy to GitHub Pages
1. Extract the ZIP.
2. Upload the **contents** of the `mezx_v6` folder into the root of your GitHub repository (keep the `products/` folder).
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site.

No custom domain is assumed. The `404.html` page is included for GitHub Pages.

## Accuracy and production limits
MezX is presented as an early-stage venture and MAI/MCI/MFI/MFS are proposed product pillars. All charts, amounts, transactions and outcomes in the demos are fictional. Framework selection is a reference-organization concept, not an authoritative or automatically updated standards database, legal opinion, audit, filing, or compliance verdict. Local saving is browser/device-specific. The contact form opens an email draft; it does not transmit form data to a MezX server.

A production backend, authentication, database, integrations, verified standards feeds, server-side contact handling, security controls and independent compliance review are **not included** in this static GitHub Pages package. See `SECURITY.md`.

Contact: mezx.global@proton.me · https://www.linkedin.com/company/mezx
