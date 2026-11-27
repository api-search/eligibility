---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not permit any access or use this Website or its Content in or from a U.S. embargoed country or in violation of any export or import law in any jurisdiction.
  entity_types:
  - text: the Website is intended for use by natural persons
    type: individual
  minimum_age:
    text: 'You represent that You are: (a) at least eighteen (18) years of age'
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use
    text: 'Strictly prohibited uses of the Website also include, but is not limited to: (a) using the Website for illegal purpose'
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
name: Deep Instinct
provenance_date: '2026-11-09'
provider_name: Deep Instinct
provider_slug: deep-instinct
slug: deep-instinct-eligibility
source_date: '2026-11-09'
source_filename: deep-instinct-eligibility.yml
source_heading: Eligibility
source_page: https://www.deepinstinct.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deep Instinct\naid: deep-instinct\nurl: https://www.deepinstinct.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will not permit any access or use this Website or its Content in or from a U.S. embargoed country or\n    in violation of any export or import law in any jurisdiction.\nentity_types:\n- type: individual\n  text: the Website is intended for use by natural persons\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: 'Strictly prohibited uses of the Website also include, but is not limited to: (a) using the Website for\n    illegal purpose'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'You represent that You are: (a) at least eighteen (18) years of age'\n"
source_yaml_url: https://artifacts.apis.io/deep-instinct/eligibility/deep-instinct-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Deep Instinct's own page on 2026-11-09.
synthetic: false
tags:
- Cybersecurity
- Endpoint Security
- malware-prevention
- Ransomware
- Deep Learning
- Threat Prevention
- Data Security
- Endpoint Detection and Response
- SOC Automation
- MCP
---
