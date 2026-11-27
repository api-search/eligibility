---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  entity_types:
  - text: The Gravie Services are only available to United States residents in the states where the Gravie Service is available.
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: No commercial use of Platform
    text: You must not access or use any part of the Platform or any services or materials available through the Platform for outsourcing for others or as part of a service bureau business
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Gravie may contact you by telephone, mail, or e-mail to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gravie
provenance_date: '2026-11-09'
provider_name: Gravie
provider_slug: gravie
slug: gravie-eligibility
source_date: '2026-11-09'
source_filename: gravie-eligibility.yml
source_heading: Eligibility
source_page: https://www.gravie.com/compliance/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gravie\naid: gravie\nurl: https://www.gravie.com/compliance/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: The Gravie Services are only available to United States residents in the states where the Gravie Service\n    is available.\nrestricted_uses:\n- summary: No commercial use of Platform\n  text: You must not access or use any part of the Platform or any services or materials available through the Platform\n    for outsourcing for others or as part\
  \ of a service bureau business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Gravie may contact you by telephone, mail, or e-mail to verify your information.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/gravie/eligibility/gravie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gravie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Insurance
- Health Benefits
- Employee Benefits
- Third-Party Administrator
- ICHRA
- Level Funded
- Transparency In Coverage
- Machine-Readable Files
- Healthcare
- Insurance
- Regulatory
---
