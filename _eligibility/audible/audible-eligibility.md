---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some of our Content may be offered in limited territories, and we may use geofiltering technology to restrict access outside of those territories.
  entity_types:
  - text: By signing up for or using the Service, you agree to the Terms on behalf of yourself and all members of your household and others who use the Service under your account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial or illegal use
    text: use the Service or Content for any commercial or illegal purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to accept or refuse membership or to restrict use of the Service in our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Audible
provenance_date: '2026-11-09'
provider_name: Audible
provider_slug: audible
slug: audible-eligibility
source_date: '2026-11-09'
source_filename: audible-eligibility.yml
source_heading: Eligibility
source_page: https://www.audible.com/legal/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Audible\naid: audible\nurl: https://www.audible.com/legal/conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some of our Content may be offered in limited territories, and we may use geofiltering technology to restrict\n    access outside of those territories.\nentity_types:\n- type: individual\n  text: By signing up for or using the Service, you agree to the Terms on behalf of yourself and all members of\n    your household and others who use the Service under your account.\nrestricted_uses:\n- summary: No commercial or illegal use\n  text: use the Service or Content\
  \ for any commercial or illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to accept or refuse membership or to restrict use of the Service in our discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/audible/eligibility/audible-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Audible's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Audiobooks
- Podcasts
- Entertainment
- Media
- Streaming
- Amazon
---
