# Deployment

This is a static HTML/CSS site and can be hosted on any standard static host.

## Minimum launch sequence
1. Choose and register a custom domain.
2. Upload the contents of this folder to the hosting provider's public web root.
3. Replace `YOUR-DOMAIN.example` in `sitemap.xml` and `robots.txt`.
4. Enable HTTPS.
5. Test:
   - Home navigation
   - Mobile menu
   - Call button
   - WhatsApp order button
   - Google Maps link/embed
   - Gallery lightbox
   - Payment QR image
6. In Google Search Console, add the final domain as a Domain property and complete DNS verification.
7. Submit `https://YOUR-DOMAIN.example/sitemap.xml`.
8. Update the Google Business Profile website URL to the final domain.

## Domain/hosting access required
To actually connect the domain and publish the site, the owner must provide/perform the domain registrar and hosting login or DNS changes. Never put passwords or verification tokens in this package.
