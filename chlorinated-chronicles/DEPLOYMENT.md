# Deployment plan

## Current state
The canonical publication remains https://swimed.substack.com/.
The knowledge layer currently lives in the DataDrivenMed/swimtech repository under /chlorinated-chronicles/.

## Recommended public topology
- Publication: https://swimed.substack.com/
- Knowledge/evidence layer: a dedicated domain or subdomain controlled by the author
- GitHub: source and transparent version history

## Domain migration rule
When a dedicated domain is selected, update canonical URLs, sitemap URLs, JSON-LD identifiers and llms.txt together. Keep redirects from any previous public knowledge-layer URLs.

## Do not do
Do not set the knowledge-layer landing page as canonical to the Substack home if the knowledge page is intended to be independently indexed. Give it its own canonical URL after a stable public domain exists.
