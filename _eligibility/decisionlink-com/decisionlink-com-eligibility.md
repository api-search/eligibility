---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the authority to enter into these Terms personally or on behalf of the entity you represent
    type: business
  minimum_age:
    text: You affirm that you are more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    value: '18'
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
name: DecisionLink
provenance_date: '2026-11-09'
provider_name: DecisionLink
provider_slug: decisionlink-com
slug: decisionlink-com-eligibility
source_date: '2026-11-09'
source_filename: decisionlink-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.xfactor.io/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DecisionLink\naid: decisionlink-com\nurl: https://www.xfactor.io/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you have the authority to enter into these Terms personally or on behalf of the entity you represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are more than 18 years of age, or an emancipated minor, or possess legal parental or\n    guardian consent\n"
source_yaml_url: https://artifacts.apis.io/decisionlink-com/eligibility/decisionlink-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from DecisionLink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Decision Intelligence
- Revenue
- Simulation
- Platform
---
