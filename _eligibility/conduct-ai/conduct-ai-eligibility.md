---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not permit Users to access or use the Services in a US-embargoed country or in violation of any applicable export law or regulation
  entity_types:
  - text: access to, and use of the software-as-a-service platform and related services provided by Conduct AI under a commercial agreement between the parties
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use or third-party rights violation
    text: (e) use the Services for any illegal purpose or in violation of third-party rights.
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
name: Conduct AI
provenance_date: '2026-11-09'
provider_name: Conduct AI
provider_slug: conduct-ai
slug: conduct-ai-eligibility
source_date: '2026-11-09'
source_filename: conduct-ai-eligibility.yml
source_heading: Eligibility
source_page: https://conduct.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conduct AI\naid: conduct-ai\nurl: https://conduct.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not permit Users to access or use the Services in a US-embargoed country or in violation\n    of any applicable export law or regulation\nentity_types:\n- type: business\n  text: access to, and use of the software-as-a-service platform and related services provided by Conduct AI under\n    a commercial agreement between the parties\nrestricted_uses:\n- summary: Illegal use or third-party rights violation\n  text: (e) use the Services for any illegal purpose\
  \ or in violation of third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conduct-ai/eligibility/conduct-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Conduct AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise Software
- SAP
- S/4HANA
- Legacy Modernization
- Code Analysis
- IT Operations
---
