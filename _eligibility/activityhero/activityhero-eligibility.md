---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States. You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: You may use the Service only if you can form a binding contract with ActivityHero
    type: individual
  - text: If you open a ActivityHero account on behalf of a company, organization, or other entity, then (a) "you" includes you and that entity
    type: business
  minimum_age:
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Commercial solicitation prohibited
    text: using the Service for any commercial solicitation purposes
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
name: ActivityHero
provenance_date: '2026-11-09'
provider_name: ActivityHero
provider_slug: activityhero
slug: activityhero-eligibility
source_date: '2026-11-09'
source_filename: activityhero-eligibility.yml
source_heading: Eligibility
source_page: https://www.activityhero.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ActivityHero\naid: activityhero\nurl: https://www.activityhero.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States. You may not use the Service if you are a resident\n    of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United\n    States government.\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a binding\
  \ contract with ActivityHero\n- type: business\n  text: If you open a ActivityHero account on behalf of a company, organization, or other entity, then (a) \"you\"\n    includes you and that entity\nrestricted_uses:\n- summary: Commercial solicitation prohibited\n  text: using the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/activityhero/eligibility/activityhero-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ActivityHero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Kids Activities
- Camps
- Classes
- Marketplace
- Registration
- Webhook
- Education
---
