---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Les prestations de JAIKIN sont réservées aux professionnels agissant dans le cadre de leur activité commerciale, industrielle, artisanale, libérale ou agricole.
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
name: jaikin-eu
provenance_date: '2026-11-09'
provider_name: jaikin-eu
provider_slug: jaikin-eu
slug: jaikin-eu-eligibility
source_date: '2026-11-09'
source_filename: jaikin-eu-eligibility.yml
source_heading: Eligibility
source_page: https://www.jaikin.eu/conditions-generales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: jaikin-eu\naid: jaikin-eu\nurl: https://www.jaikin.eu/conditions-generales\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Les prestations de JAIKIN sont réservées aux professionnels agissant dans le cadre de leur activité commerciale,\n    industrielle, artisanale, libérale ou agricole.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jaikin-eu/eligibility/jaikin-eu-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from jaikin-eu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Odoo
- Custom Software
- Consulting
- France
---
