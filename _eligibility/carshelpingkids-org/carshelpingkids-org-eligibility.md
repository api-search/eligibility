---
api_specs:
- filename: carshelpingkids-org-api-openapi.json
  format: json
  label: Cars Helping Kids — Car Donations Agent API API
  slug: cars-helping-kids-car-donations-agent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carshelpingkids-org/openapi/_original/carshelpingkids-org-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: donations welcomed from all 50 states
  entity_types:
  - text: You represent that you are at least 18 years old and that you are the legal owner of the vehicle (or are authorized to dispose of it by the legal owner or an executor).
    type: individual
  minimum_age:
    text: You represent that you are at least 18 years old
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may accept or decline any vehicle in our reasonable discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cars Helping Kids
provenance_date: '2026-11-09'
provider_name: Cars Helping Kids
provider_slug: carshelpingkids-org
slug: carshelpingkids-org-eligibility
source_date: '2026-11-09'
source_filename: carshelpingkids-org-eligibility.yml
source_heading: Eligibility
source_page: https://carshelpingkids.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cars Helping Kids\naid: carshelpingkids-org\nurl: https://carshelpingkids.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: donations welcomed from all 50 states\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old and that you are the legal owner of the vehicle (or are\n    authorized to dispose of it by the legal owner or an executor).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may accept or decline any vehicle in our reasonable discretion\nminimum_age:\n  value: '18'\n  text:\
  \ You represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/carshelpingkids-org/eligibility/carshelpingkids-org-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cars Helping Kids's own page on 2026-11-09.
synthetic: false
tags:
- Charity
- Non-Profit
- Vehicle Donation
- Education Support
- Georgia
---
