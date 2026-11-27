---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are a person barred from using or receiving the Software Service under the applicable laws of the United States or other countries
  entity_types:
  - text: If you are using or accessing the Software Service on behalf of an entity, you represent and warrant that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Desmos Studio
    value: null
  restricted_uses:
  - summary: Offensive or malicious Applications
    text: is not pornographic, hate-related, violent abusive, or otherwise offensive in content
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
name: Desmos
provenance_date: '2026-11-09'
provider_name: Desmos
provider_slug: desmos
slug: desmos-eligibility
source_date: '2026-11-09'
source_filename: desmos-eligibility.yml
source_heading: Eligibility
source_page: https://www.desmos.com/api-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Desmos\naid: desmos\nurl: https://www.desmos.com/api-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are a person barred from using or receiving the Software Service under the applicable laws of the United\n    States or other countries\nentity_types:\n- type: business\n  text: If you are using or accessing the Software Service on behalf of an entity, you represent and warrant that\n    you have authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Offensive or malicious Applications\n  text: is not pornographic, hate-related, violent abusive, or otherwise\
  \ offensive in content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Desmos Studio\n"
source_yaml_url: https://artifacts.apis.io/desmos/eligibility/desmos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Desmos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- Mathematics
- Graphing Calculator
- Embeddable
- JavaScript
- EdTech
- Data Visualization
---
