SNAPFOLD CO. WEBSITE — ZERO-COST STATIC STARTER

Included:
- Responsive single-page agency website
- Services, approach, illustrative portfolio concepts, about and enquiry sections
- Basic page title and description
- Mobile navigation
- Enquiry form that opens the visitor's email application (it does NOT store or transmit leads)

IMPORTANT BEFORE PUBLISHING:
1. Replace the mailto destination in script.js with your real business email:
   Change window.location.href=`mailto:?subject=${subject}&body=${body}`;
   to window.location.href=`mailto:YOUR-EMAIL@example.com?subject=${subject}&body=${body}`;
2. Confirm your actual service capabilities, business contact details, legal business identity and service areas.
3. The portfolio visuals are illustrative concepts, not completed client work. Keep the disclosure note unless replaced with genuine work and permission.
4. Do not publish invented testimonials, client logos, addresses, phone numbers or performance claims.
5. Add a privacy policy before collecting personal information or using analytics/advertising trackers.

DEPLOY TO CLOUDFLARE PAGES (FREE STATIC HOSTING):
A. Create a GitHub account and a new public or private repository named snapfoldco-website.
B. Upload index.html, styles.css, script.js, favicon.svg.
C. In Cloudflare, open Workers & Pages > Create > Pages > Connect to Git.
D. Select the repository. Framework preset: None. Build command: leave blank. Build output directory: / (or the repository root, as the dashboard specifies).
E. Deploy.
F. In the Pages project, open Custom domains and add snapfoldco.com. Follow Cloudflare's DNS instructions. Add www.snapfoldco.com too if desired and configure a redirect to the primary domain.
G. Keep the domain registered at Spaceship. You do not need to transfer it. Change DNS records only as Cloudflare instructs; avoid deleting existing email-related records.

No deployment or DNS changes have been made by this package. Domain connection requires access to your Cloudflare and Spaceship accounts and your explicit approval.
