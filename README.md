# Open-source product site

Static GitHub Pages site for focused open-source products.

## Information architecture

- The root is a product-first, multi-product hub.
- APIdapter has the stable canonical path at https://p1ac4.github.io/apidapter/.
- English and Simplified Chinese pages are paired with canonical and hreflang metadata.
- Future products should use independent top-level paths.

## Search and AI discovery

- robots.txt allows major search and answer crawlers.
- Known training crawlers are disallowed by policy.
- sitemap.xml lists canonical bilingual pages.
- llms.txt is an optional plain-text navigation aid. It is not treated as a search-ranking control.
- The root IndexNow key enables URL submission after deployment.

## Site boundary

The site uses plain HTML and CSS with no forms or external fonts. Google Analytics 4 measures product discovery and navigation with Measurement ID `G-8JHM6JYCK9`; the bilingual privacy pages describe the resulting cookies and data flow.
