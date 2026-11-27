---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Service is limited exclusively to users located in jurisdictions within the United States where the Service is available.
  entity_types:
  - text: 'Generally, the Service is available only to individuals who: are at least 18 years old, emancipated minors, minors who are legally able to independently consent to, or contract to, receiving the Service'
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years old, an emancipated minor, a minor who is legally able to independently consent or contract to receiving the Service
    value: '18'
  restricted_uses:
  - summary: No resale by dealers or wholesalers
    text: We do not accept orders from dealers, wholesalers or other customers who intend to resell items offered on our Site.
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
name: Nomi Health
provenance_date: '2026-11-10'
provider_name: Nomi Health
provider_slug: nomi-health
slug: nomi-health-eligibility
source_date: '2026-11-10'
source_filename: nomi-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.nomihealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nomi Health\naid: nomi-health\nurl: https://www.nomihealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Service is limited exclusively to users located in jurisdictions within the United\n    States where the Service is available.\nentity_types:\n- type: individual\n  text: 'Generally, the Service is available only to individuals who: are at least 18 years old, emancipated minors,\n    minors who are legally able to independently consent to, or contract to, receiving the Service'\nrestricted_uses:\n- summary:\
  \ No resale by dealers or wholesalers\n  text: We do not accept orders from dealers, wholesalers or other customers who intend to resell items offered\n    on our Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old, an emancipated minor, a minor who is legally able to independently\n    consent or contract to receiving the Service\n"
source_yaml_url: https://artifacts.apis.io/nomi-health/eligibility/nomi-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nomi Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Payments
- Financial Services
- Insurance
- Benefits
- Analytics
- Claims
---
