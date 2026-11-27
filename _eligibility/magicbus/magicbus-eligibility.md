---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country.
  entity_types:
  - text: You must be at least 18 years old to use the Platform.
    type: individual
  - text: If you agree to these Terms on behalf of an organization, then you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your personal, non-commercial use
  - summary: Disruptive behavior while riding
    text: engage in disruptive behavior or consume illegal substances while receiving Transportation Services reserved through the Platform
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
name: MagicBus
provenance_date: '2026-11-10'
provider_name: MagicBus
provider_slug: magicbus
slug: magicbus-eligibility
source_date: '2026-11-10'
source_filename: magicbus-eligibility.yml
source_heading: Eligibility
source_page: https://www.magicbus.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MagicBus\naid: magicbus\nurl: https://www.magicbus.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a \"terrorist supporting\" country.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Platform.\n- type: business\n  text: If you agree to these Terms on behalf of an organization, then you represent and warrant that you have the\n    authority to bind that\
  \ organization to these Terms.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: solely for your personal, non-commercial use\n- summary: Disruptive behavior while riding\n  text: engage in disruptive behavior or consume illegal substances while receiving Transportation Services reserved\n    through the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/magicbus/eligibility/magicbus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from MagicBus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Vanpool
- Commuting
- Transportation
- Rideshare
- Transit
---
