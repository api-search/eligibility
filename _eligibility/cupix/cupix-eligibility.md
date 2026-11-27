---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If Your principal place of business or residence is in the United States, Canada, Europe or Middle East, these Terms will be between You and Cupix America Inc., a Texas corporation.
  entity_types:
  - text: if You are an individual, where You reside
    type: individual
  - text: If You will use the Services on behalf of a legal entity or similar organization, You represent and warrant that You have the right, authority and capacity to act on behalf of and bind such legal entity or similar organization.
    type: business
  minimum_age:
    text: The Services are not directed to, and may not be used by, individuals under the age of thirteen (13).
    value: '13'
  restricted_uses:
  - summary: Geographic photography and use restrictions
    text: '(2) United States and using the Services for the following purposes: (i) new and used automotive vehicle sales.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You authorize Us to verify Your Registration Data at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cupix
provenance_date: '2026-11-09'
provider_name: Cupix
provider_slug: cupix
slug: cupix-eligibility
source_date: '2026-11-09'
source_filename: cupix-eligibility.yml
source_heading: Eligibility
source_page: https://www.cupix.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cupix\naid: cupix\nurl: https://www.cupix.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If Your principal place of business or residence is in the United States, Canada, Europe or Middle East,\n    these Terms will be between You and Cupix America Inc., a Texas corporation.\nentity_types:\n- type: individual\n  text: if You are an individual, where You reside\n- type: business\n  text: If You will use the Services on behalf of a legal entity or similar organization, You represent and warrant\n    that You have the right, authority and capacity to act on behalf\
  \ of and bind such legal entity or similar organization.\nrestricted_uses:\n- summary: Geographic photography and use restrictions\n  text: '(2) United States and using the Services for the following purposes: (i) new and used automotive vehicle\n    sales.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You authorize Us to verify Your Registration Data at any time.\nminimum_age:\n  value: '13'\n  text: The Services are not directed to, and may not be used by, individuals under the age of thirteen (13).\n"
source_yaml_url: https://artifacts.apis.io/cupix/eligibility/cupix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cupix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Spatial Intelligence
- Digital Twin
- Artificial Intelligence
---
