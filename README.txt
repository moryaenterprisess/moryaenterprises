MORYA ENTERPRISE - STATIC WEBSITE
=================================

A simple, fast, single-page website for Morya Enterprise (RO water purifiers, since 2015, open 24/7).
No build step and no dependencies. It works on any static host (GitHub Pages, Netlify, cPanel, etc.).

FILES
-----
index.html     Main page: header, hero, about, products, services, contact, footer
privacy.html   Privacy Policy (template)
terms.html     Terms & Conditions (template)
styles.css     All styling (colours are CSS variables at the top of the file)
assets/
  logo.svg                    Your Morya Enterprise logo (header and footer). It wraps the same
                              image as logo.jpg, so it is not a true vector file.
  logo.jpg                    Same logo as a plain image
  favicon.png                 Browser tab icon (the crown from the logo)
  shop-display.jpg            Shop photo with home RO purifiers (hero + Home RO card)
  commercial-ro-plant-1.jpg   Commercial RO plant photo
  commercial-ro-plant-2.jpg   Compact commercial RO plant photo
  commercial-ro-plant-3.jpg   High-capacity commercial RO plant photo

THINGS TO UPDATE
----------------
1. Shop address: search for "[Add your shop address" in index.html, privacy.html and terms.html.
2. Dates: replace "[add date]" in privacy.html and terms.html.
3. Email: none is shown. Add one in the contact section if you want.
4. Products: edit the four cards in the Products section. Add prices or capacities if you want them shown.
5. Services: the six service cards are general. Edit them to match what you actually offer.
6. Warranty/returns and payment wording in terms.html: fill in your own policy.
7. Privacy and terms are templates. Have them reviewed before relying on them.

HOW IT WORKS
------------
- Sticky header with a Call button; anchor links scroll smoothly to each section.
- On mobile (under 860px) the menu collapses behind a Menu button and a floating "Call now" button appears.
- Every "Enquire" button and the WhatsApp buttons open WhatsApp chat with 9730644087 and a ready message.
  The number is written as 919730644087 (India country code 91). Change it in index.html if needed.
- The footer year updates automatically.

PUBLISHING ON GITHUB PAGES
--------------------------
1. Create a repository and upload all files, keeping the assets folder.
2. In Settings > Pages, choose the main branch and the root folder.
3. Your site will be live at https://USERNAME.github.io/REPOSITORY/
