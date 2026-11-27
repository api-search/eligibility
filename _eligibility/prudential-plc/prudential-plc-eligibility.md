---
claim_count: 1
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
  - summary: Denial-of-service and unauthorised access
    text: You must not attempt to gain unauthorised access to the Website, the server on which the Website is stored or any server, computer or database connected to the Website
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
name: Prudential
provenance_date: '2026-11-10'
provider_name: Prudential
provider_slug: prudential-plc
slug: prudential-plc-eligibility
source_date: '2026-11-10'
source_filename: prudential-plc-eligibility.yml
source_heading: Eligibility
source_page: https://www.prudentialplc.com/en/site-services/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prudential\naid: prudential-plc\nurl: https://www.prudentialplc.com/en/site-services/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Denial-of-service and unauthorised access\n  text: You must not attempt to gain unauthorised access to the Website, the server on which the Website is stored\n    or any server, computer or database connected to the Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prudential-plc/eligibility/prudential-plc-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Prudential's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- United Kingdom
- Life Insurance
- Health Insurance
- Carrier
- Asset Management
- Pensions
- Takaful
- Bancassurance
- Asia
- Africa
- Hong Kong
- Singapore
- Malaysia
- Indonesia
- Vietnam
- Philippines
- Eastspring
- Responsible AI
- Llms.txt
---
