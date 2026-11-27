---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal or otherwise violate any applicable law.
  entity_types:
  - text: If you use our Services on behalf of another person or entity, (a) all references to “you” throughout these Terms will include that person or entity
    type: other
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: Sell, resell or commercially use our Services;
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
name: Glydways
provenance_date: '2026-11-09'
provider_name: Glydways
provider_slug: glydways
slug: glydways-eligibility
source_date: '2026-11-09'
source_filename: glydways-eligibility.yml
source_heading: Eligibility
source_page: https://www.glydways.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glydways\naid: glydways\nurl: https://www.glydways.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory\n    or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal\n    or otherwise violate any applicable law.\nentity_types:\n- type: other\n  text: If you use our Services on behalf of another person or entity, (a) all references to “you” throughout these\n    Terms will include that person or entity\n\
  restricted_uses:\n- summary: Commercial use prohibited\n  text: Sell, resell or commercially use our Services;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/glydways/eligibility/glydways-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Glydways's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Urban Mobility
- Autonomous Vehicles
- Transit
- Infrastructure
- Mobility
---
