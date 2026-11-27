---
api_specs:
- filename: cyrisma-openapi-generated.yml
  format: yaml
  label: CYRISMA API
  slug: cyrisma-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyrisma/openapi/_ae-authored/cyrisma-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Cyrisma Services.
  entity_types:
  - text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Cyrisma Services.
    type: individual
  - text: if you have accepted these Terms on behalf of any person or entity, you represent that you have legal authority to do so
    type: business
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Cyrisma Services.
    value: '18'
  restricted_uses:
  - summary: Stalking, threats, privacy violations
    text: use the Cyrisma Services to stalk, threaten, or otherwise violate the rights of others, including without limitation others’ privacy rights or rights of publicity
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
name: CYRISMA
provenance_date: '2026-11-09'
provider_name: CYRISMA
provider_slug: cyrisma
slug: cyrisma-eligibility
source_date: '2026-11-09'
source_filename: cyrisma-eligibility.yml
source_heading: Eligibility
source_page: https://www.cyrisma.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CYRISMA\naid: cyrisma\nurl: https://www.cyrisma.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Cyrisma Services.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Cyrisma Services.\n- type: business\n  text: if you have accepted these Terms on behalf of any person or entity, you represent that you have legal authority\n    to do so\nrestricted_uses:\n\
  - summary: Stalking, threats, privacy violations\n  text: use the Cyrisma Services to stalk, threaten, or otherwise violate the rights of others, including without\n    limitation others’ privacy rights or rights of publicity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Cyrisma Services.\n"
source_yaml_url: https://artifacts.apis.io/cyrisma/eligibility/cyrisma-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CYRISMA's own page on 2026-11-09.
synthetic: false
tags:
- Cybersecurity
- Software-as-a-Service
- Risk Management
- Compliance
- Vulnerability Management
- MSP
---
