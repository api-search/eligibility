---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Clerky Services are directed to users in the United States. You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND YOU ARE LEGALLY ABLE TO ENTER INTO A CONTRACT.
    type: individual
  - text: If you access or use the Services on behalf of a company, organization, or other entity, then (a) "you" and "your" also refers to that entity, (b) you represent and warrant that you are a Representative of the entity with the authority to bind it to these terms of service
    type: business
  minimum_age:
    text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND YOU ARE LEGALLY ABLE TO ENTER INTO A CONTRACT.
    value: '18'
  restricted_uses:
  - summary: Securities offerings
    text: Any investor who intends to utilize the Services must be an accredited investor under United State securities laws, and it is your responsibility to verify such.
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
name: Clerky
provenance_date: '2026-11-09'
provider_name: Clerky
provider_slug: clerky
slug: clerky-eligibility
source_date: '2026-11-09'
source_filename: clerky-eligibility.yml
source_heading: Eligibility
source_page: https://www.clerky.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clerky\naid: clerky\nurl: https://www.clerky.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Clerky Services are directed to users in the United States. You may not use the Services if you are a resident\n    of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United\n    States government.\nentity_types:\n- type: individual\n  text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND YOU ARE LEGALLY ABLE TO ENTER\n    INTO A CONTRACT.\n- type: business\n  text: If you access or use the Services\
  \ on behalf of a company, organization, or other entity, then (a) \"you\"\n    and \"your\" also refers to that entity, (b) you represent and warrant that you are a Representative of the entity\n    with the authority to bind it to these terms of service\nrestricted_uses:\n- summary: Securities offerings\n  text: Any investor who intends to utilize the Services must be an accredited investor under United State securities\n    laws, and it is your responsibility to verify such.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND YOU ARE LEGALLY ABLE TO ENTER\n    INTO A CONTRACT.\n"
source_yaml_url: https://artifacts.apis.io/clerky/eligibility/clerky-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Clerky's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Startups
- Incorporation
- Fundraising
- Compliance
- Document Automation
- Y Combinator
---
