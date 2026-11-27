---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Lieferungen erfolgen innerhalb des deutschen Bundesgebietes, innerhalb der EU (Intrahandel) sowie außerhalb der EU (Extrahandel).
  entity_types:
  - text: Sie haben das Recht, binnen vierzehn Tagen ohne Angabe von Gründen diesen Vertrag zu widerrufen.
    type: individual
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
name: Pollin Electronic
provenance_date: '2026-11-10'
provider_name: Pollin Electronic
provider_slug: pollin
slug: pollin-eligibility
source_date: '2026-11-10'
source_filename: pollin-eligibility.yml
source_heading: Eligibility
source_page: https://www.pollin.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pollin Electronic\naid: pollin\nurl: https://www.pollin.de/agb\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Lieferungen erfolgen innerhalb des deutschen Bundesgebietes, innerhalb der EU (Intrahandel) sowie außerhalb\n    der EU (Extrahandel).\nentity_types:\n- type: individual\n  text: Sie haben das Recht, binnen vierzehn Tagen ohne Angabe von Gründen diesen Vertrag zu widerrufen.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pollin/eligibility/pollin-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Pollin Electronic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Electronics
- Retail
- E-Commerce
- Germany
---
