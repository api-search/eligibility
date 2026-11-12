---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Ouvert à toutes les entreprises françaises.
  entity_types:
  - text: forfaits sans engagement pour les indépendants, artisans et TPE établis en France
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Comontel
provenance_date: '2026-11-09'
provider_name: Comontel
provider_slug: comontel-fr
slug: comontel-fr-eligibility
source_date: '2026-11-09'
source_filename: comontel-fr-eligibility.yml
source_heading: Eligibility
source_page: https://comontel.fr/conditions-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comontel\naid: comontel-fr\nurl: https://comontel.fr/conditions-generales\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Ouvert à toutes les entreprises françaises.\nentity_types:\n- type: business\n  text: forfaits sans engagement pour les indépendants, artisans et TPE établis en France\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/comontel-fr/eligibility/comontel-fr-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Comontel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telecommunications
- Mobile
- MVNO
- Cross-Border
- France
- Switzerland
- Small Business
- MCP
---
