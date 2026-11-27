---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" means the company or person who completes the online registration form for use of the Services'
    type: individual
  - text: '"Customer" means the company or person who completes the online registration form for use of the Services'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk applications
    text: The Customer acknowledges that Services should not be used for high-risk applications where precise locations or features on maps are essential to the Customer
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company is entitled to refuse any order placed by a Customer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cookieyes
provenance_date: '2026-11-09'
provider_name: Cookieyes
provider_slug: cookieyes
slug: cookieyes-eligibility
source_date: '2026-11-09'
source_filename: cookieyes-eligibility.yml
source_heading: Eligibility
source_page: https://www.cookieyes.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cookieyes\naid: cookieyes\nurl: https://www.cookieyes.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"Customer\" means the company or person who completes the online registration form for use of the Services'\n- type: business\n  text: '\"Customer\" means the company or person who completes the online registration form for use of the Services'\nrestricted_uses:\n- summary: High-risk applications\n  text: The Customer acknowledges that Services should not be used for high-risk applications where precise\
  \ locations\n    or features on maps are essential to the Customer\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company is entitled to refuse any order placed by a Customer.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cookieyes/eligibility/cookieyes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Cookieyes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consent Management
- Privacy
- GDPR
- CCPA
- Cookie Consent
- Compliance
- Data Protection
- MCP
---
