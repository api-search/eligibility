---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Country refers to: United States'
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
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
name: Athena Security
provenance_date: '2026-11-09'
provider_name: Athena Security
provider_slug: athena-security
slug: athena-security-eligibility
source_date: '2026-11-09'
source_filename: athena-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.athena-security.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Athena Security\naid: athena-security\nurl: https://www.athena-security.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Country refers to: United States'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/athena-security/eligibility/athena-security-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Athena Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Weapons Detection
- Safety
---
