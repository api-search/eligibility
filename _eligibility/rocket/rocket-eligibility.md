---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not located in, under the control of, or a national or resident of a U.S. embargoed country or territory
  entity_types:
  - text: (a) of legal age (18 years of age or older or otherwise of legal age in your resident jurisdiction) and competent to agree to these Terms
    type: individual
  - text: If you are accessing Website or using Rocket Services on behalf of an organization or legal entity, you are agreeing to the Terms for that organization
    type: business
  minimum_age:
    text: of legal age (18 years of age or older or otherwise of legal age in your resident jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Export-controlled information
    text: You will not submit to the Rocket Services any information that is controlled under the U.S. International Traffic in Arms Regulations.
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
name: Rocket
provenance_date: '2026-11-10'
provider_name: Rocket
provider_slug: rocket
slug: rocket-eligibility
source_date: '2026-11-10'
source_filename: rocket-eligibility.yml
source_heading: Eligibility
source_page: https://www.rocket.new/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rocket\naid: rocket\nurl: https://www.rocket.new/terms-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not located in, under the control of, or a national or resident of a U.S. embargoed country or territory\nentity_types:\n- type: individual\n  text: (a) of legal age (18 years of age or older or otherwise of legal age in your resident jurisdiction) and\n    competent to agree to these Terms\n- type: business\n  text: If you are accessing Website or using Rocket Services on behalf of an organization or legal entity, you\n    are agreeing to the Terms for that organization\n\
  restricted_uses:\n- summary: Export-controlled information\n  text: You will not submit to the Rocket Services any information that is controlled under the U.S. International\n    Traffic in Arms Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: of legal age (18 years of age or older or otherwise of legal age in your resident jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/rocket/eligibility/rocket-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Rocket's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- App Builder
- No-Code
- Low-Code
- Developer Tools
- Web Development
- Mobile Development
- Generative AI
---
