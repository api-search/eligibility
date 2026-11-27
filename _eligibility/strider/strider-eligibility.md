---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: are not located in, under the control of, or a national or resident of any country to which the United States has embargoed goods or services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Member is solely responsible for identifying and authenticating all Users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Strider
provenance_date: '2026-11-10'
provider_name: Strider
provider_slug: strider
slug: strider-eligibility
source_date: '2026-11-10'
source_filename: strider-eligibility.yml
source_heading: Eligibility
source_page: http://striderintel.com/company/strider-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strider\naid: strider\nurl: http://striderintel.com/company/strider-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: are not located in, under the control of, or a national or resident of any country to which the United States\n    has embargoed goods or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Member is solely responsible for identifying and authenticating all Users\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/strider/eligibility/strider-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Strider's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Strategic Intelligence
- Threat Intelligence
- Risk Management
- Security
- Supply Chain
- Due Diligence
- Open Source Intelligence
- Artificial Intelligence
- Geopolitical Risk
---
