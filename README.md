# LinkeInCommunityManagementAPI-AirVision
This is a code‑only integration (no public UI yet). 

The repository below contains:

• OAuth flow (authorization URL → token exchange → refresh) • Calls to /rest/organizations?q=vanityName and /rest/organizationalEntityFollowerStatistics • Postman collection + environment • README with exact steps to run locally • Mock JSON responses showing the fields we read (e.g., organicFollowerCount)

Test login details: N/A — there is no end‑user account or dashboard. This is an internal, single‑tenant tool for AirVision’s own page. Until Community Management API access is approved, the analytics endpoints return 403, so the code is provided for review instead of a live UI.

Scopes requested: r_organization_social (analytics) (w_organization_social may be added later only for posting to our own page)

Headers used: LinkedIn-Version: 202405 X-Restli-Protocol-Version: 2.0.0

Compliance: Single organization (AirVision) only. No client management, no data resale, no scraping.
