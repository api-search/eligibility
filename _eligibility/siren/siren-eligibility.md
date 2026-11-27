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
  - text: you represent and warrant that you are older than eighteen (18) years old.
    type: individual
  minimum_age:
    text: you represent and warrant that you are older than eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: No access from jurisdictions where illegal
    text: Accessing the Site or Services from jurisdictions where content is illegal, or where we do not offer Services, is prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Siren may contact you by push notification, telephone, mail, or email to verify your account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Siren
provenance_date: '2026-11-10'
provider_name: Siren
provider_slug: siren
slug: siren-eligibility
source_date: '2026-11-10'
source_filename: siren-eligibility.yml
source_heading: Eligibility
source_page: https://www.siren.care/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Siren\naid: siren\nurl: https://www.siren.care/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: you represent and warrant that you are older than eighteen (18) years old.\nrestricted_uses:\n- summary: No access from jurisdictions where illegal\n  text: Accessing the Site or Services from jurisdictions where content is illegal, or where we do not offer Services,\n    is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Siren may contact you by push notification, telephone, mail, or email to verify your account information.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are older than eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/siren/eligibility/siren-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Siren's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Remote Patient Monitoring
- Diabetes
- Wearables
- Medical Devices
- Health Tech
---
