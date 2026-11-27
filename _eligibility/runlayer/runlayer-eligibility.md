---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual accepting these Terms, or the company or other legal entity on whose behalf that individual is accepting these Terms
    type: individual
  - text: the company or other legal entity on whose behalf that individual is accepting these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Data submission
    text: You will not submit any Restricted Data (as defined in Section 6) to the Services unless necessary for Your evaluation of the Trial Services and as agreed to in writing by Runlayer.
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
name: Runlayer
provenance_date: '2026-11-10'
provider_name: Runlayer
provider_slug: runlayer
slug: runlayer-eligibility
source_date: '2026-11-10'
source_filename: runlayer-eligibility.yml
source_heading: Eligibility
source_page: https://www.runlayer.com/legal/trial-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runlayer\naid: runlayer\nurl: https://www.runlayer.com/legal/trial-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual accepting these Terms, or the company or other legal entity on whose behalf that individual\n    is accepting these Terms\n- type: business\n  text: the company or other legal entity on whose behalf that individual is accepting these Terms\nrestricted_uses:\n- summary: Restricted Data submission\n  text: You will not submit any Restricted Data (as defined in Section 6) to the Services unless necessary\
  \ for Your\n    evaluation of the Trial Services and as agreed to in writing by Runlayer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runlayer/eligibility/runlayer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Runlayer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- MCP
- API Gateway
- Security
- Governance
- Identity
- Observability
- Enterprise
---
