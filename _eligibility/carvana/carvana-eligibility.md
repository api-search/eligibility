---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is based in the United States. It is not designed, customized, intended for, or directed to, any other country.
  minimum_age:
    text: The Service is not intended for users under the age of 16
    value: '16'
  restricted_uses:
  - summary: Users under 16
    text: The Service is not intended for users under the age of 16, and we do not knowingly collect personally identifiable information from users under the age of 16.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    source: https://api-developer.carvana.com/
    text: This API requires authorization by Carvana LLC.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carvana
provenance_date: '2026-11-09'
provider_name: Carvana
provider_slug: carvana
slug: carvana-eligibility
source_date: '2026-11-09'
source_filename: carvana-eligibility.yml
source_heading: Eligibility
source_page: https://www.carvana.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carvana\naid: carvana\nurl: https://www.carvana.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://api-developer.carvana.com/\n  - https://www.carvana.com/terms-of-use\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is based in the United States. It is not designed, customized, intended for, or directed to,\n    any other country.\nentity_types: []\nrestricted_uses:\n- summary: Users under 16\n  text: The Service is not intended for users under the age of 16, and we do not knowingly collect personally identifiable\n    information from users under the age\
  \ of 16.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: This API requires authorization by Carvana LLC.\n  source: https://api-developer.carvana.com/\nminimum_age:\n  value: '16'\n  text: The Service is not intended for users under the age of 16\n"
source_yaml_url: https://artifacts.apis.io/carvana/eligibility/carvana-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Carvana's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- E-Commerce
- Used Cars
- Inventory
- Partner API
- Fortune 500
---
