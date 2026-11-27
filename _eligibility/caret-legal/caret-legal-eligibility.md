---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AN INDIVIDUAL ACCEPTING THESE TERMS ON BEHALF OF AN ENTITY REPRESENTS THAT HE OR SHE IS AT LEAST 18 YEARS OF AGE AND HAS THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS
    type: business
  minimum_age:
    text: AN INDIVIDUAL ACCEPTING THESE TERMS ON BEHALF OF AN ENTITY REPRESENTS THAT HE OR SHE IS AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Illegal or unlawful use
    text: use the Subscription Service or a Beta Service for any illegal purpose or to generate unlawful, harmful, deceptive, infringing, or discriminatory content
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
name: CARET Legal
provenance_date: '2026-11-09'
provider_name: CARET Legal
provider_slug: caret-legal
slug: caret-legal-eligibility
source_date: '2026-11-09'
source_filename: caret-legal-eligibility.yml
source_heading: Eligibility
source_page: https://caretlegal.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CARET Legal\naid: caret-legal\nurl: https://caretlegal.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: AN INDIVIDUAL ACCEPTING THESE TERMS ON BEHALF OF AN ENTITY REPRESENTS THAT HE OR SHE IS AT LEAST 18 YEARS\n    OF AGE AND HAS THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: use the Subscription Service or a Beta Service for any illegal purpose or to generate unlawful, harmful,\n    deceptive, infringing, or discriminatory content\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AN INDIVIDUAL ACCEPTING THESE TERMS ON BEHALF OF AN ENTITY REPRESENTS THAT HE OR SHE IS AT LEAST 18 YEARS\n    OF AGE\n"
source_yaml_url: https://artifacts.apis.io/caret-legal/eligibility/caret-legal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CARET Legal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Software-as-a-Service
- Cloud
- Practice Management
---
