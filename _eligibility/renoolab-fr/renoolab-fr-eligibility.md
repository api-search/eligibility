---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Des particuliers recherchant un artisan du bâtiment pour un projet
    type: individual
  - text: Des artisans du bâtiment souhaitant gagner en visibilité et trouver de nouveaux clients
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive content
    text: Ne pas publier de contenu diffamatoire, injurieux, haineux, discriminatoire, violent, pornographique ou illégal
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Seuls les profils arborant le badge vérifié ( ) ont fait l'objet d'une vérification par RenooLab, portant sur la validité du numéro SIREN et la détention d'une assurance professionnelle en cours de validité.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RenooLab
provenance_date: '2026-11-10'
provider_name: RenooLab
provider_slug: renoolab-fr
slug: renoolab-fr-eligibility
source_date: '2026-11-10'
source_filename: renoolab-fr-eligibility.yml
source_heading: Eligibility
source_page: https://renoolab.fr/cgu/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RenooLab\naid: renoolab-fr\nurl: https://renoolab.fr/cgu/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Des particuliers recherchant un artisan du bâtiment pour un projet\n- type: business\n  text: Des artisans du bâtiment souhaitant gagner en visibilité et trouver de nouveaux clients\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: Ne pas publier de contenu diffamatoire, injurieux, haineux, discriminatoire, violent, pornographique ou\n    illégal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Seuls les profils arborant le badge vérifié ( ) ont fait l'objet d'une vérification par RenooLab, portant\n    sur la validité du numéro SIREN et la détention d'une assurance professionnelle en cours de validité.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/renoolab-fr/eligibility/renoolab-fr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from RenooLab's own page on 2026-11-10.
synthetic: false
tags:
- Home Services
- Construction
- Building Trades
- Renovation
- Marketplace
- Local Services
- MCP
- A2A
- AI Agents
- Agent Skills
- France
---
