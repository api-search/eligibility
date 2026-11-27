---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: offer enterprises a managed identity security AI Agent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI use by HIPAA covered entities
    text: Opti does not permit the use of the Opti Platform by any Customer that is a
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
name: Opti
provenance_date: '2026-11-10'
provider_name: Opti
provider_slug: opti
slug: opti-eligibility
source_date: '2026-11-10'
source_filename: opti-eligibility.yml
source_heading: Eligibility
source_page: https://www.opti.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opti\naid: opti\nurl: https://www.opti.ai/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: offer enterprises a managed identity security AI Agent\nrestricted_uses:\n- summary: No PHI use by HIPAA covered entities\n  text: Opti does not permit the use of the Opti Platform by any Customer that is a\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/opti/eligibility/opti-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Opti's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity and Access Management
- Identity Security
- Access Governance
- Non-Human Identity
- Agentic Identity
- Least Privilege
- Compliance
- Artificial Intelligence
---
