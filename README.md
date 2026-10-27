# Portfolio

**View the site: https://ilyesbenmaamar.github.io/portfolio/**

An interactive walkthrough of three linked pieces of work:

- **The data pipeline:** a multi-source market-data system. National customs statistics, licensed trade feeds and government energy statistics arrive through different routes, are landed raw in bronze, cleaned in silver, organised in gold, and handed on ready for forecasting.
- **Harbour View:** a visual workspace for steering AI agents across the pipeline. Agents work on a copy, every action passes a gate, and whatever needs a decision appears as a card on a ship. The site runs its real 3D harbour.
- **The AI Operating System:** the portable control layer I designed around the agents: context, risk, authority, evidence, handoff and learning. AI coding agents produced the implementation under my direction.

The pipeline uses twelve connectors across six acquisition methods (official APIs, scrapers, a browser handoff, a portal download, a drop zone and licensed feeds), with bronze, silver, gold and data-quality layers. Each connector is tested offline on small made-up fixtures. No real data, mappings or credentials appear on the site.

Code is available on request.

Examples use an invented company, Northwind Shipping Analytics. The site is a single page, `index.html`, served by GitHub Pages.
