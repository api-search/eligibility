---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a U.S., EU, or other sovereign government embargo, or that has been designated by the government as a "terrorist-supporting" country.
  entity_types:
  - text: Enterprise customers may have custom payment method agreements.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: Engaging in any activity that is unlawful or harmful to others.
  - summary: Circumventing usage limits
    text: Creating multiple accounts to circumvent usage limits.
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
name: Amie
provenance_date: '2026-11-09'
provider_name: Amie
provider_slug: amie
slug: amie-eligibility
source_date: '2026-11-09'
source_filename: amie-eligibility.yml
source_heading: Eligibility
source_page: https://amie.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amie\naid: amie\nurl: https://amie.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a U.S., EU, or other\n    sovereign government embargo, or that has been designated by the government as a \"terrorist-supporting\" country.\nentity_types:\n- type: business\n  text: Enterprise customers may have custom payment method agreements.\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: Engaging in any activity that is unlawful or harmful to others.\n- summary: Circumventing usage\
  \ limits\n  text: Creating multiple accounts to circumvent usage limits.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amie/eligibility/amie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Amie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Calendar
- Productivity
- Meetings
- AI Assistant
- Scheduling
- Task
- Notes
- MCP
---
