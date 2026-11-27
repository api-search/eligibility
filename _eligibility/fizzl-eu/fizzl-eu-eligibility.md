---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer in the EU, you keep the protection of the mandatory law of the country where you live.
  entity_types:
  - text: consumers in the EU can withdraw within 14 days of purchase
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud, money laundering, sanctions evasion
    text: Don't use the services for anything illegal, such as fraud, money laundering or evading sanctions
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
name: fizzl-eu
provenance_date: '2026-11-09'
provider_name: fizzl-eu
provider_slug: fizzl-eu
slug: fizzl-eu-eligibility
source_date: '2026-11-09'
source_filename: fizzl-eu-eligibility.yml
source_heading: Eligibility
source_page: https://fizzl.eu/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fizzl-eu\naid: fizzl-eu\nurl: https://fizzl.eu/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer in the EU, you keep the protection of the mandatory law of the country where you live.\nentity_types:\n- type: individual\n  text: consumers in the EU can withdraw within 14 days of purchase\nrestricted_uses:\n- summary: Fraud, money laundering, sanctions evasion\n  text: Don't use the services for anything illegal, such as fraud, money laundering or evading sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fizzl-eu/eligibility/fizzl-eu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from fizzl-eu's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Payments
- Automation
- Tools
- Platform
---
