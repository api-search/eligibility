---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual accepting this Agreement who plans to access or use the Service(s) in a personal capacity
    type: individual
  - text: the organization that the individual accepting this Agreement represents
    type: business
  minimum_age:
    text: AFFIRMS THAT IT IS AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Jurisdictions not giving effect to terms
    text: Use of the Service(s) is not authorized in any jurisdiction that does not give effect to all provisions of the Agreement
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
name: Factory
provenance_date: '2026-11-09'
provider_name: Factory
provider_slug: factory-ai
slug: factory-ai-eligibility
source_date: '2026-11-09'
source_filename: factory-ai-eligibility.yml
source_heading: Eligibility
source_page: https://factory.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Factory\naid: factory-ai\nurl: https://factory.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual accepting this Agreement who plans to access or use the Service(s) in a personal capacity\n- type: business\n  text: the organization that the individual accepting this Agreement represents\nrestricted_uses:\n- summary: Jurisdictions not giving effect to terms\n  text: Use of the Service(s) is not authorized in any jurisdiction that does not give effect to all provisions\n    of the Agreement\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AFFIRMS THAT IT IS AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/factory-ai/eligibility/factory-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Factory's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Autonomous
- Developer Tools
- Software Engineering
- Code Generation
- DevOps
---
