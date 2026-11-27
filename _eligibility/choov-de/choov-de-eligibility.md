---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unternehmen, die ihre Produkte oder Tarife über die Choov-Plattform vermarkten möchten
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Choov prüft jeden Antrag manuell und bestätigt die Aufnahme per E-Mail.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Choov
provenance_date: '2026-11-09'
provider_name: Choov
provider_slug: choov-de
slug: choov-de-eligibility
source_date: '2026-11-09'
source_filename: choov-de-eligibility.yml
source_heading: Eligibility
source_page: https://www.choov.de/agb.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Choov\naid: choov-de\nurl: https://www.choov.de/agb.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Unternehmen, die ihre Produkte oder Tarife über die Choov-Plattform vermarkten möchten\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Choov prüft jeden Antrag manuell und bestätigt die Aufnahme per E-Mail.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/choov-de/eligibility/choov-de-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Choov's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Electricity
- Tariff Comparison
- MCP
- AI Agents
- Marketplace
- Germany
---
