---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CAN Capital makes no representations that the Site is appropriate or available for use in locations outside of the United States of America.
  entity_types:
  - text: You affirm that you are at least the age of 18.
    type: individual
  minimum_age:
    text: You affirm that you are at least the age of 18.
    value: '18'
  restricted_uses:
  - summary: No lending transactions outside the Site
    text: It is against the Terms to attempt to enter into any lending or other similar transactions outside of the Site.
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
name: Can Capital
provenance_date: '2026-11-09'
provider_name: Can Capital
provider_slug: can-capital
slug: can-capital-eligibility
source_date: '2026-11-09'
source_filename: can-capital-eligibility.yml
source_heading: Eligibility
source_page: https://www.cancapital.com/legal-pages/can-capitals-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Can Capital\naid: can-capital\nurl: https://www.cancapital.com/legal-pages/can-capitals-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: CAN Capital makes no representations that the Site is appropriate or available for use in locations outside\n    of the United States of America.\nentity_types:\n- type: individual\n  text: You affirm that you are at least the age of 18.\nrestricted_uses:\n- summary: No lending transactions outside the Site\n  text: It is against the Terms to attempt to enter into any lending or other similar transactions outside of the\n    Site.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are at least the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/can-capital/eligibility/can-capital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Can Capital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Financial Services
- Lending
- Small Business
- Working Capital
- Merchant Cash Advance
- Fintech
---
