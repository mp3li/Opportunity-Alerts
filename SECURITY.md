# Security and privacy

Opportunity Alerts keeps account data and watched webpages in private dashboards. Only public webpages can be monitored; the service does not ask for passwords to the sites being watched. Webpage content is treated as untrusted and displayed as text.

Account access is checked for private actions. Authentication, request limits, destination validation, and bounded fetching are part of the service design. These controls are tested, but no software can be promised free of vulnerabilities. The application source and production configuration are private.

Members can export their data or delete their account. Deletion removes live application data; provider recovery copies may retain deleted data for up to 30 days. Cloudflare processes the data needed to host the service. This is not end-to-end encryption. No advertising trackers or third-party analytics SDKs are included.
