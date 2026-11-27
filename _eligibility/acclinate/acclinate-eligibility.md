---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms permit you to use the Website for your personal use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Website only for lawful purposes and in accordance with these Terms.
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
name: Acclinate
provenance_date: '2026-11-09'
provider_name: Acclinate
provider_slug: acclinate
slug: acclinate-eligibility
source_date: '2026-11-09'
source_filename: acclinate-eligibility.yml
source_heading: Eligibility
source_page: https://www.acclinate.com/terms-of-use-acclinate
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acclinate\naid: acclinate\nurl: https://www.acclinate.com/terms-of-use-acclinate\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms permit you to use the Website for your personal use only.\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acclinate/eligibility/acclinate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Acclinate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Clinical Trials
- Health Equity
- Patient Recruitment
- Artificial Intelligence
- Machine Learning
- Healthcare
- Diversity
---
