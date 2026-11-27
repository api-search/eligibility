---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - AU
    - NZ
    text: 'Supported destinations: US, Canada, Australia, New Zealand and 39 more countries (see sendfaxfast.com).'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI transmission
    text: is not designed, certified, or intended for the transmission of Protected Health Information (PHI) as defined under HIPAA or any comparable health-data regulations.
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
name: sendfaxfast-com
provenance_date: '2026-11-10'
provider_name: sendfaxfast-com
provider_slug: sendfaxfast-com
slug: sendfaxfast-com-eligibility
source_date: '2026-11-10'
source_filename: sendfaxfast-com-eligibility.yml
source_heading: Eligibility
source_page: https://sendfaxfast.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sendfaxfast-com\naid: sendfaxfast-com\nurl: https://sendfaxfast.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - AU\n  - NZ\n  excluded: []\n  text: 'Supported destinations: US, Canada, Australia, New Zealand and 39 more countries (see sendfaxfast.com).'\nentity_types: []\nrestricted_uses:\n- summary: No PHI transmission\n  text: is not designed, certified, or intended for the transmission of Protected Health Information (PHI) as defined\n    under HIPAA or any comparable health-data regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sendfaxfast-com/eligibility/sendfaxfast-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from sendfaxfast-com's own page on 2026-11-10.
synthetic: false
tags:
- Fax
- Payments
- Healthcare
- Government
- Germany
---
