---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organisation, you agree to these Terms on its behalf and confirm you have authority to do so.
    type: business
  minimum_age:
    text: You must be at least 16 years old and able to form a binding contract to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful or infringing use
    text: use the Service for any unlawful purpose, or to infringe the rights of others
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
name: ConferenceGrid
provenance_date: '2026-11-09'
provider_name: ConferenceGrid
provider_slug: conferencegrid-com
slug: conferencegrid-com-eligibility
source_date: '2026-11-09'
source_filename: conferencegrid-com-eligibility.yml
source_heading: Eligibility
source_page: https://conferencegrid.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConferenceGrid\naid: conferencegrid-com\nurl: https://conferencegrid.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organisation, you agree to these Terms on its behalf and confirm\n    you have authority to do so.\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: use the Service for any unlawful purpose, or to infringe the rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n\
  \  text: You must be at least 16 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/conferencegrid-com/eligibility/conferencegrid-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ConferenceGrid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Conferences
- Events
- Trade Shows
- Sales Intelligence
- B2B
- Sponsorship
- MCP
---
