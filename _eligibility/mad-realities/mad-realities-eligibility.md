---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Those who choose to access the Services from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: You must be eighteen (18) years of age or older to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be eighteen (18) years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by the Company hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
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
name: Mad Realities
provenance_date: '2026-11-10'
provider_name: Mad Realities
provider_slug: mad-realities
slug: mad-realities-eligibility
source_date: '2026-11-10'
source_filename: mad-realities-eligibility.yml
source_heading: Eligibility
source_page: https://www.madrealities.tv/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mad Realities\naid: mad-realities\nurl: https://www.madrealities.tv/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Those who choose to access the Services from locations outside the United States do so at their own initiative\n    and are responsible for compliance with applicable local laws.\nentity_types:\n- type: individual\n  text: You must be eighteen (18) years of age or older to use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a)\
  \ you are an authorized representative of the entity\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials\n    provided by the Company hereunder, to any country for which the United States or any other relevant jurisdiction\n    requires any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/mad-realities/eligibility/mad-realities-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Mad Realities's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Entertainment
- Media
- Creators
- Video
- Streaming
---
