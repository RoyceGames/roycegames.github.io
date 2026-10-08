# RoyceGames website draft

This folder is a standalone GitHub Pages site for `roycegames.online`. It is **not ready to publish**: the visible draft banners, `noindex` tags, placeholder contact details, and incomplete privacy notice intentionally flag missing facts.

## Confirm before publication

1. Public publisher/controller name supplied: `RoyceGames`. Confirm its registered legal form and country/address before publication. The site is a shared publisher website and intentionally does not describe individual apps.
2. Replace the clearly inactive `support@example.com` and `privacy@example.com` placeholders with monitored public addresses. The GitHub login email is not treated as a public contact address.
3. The user says RoyceGames products will not collect player information through their own gameplay systems beyond third-party advertising SDK processing, and that iOS apps will show ATT. Verify this in each final binary. The user reports advertising through AppLovin, Meta, ironSource, Liftoff, Mintegral, Pangle, Unity, and Kwai; games are not directed to children and currently have no in-app purchases. Confirm the exact Kwai product/SDK, all mediation partners, CMP and US state opt-out mechanisms, and any analytics/crash components. Complete the privacy policy to match each game binary and store disclosures.
4. GitHub username `RoyceGames` was confirmed in Safari on October 8, 2026. Confirm the signed-in account again immediately before creating a repo or uploading. Confirm DNS control for `roycegames.online`.

Search for `[` and `Draft` before publishing. Remove the draft ribbons and `noindex` only after the page content is confirmed. The `CNAME` file already contains the intended domain.

## Privacy release checks

- Confirm RoyceGames' registered legal form and country or address, monitored support/privacy email, and effective date.
- Audit each shipping app and mediation dashboard for SDKs, versions, bidders, permissions, data categories, recipients, retention, and preceding 12-month California practices. Update the policy and store privacy disclosures accordingly.
- Implement an appropriate CMP for EEA/UK/Switzerland before the relevant SDKs initialize, with a way to withdraw consent. Pass choices to every participating network. Confirm the actual GDPR lawful basis per purpose and international transfer safeguards.
- Implement iOS App Tracking Transparency before tracking/IDFA access where required, and align App Store Connect tracking answers with the binary.
- Implement and test applicable US state sale/sharing opt-out, partner restrictions and privacy signals; make the in-app privacy entry point and the website's privacy request method functional. Determine whether sensitive-data limiting rights apply. Do not treat the static choices page as a working SDK switch.
- Configure child/age treatment across all SDKs despite the games not being directed to children. Test the final binary, App Store privacy details, and Google Play Data safety answers after every SDK or configuration change.

## Publishing plan

1. **Completed October 8, 2026:** In Alibaba Cloud **Public DNS** for `roycegames.online`, a TXT record was added with host `_github-pages-challenge-RoyceGames` (Alibaba Cloud displays it in lowercase) and value `33beff925c372a49db6ccf15fb4d56`. Leave the TXT record in place.
2. **Completed October 8, 2026:** GitHub `RoyceGames` account Settings → Pages displayed `Successfully verified roycegames.online` and listed the domain as `Verified`. Domain verification does not publish the website.
3. **Staged October 8, 2026:** The draft files were uploaded to the private `RoyceGames/roycegames.github.io` repository, branch `main`, repository root (initial commit `5cbff37`). Repository Settings → Pages currently says **Upgrade or make this repository public to enable Pages**. Before publishing, replace the placeholder contacts, complete the privacy audit and implementation checks, and update the files in the same repository. Confirm that the signed-in account menu says `RoyceGames` immediately before further uploads or visibility changes. After the content is ready, make the repository public for free GitHub Pages, publish from `main` / `(root)`, and set the custom domain to `roycegames.online` before adding site-routing DNS records. The included `CNAME` file contains the same domain.
4. Add the site-routing DNS records below, wait for propagation, then enable **Enforce HTTPS** in GitHub Pages. Check the site, support page, privacy policy, and privacy choices page over HTTPS.

At the domain registrar, add four apex `A` records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. If `www.roycegames.online` should work, add a `CNAME` record for `www` pointing to `RoyceGames.github.io`. Avoid conflicting apex `A`/`AAAA`/`ALIAS` records. These values follow GitHub's current Pages documentation and should be rechecked in its settings when configuring DNS. Verify all three HTTPS pages on desktop and mobile after propagation.

Intended App Store Connect URLs **after publication and verification**:

- Marketing: `https://roycegames.online/` (as a publisher site, if accepted for the listing)
- Support: `https://roycegames.online/support.html`
- Privacy Policy: `https://roycegames.online/privacy-policy.html`
- Your Privacy Choices: `https://roycegames.online/privacy-choices.html`

## Official references reviewed October 8, 2026

- [EU General Data Protection Regulation](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32016R0679)
- [California Privacy Protection Agency: consumer rights and request methods](https://cppa.ca.gov/faq)
- [California CCPA regulations effective January 1, 2026](https://cppa.ca.gov/regulations/pdf/ccpa_statute_eff_20260101.pdf)
- [Apple: user privacy and App Tracking Transparency](https://developer.apple.com/app-store/user-privacy-and-data-use/)
- [Unity LevelPlay: GDPR and consent before SDK initialization](https://docs.unity.com/en-us/grow/is-ads/legal-resources/ironsource-gdpr-compliance)

The policy page links to each planned ad provider's official notice or legal hub. These sources inform the draft; they do not establish that the actual games or consent flows comply with any law.
