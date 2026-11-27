---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is intended for use by Users of 18 years of age and older.
    type: individual
  - text: or the entity on whose behalf You are agreeing to these Terms.
    type: business
  minimum_age:
    text: The Website is intended for use by Users of 18 years of age and older.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: This Website is not for medical emergencies.
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
name: Belong Health
provenance_date: '2026-11-09'
provider_name: Belong Health
provider_slug: belong-health
slug: belong-health-eligibility
source_date: '2026-11-09'
source_filename: belong-health-eligibility.yml
source_heading: Eligibility
source_page: https://belong-health.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Belong Health\naid: belong-health\nurl: https://belong-health.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is intended for use by Users of 18 years of age and older.\n- type: business\n  text: or the entity on whose behalf You are agreeing to these Terms.\nrestricted_uses:\n- summary: Not for emergencies\n  text: This Website is not for medical emergencies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is intended for\
  \ use by Users of 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/belong-health/eligibility/belong-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Belong Health's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Insurance
- Medicare
- Healthcare
- Platform
- Company
---
