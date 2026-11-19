# MezX Production Readiness Checklist

## Included in this GitHub Pages release
- Responsive static marketing site and navigation.
- Four independently animated orbital product rings, including the moving metallic-gold MFS ring and attached MFS button.
- Keyboard controls, focus indicators, reduced-motion support, and background-tab animation pause.
- Four interactive browser-only concept demonstrations.
- Ten selectable MFS framework families with jurisdiction/reporting-period context, filtering, local browser saving, and JSON export.
- GitHub Pages 404 page, favicon, and basic robots policy.

## Not included (requires separate infrastructure and product decisions)
1. **Backend/API:** GitHub Pages serves static files only. It cannot host a secure application server, scheduled jobs, or private API credentials.
2. **Authentication and roles:** no user accounts, organization workspaces, permissions, or session management.
3. **Database and storage:** no server-side customer records, financial documents, audit trails, or backups.
4. **Live financial standards:** no licensed/authoritative standards feed, version synchronization, jurisdictional rule engine, or legal update service. MFS selections are reference categories only.
5. **Accounting/compliance integrations:** no bank feeds, ERP/accounting connectors, regulator filing, tax calculation, or audit evidence ingestion.
6. **Contact delivery:** the contact form opens a prefilled email draft; it does not send data to a MezX server.
7. **Security and compliance assurance:** no penetration test, privacy/legal review, independent audit, or certification.

## Before accepting real customer data
Select the intended hosting and backend provider, define data residency and privacy requirements, appoint qualified financial/legal reviewers for the applicable jurisdictions, and implement authentication, authorization, encryption, input validation, audit logging, backups, retention/deletion controls, monitoring, incident response and independent security testing. Do not use the current prototypes for real financial records or compliance decisions.
