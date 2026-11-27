---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Seules les commandes payées, facturées et livrées en France métropolitaine (Corse incluse) sont acceptées sur le Site.
  entity_types:
  - text: réalisées auprès des acheteurs particuliers (le(s) « Client(s) »)
    type: individual
  - text: Conditions générales de vente - Professionnels - Janvier 2022
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: La création d’un compte par le Client est obligatoire avant toute passation de commande
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 123elec
provenance_date: '2026-11-09'
provider_name: 123elec
provider_slug: 123elec-com
slug: 123elec-com-eligibility
source_date: '2026-11-09'
source_filename: 123elec-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.123elec.com/cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 123elec\naid: 123elec-com\nurl: https://www.123elec.com/cgv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Seules les commandes payées, facturées et livrées en France métropolitaine (Corse incluse) sont acceptées\n    sur le Site.\nentity_types:\n- type: individual\n  text: réalisées auprès des acheteurs particuliers (le(s) « Client(s) »)\n- type: business\n  text: Conditions générales de vente - Professionnels - Janvier 2022\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: La création d’un compte par le Client\
  \ est obligatoire avant toute passation de commande\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/123elec-com/eligibility/123elec-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 4 quoted statements, read from 123elec's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Electrical
- Hardware
- Retail
- France
---
