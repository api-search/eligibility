---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal or otherwise violate any applicable law.
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  - text: If you use our Services on behalf of another person or entity, (a) all references to “you” throughout these Terms will include that person or entity
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Fearn may contact you by telephone, mail or email to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fearn
provenance_date: '2026-11-09'
provider_name: Fearn
provider_slug: fearn
slug: fearn-eligibility
source_date: '2026-11-09'
source_filename: fearn-eligibility.yml
source_heading: Eligibility
source_page: https://fearn.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fearn\naid: fearn\nurl: https://fearn.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory\n    or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal\n    or otherwise violate any applicable law.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\n- type: business\n  text: If you use our Services on behalf of another person or entity, (a) all references to\
  \ “you” throughout these\n    Terms will include that person or entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Fearn may contact you by telephone, mail or email to verify your information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/fearn/eligibility/fearn-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fearn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Patents
- Intellectual Property
- Legal Tech
- Patent Prosecution
- Artificial Intelligence
- Legal Services
- Startups
---
