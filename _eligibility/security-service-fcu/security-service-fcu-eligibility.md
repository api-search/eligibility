---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual and use your account for personal, family or household purposes, important limitations on your liability for unauthorized electronic funds transfers
    type: individual
  - text: if you use the Services for any business activity, you assume all risk of loss for unauthorized transfers and payments
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or illegal purposes
    text: If you use our Website or our Products, Materials or Services for any unlawful or illegal purpose, you must promptly reimburse us for all losses, costs and expenses incurred by us as a result of such use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access Online Banking, you must follow our enrollment procedures, including our procedures for verification, authentication and security.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Security Service Federal Credit Union
provenance_date: '2026-11-10'
provider_name: Security Service Federal Credit Union
provider_slug: security-service-fcu
slug: security-service-fcu-eligibility
source_date: '2026-11-10'
source_filename: security-service-fcu-eligibility.yml
source_heading: Eligibility
source_page: https://ssfcu.org/enrollment/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Security Service Federal Credit Union\naid: security-service-fcu\nurl: https://ssfcu.org/enrollment/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual and use your account for personal, family or household purposes, important limitations\n    on your liability for unauthorized electronic funds transfers\n- type: business\n  text: if you use the Services for any business activity, you assume all risk of loss for unauthorized transfers\n    and payments\nrestricted_uses:\n- summary: Unlawful or\
  \ illegal purposes\n  text: If you use our Website or our Products, Materials or Services for any unlawful or illegal purpose, you must\n    promptly reimburse us for all losses, costs and expenses incurred by us as a result of such use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access Online Banking, you must follow our enrollment procedures, including our procedures for verification,\n    authentication and security.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/security-service-fcu/eligibility/security-service-fcu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Security Service Federal Credit Union's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Credit Union
- Open Finance
---
