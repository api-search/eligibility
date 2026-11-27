---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated by us in the United States. Those who choose to access the Services from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: You must be 18 years of age or older to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then "you" includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity with the authority to bind the entity to these Terms
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You agree that you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by the Company hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
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
name: Instinct
provenance_date: '2026-11-09'
provider_name: Instinct
provider_slug: instinct
slug: instinct-eligibility
source_date: '2026-11-09'
source_filename: instinct-eligibility.yml
source_heading: Eligibility
source_page: https://instinct.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instinct\naid: instinct\nurl: https://instinct.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated by us in the United States. Those who choose to access the Services from locations\n    outside the United States do so at their own initiative and are responsible for compliance with applicable local\n    laws.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then \"you\" includes you and that entity,\n    and\
  \ you represent and warrant that (a) you are an authorized representative of the entity with the authority\n    to bind the entity to these Terms\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree that you will not export or re-export, directly or indirectly, the Services and/or other information\n    or materials provided by the Company hereunder, to any country for which the United States or any other relevant\n    jurisdiction requires any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/instinct/eligibility/instinct-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Instinct's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
