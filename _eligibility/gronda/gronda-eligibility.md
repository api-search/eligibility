---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You have not been prohibited from using the Services by EU or any other relevant jurisdiction.
  entity_types:
  - text: If you use the Services on behalf of a company or other legal entity, you represent that you are authorized to license and agree to the Agreement on behalf of that company or legal entity.
    type: business
  minimum_age:
    text: Children under 16 years of age may neither register as a member nor use the Services.
    value: '16'
  restricted_uses:
  - summary: No illegal use
    text: you do not use the Services for illegal purposes or for purposes prohibited by this Agreement.
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
name: Gronda
provenance_date: '2026-11-09'
provider_name: Gronda
provider_slug: gronda
slug: gronda-eligibility
source_date: '2026-11-09'
source_filename: gronda-eligibility.yml
source_heading: Eligibility
source_page: https://gronda.com/legal/conditions-user
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gronda\naid: gronda\nurl: https://gronda.com/legal/conditions-user\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You have not been prohibited from using the Services by EU or any other relevant jurisdiction.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other legal entity, you represent that you are authorized\n    to license and agree to the Agreement on behalf of that company or legal entity.\nrestricted_uses:\n- summary: No illegal use\n  text: you do not use the Services for illegal purposes or for purposes prohibited by this Agreement.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Children under 16 years of age may neither register as a member nor use the Services.\n"
source_yaml_url: https://artifacts.apis.io/gronda/eligibility/gronda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gronda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Culinary
- Food
- Education
- Community
- Recipes
- Chefs
- Gastronomy
- Learning
---
