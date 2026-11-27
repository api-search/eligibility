---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited Services (e.g., cannabis, certain opioids, ketamine)
    text: Practices offering any Prohibited Service are excluded from using Cherry Services to finance any product or service.
  - summary: Excluded Services (e.g., gender transition, abortion, pet procedures)
    text: In addition, practices are prohibited from using Cherry to finance any of the following products and services
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
name: Cherry
provenance_date: '2026-11-09'
provider_name: Cherry
provider_slug: cherry
slug: cherry-eligibility
source_date: '2026-11-09'
source_filename: cherry-eligibility.yml
source_heading: Eligibility
source_page: https://withcherry.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cherry\naid: cherry\nurl: https://withcherry.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses:\n- summary: Prohibited Services (e.g., cannabis, certain opioids, ketamine)\n  text: Practices offering any Prohibited Service are excluded from using Cherry Services to finance any product\n    or service.\n- summary: Excluded Services (e.g., gender transition, abortion, pet procedures)\n  text: In addition, practices are prohibited from using Cherry to finance any of the following products and services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cherry/eligibility/cherry-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Cherry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Financing
- Point-of-Sale
- Patient Financing
- Buy Now Pay Later
- Healthcare
- Lending
---
