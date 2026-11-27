---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: the Services may not be exported or re-exported (a) into any U.S. embargoed countries or any country that has been designated by the U.S. Government as a “terrorist supporting” country
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
name: Biobot
provenance_date: '2026-11-09'
provider_name: Biobot
provider_slug: biobot
slug: biobot-eligibility
source_date: '2026-11-09'
source_filename: biobot-eligibility.yml
source_heading: Eligibility
source_page: https://biobot.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biobot\naid: biobot\nurl: https://biobot.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Export restrictions\n  text: the Services may not be exported or re-exported (a)\
  \ into any U.S. embargoed countries or any country that\n    has been designated by the U.S. Government as a “terrorist supporting” country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/biobot/eligibility/biobot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Biobot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Wastewater
- Epidemiology
- Public Health
- Data
- Analytics
- Government
- Life Sciences
---
