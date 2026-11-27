---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are creating a workspace on behalf of an organisation, you represent that you have the authority to bind that organisation to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical and regulated decisions
    text: The Service is not intended for use in safety-critical, medical, legal, or regulated decision-making contexts where errors could cause harm
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
name: Ambix
provenance_date: '2026-11-09'
provider_name: Ambix
provider_slug: ambix-ai
slug: ambix-ai-eligibility
source_date: '2026-11-09'
source_filename: ambix-ai-eligibility.yml
source_heading: Eligibility
source_page: https://ambix.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambix\naid: ambix-ai\nurl: https://ambix.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are creating a workspace on behalf of an organisation, you represent that you have the authority\n    to bind that organisation to these Terms\nrestricted_uses:\n- summary: Safety-critical and regulated decisions\n  text: The Service is not intended for use in safety-critical, medical, legal, or regulated decision-making contexts\n    where errors could cause harm\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ambix-ai/eligibility/ambix-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ambix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Collaboration
- Product Management
- Data
---
