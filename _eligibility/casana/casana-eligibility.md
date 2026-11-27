---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website and Products are designed and intended for use within the United States only.
  entity_types:
  - text: If you accept or agree to these Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: The Website and Products are intended solely for individuals who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Non-personal orders
    text: if we have reason to believe that your order is not for personal use, we reserve the right to reject or cancel any order that you place.
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
name: Casana
provenance_date: '2026-11-09'
provider_name: Casana
provider_slug: casana
slug: casana-eligibility
source_date: '2026-11-09'
source_filename: casana-eligibility.yml
source_heading: Eligibility
source_page: https://casanacare.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Casana\naid: casana\nurl: https://casanacare.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website and Products are designed and intended for use within the United States only.\nentity_types:\n- type: business\n  text: If you accept or agree to these Terms on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority to bind that company or other legal entity to these Terms.\nrestricted_uses:\n- summary: Non-personal orders\n  text: if we have reason to believe that your order is not for personal use, we reserve the\
  \ right to reject or\n    cancel any order that you place.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website and Products are intended solely for individuals who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/casana/eligibility/casana-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Casana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Remote Patient Monitoring
- Vital Signs
- Cardiovascular
- Connected Medical Devices
- Consumer Health
---
