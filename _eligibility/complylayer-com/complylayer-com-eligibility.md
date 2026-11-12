---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organisation, you represent that you have the authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Use the Service in violation of any applicable law or regulation
  - summary: Processing data without rights
    text: Use the Service to process data that you do not have the right to process
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
name: ComplyLayer
provenance_date: '2026-11-09'
provider_name: ComplyLayer
provider_slug: complylayer-com
slug: complylayer-com-eligibility
source_date: '2026-11-09'
source_filename: complylayer-com-eligibility.yml
source_heading: Eligibility
source_page: https://complylayer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ComplyLayer\naid: complylayer-com\nurl: https://complylayer.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organisation, you represent that you have the authority to\n    bind that organisation to these Terms.\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Service in violation of any applicable law or regulation\n- summary: Processing data without rights\n  text: Use the Service to process data that you do not have the right to process\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/complylayer-com/eligibility/complylayer-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ComplyLayer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Governance
- Compliance
- EU AI Act
- Risk Management
- GDPR
- MCP
- Privacy
---
