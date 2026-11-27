---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We ship to approximately 90 countries around the world.
  entity_types:
  - text: If you are under the age of 18, you may use the Site only with involvement of a parent or legal guardian.
    type: individual
  minimum_age:
    text: If you are under the age of 18, you may use the Site only with involvement of a parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: No commercial resale purchases
    text: Commercial purchases for resale are not permitted.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: provide true, accurate, current and complete information about yourself as prompted by the registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dia
provenance_date: '2026-11-09'
provider_name: Dia
provider_slug: dia
slug: dia-eligibility
source_date: '2026-11-09'
source_filename: dia-eligibility.yml
source_heading: Eligibility
source_page: https://www.dia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dia\naid: dia\nurl: https://www.dia.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We ship to approximately 90 countries around the world.\nentity_types:\n- type: individual\n  text: If you are under the age of 18, you may use the Site only with involvement of a parent or legal guardian.\nrestricted_uses:\n- summary: No commercial resale purchases\n  text: Commercial purchases for resale are not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: provide true, accurate, current and complete information about yourself as prompted\
  \ by the registration\n    form.\nminimum_age:\n  value: '18'\n  text: If you are under the age of 18, you may use the Site only with involvement of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/dia/eligibility/dia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Dia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fashion
- Retail
- E-Commerce
- Personal Styling
- Subscription
- Apparel
---
