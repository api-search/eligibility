---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors excluded
    text: YOU MAY NOT ACCESS THE SUBSCRIPTION SERVICES IF YOU ARE OUR DIRECT COMPETITOR, EXCEPT WITH OUR PRIOR WRITTEN CONSENT.
  - summary: No monitoring or benchmarking
    text: YOU MAY NOT ACCESS THE SUBSCRIPTION SERVICES FOR PURPOSES OF MONITORING THEIR AVAILABILITY, PERFORMANCE OR FUNCTIONALITY, OR FOR ANY OTHER BENCHMARKING OR COMPETITIVE PURPOSES.
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
name: BoomerangAI
provenance_date: '2026-11-09'
provider_name: BoomerangAI
provider_slug: boomerangai
slug: boomerangai-eligibility
source_date: '2026-11-09'
source_filename: boomerangai-eligibility.yml
source_heading: Eligibility
source_page: https://www.getboomerang.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoomerangAI\naid: boomerangai\nurl: https://www.getboomerang.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Direct competitors excluded\n  text: YOU MAY NOT ACCESS THE SUBSCRIPTION SERVICES IF YOU ARE OUR DIRECT COMPETITOR, EXCEPT WITH OUR PRIOR WRITTEN\n    CONSENT.\n- summary: No monitoring or benchmarking\n  text: YOU MAY NOT ACCESS\
  \ THE SUBSCRIPTION SERVICES FOR PURPOSES OF MONITORING THEIR AVAILABILITY, PERFORMANCE\n    OR FUNCTIONALITY, OR FOR ANY OTHER BENCHMARKING OR COMPETITIVE PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boomerangai/eligibility/boomerangai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from BoomerangAI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sales
- B2B
- Referrals
- Automation
---
