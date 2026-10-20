# Highlights Chicago services: URL hierarchy preview (v2)

Static preview of the /services pages with the corrected URL hierarchy, for review only.

- Live preview: https://logeshmaximus.github.io/services-urls-v2/
- Example: https://logeshmaximus.github.io/services-urls-v2/panel-upgrades/electrical-panel-upgrade/

What changed from the live site:

- Every service group's URL is its name: Panel Upgrades is /panel-upgrades (was /power-distribution), Circuit Protection /circuit-protection, Electrical Wiring /electrical-wiring, Electrical Outlets /electrical-outlets, Outdoor Lighting /outdoor-lighting, Solar Energy /solar-energy.
- Service pages sit under their group: /services/<group>/<service>.
- The old group URLs and old nested URLs forward to the new ones.

Every page is `noindex`, and canonical URLs point to https://www.highlightschicago.com, so this never competes with the real site in search. The quote forms do not submit here, because the lead API only runs on the real site.
