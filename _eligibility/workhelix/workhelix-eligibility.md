---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting on behalf of a company or other legal entity, you represent that you have the authority to bind such entity and its affiliates to these terms and conditions
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: Workhelix’s direct competitors are prohibited from accessing or using the Services, except with Workhelix’s prior written consent.
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
name: Workhelix
provenance_date: '2026-11-10'
provider_name: Workhelix
provider_slug: workhelix
slug: workhelix-eligibility
source_date: '2026-11-10'
source_filename: workhelix-eligibility.yml
source_heading: Eligibility
source_page: https://www.workhelix.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workhelix\naid: workhelix\nurl: https://www.workhelix.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting on behalf of a company or other legal entity, you represent that you have the authority\n    to bind such entity and its affiliates to these terms and conditions\nrestricted_uses:\n- summary: Direct competitors barred\n  text: Workhelix’s direct competitors are prohibited from accessing or using the Services, except with Workhelix’s\n    prior written consent.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workhelix/eligibility/workhelix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Workhelix's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workforce Analytics
- AI ROI
- Enterprise Software
- Productivity
- Task Analysis
---
