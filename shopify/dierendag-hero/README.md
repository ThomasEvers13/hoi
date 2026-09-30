# Dierendag-hero Robustrise (2026)

Hero-banner voor de homepage van robustrise.nl tijdens de Dierendag-actie
(gratis Pet Head shampoo bij waterblazer, tondeuse, blafband of kattenfontein, t/m 6 oktober 2026).

- `sections/hero-dierendag.liquid`: de sectie. Alle teksten, beelden en de einddatum zijn aan te passen in de thema-editor.
- `templates/index.json`: homepage-indeling met de Dierendag-hero bovenaan.
- `snippets/rr-dierendag-badge.liquid`, `rr-dierendag-strip.liquid`, `rr-dierendag-pdp.liquid`: labeltje op productkaartjes, balk op collecties en kaartje op productpagina's (ook op de gratis vachtgids).
- `snippets/rr-gids-blog.liquid` + `sections/main-article.liquid`: regel boven en kaart onder hondenblog-artikelen over vachtverzorging (tag `cat-hondenrassen` plus een lijst handles in de snippet), met de gratis vachtgids. Alleen in blog `news`, verdwijnt na 6 oktober.
- `snippets/rr-gids-upsell.liquid` + `snippets/cart-drawer.liquid`: de gratis vachtgids (€ 0) als eerste kaart in de upsellcarrousel van de winkelwagen.

Na de einddatum verdwijnen de banner en alle actie-elementen vanzelf en komt de gewone hero (`hero_dog_supplies_9KeYfg`) weer terug.
