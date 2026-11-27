---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the customer executing or otherwise accepting the Order Form which refer to these Terms
    type: business
  minimum_age:
    text: 'The Platform may only be used by individuals who: (i) can form legally binding contracts under applicable law'
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: Customer is not located or uses, exports, re-exports or imports the Platform (or any portion thereof) in or to, any person, entity, organization, jurisdiction or otherwise, in violation of the Export Controls
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
name: Tonkean
provenance_date: '2026-11-10'
provider_name: Tonkean
provider_slug: tonkean
slug: tonkean-eligibility
source_date: '2026-11-10'
source_filename: tonkean-eligibility.yml
source_heading: Eligibility
source_page: https://www.tonkean.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tonkean\naid: tonkean\nurl: https://www.tonkean.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the customer executing or otherwise accepting the Order Form which refer to these Terms\nrestricted_uses:\n- summary: Export control restrictions\n  text: Customer is not located or uses, exports, re-exports or imports the Platform (or any portion thereof) in\n    or to, any person, entity, organization, jurisdiction or otherwise, in violation of the Export Controls\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: 'The Platform may only be used by individuals who: (i) can form legally binding contracts under applicable\n    law'\n"
source_yaml_url: https://artifacts.apis.io/tonkean/eligibility/tonkean-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tonkean's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Process Orchestration
- Workflow Automation
- No-Code
- Enterprise
- Procurement
- Legal
- Intake
---
