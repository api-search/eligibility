---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated by us in the United States. Those who choose to access the Services from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial or internal use only
    text: We hereby permit you to use the Services for your personal non-commercial or internal company use only
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
name: Unlearn
provenance_date: '2026-11-10'
provider_name: Unlearn
provider_slug: unlearn
slug: unlearn-eligibility
source_date: '2026-11-10'
source_filename: unlearn-eligibility.yml
source_heading: Eligibility
source_page: https://www.unlearn.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unlearn\naid: unlearn\nurl: https://www.unlearn.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated by us in the United States. Those who choose to access the Services from locations\n    outside the United States do so at their own initiative and are responsible for compliance with applicable local\n    laws.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\n\
  restricted_uses:\n- summary: Personal non-commercial or internal use only\n  text: We hereby permit you to use the Services for your personal non-commercial or internal company use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/unlearn/eligibility/unlearn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Unlearn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Artificial Intelligence
- Clinical Trials
- Digital Twin
- Machine Learning
- Healthcare
---
