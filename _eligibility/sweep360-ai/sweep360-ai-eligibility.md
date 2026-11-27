---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF THE INDIVIDUAL ENTERING INTO THE AGREEMENT OR OTHERWISE ACCESSING OR USING THE SERVICES IS DOING SO ON BEHALF OF, OR WITHIN HIS OR HER CAPACITY AS A REPRESENTATIVE, AGENT, OR EMPLOYEE OF AN ENTITY, SUCH INDIVIDUAL AND SUCH ENTITY AGREES
    type: business
  minimum_age:
    text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: THE SERVICES ARE NOT FAULT-TOLERANT AND ARE NOT DESIGNED OR INTENDED FOR HIGH-RISK ACTIVITIES SUCH AS USE IN HAZARDOUS ENVIRONMENTS
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
name: Sweep
provenance_date: '2026-11-10'
provider_name: Sweep
provider_slug: sweep360-ai
slug: sweep360-ai-eligibility
source_date: '2026-11-10'
source_filename: sweep360-ai-eligibility.yml
source_heading: Eligibility
source_page: https://sweep360.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sweep\naid: sweep360-ai\nurl: https://sweep360.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL ENTERING INTO THE AGREEMENT OR OTHERWISE ACCESSING OR USING THE SERVICES IS DOING SO ON\n    BEHALF OF, OR WITHIN HIS OR HER CAPACITY AS A REPRESENTATIVE, AGENT, OR EMPLOYEE OF AN ENTITY, SUCH INDIVIDUAL\n    AND SUCH ENTITY AGREES\nrestricted_uses:\n- summary: High-risk activities\n  text: THE SERVICES ARE NOT FAULT-TOLERANT AND ARE NOT DESIGNED OR INTENDED FOR HIGH-RISK ACTIVITIES SUCH\
  \ AS USE\n    IN HAZARDOUS ENVIRONMENTS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/sweep360-ai/eligibility/sweep360-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sweep's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
