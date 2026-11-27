---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Rediem may limit the availability of the Services to any person, geographic area or jurisdiction it chooses; no specific countries are listed.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: Some content is prohibited when accessing or using the Services.
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
name: Rediem
provenance_date: '2026-11-10'
provider_name: Rediem
provider_slug: rediem
slug: rediem-eligibility
source_date: '2026-11-10'
source_filename: rediem-eligibility.yml
source_heading: Eligibility
source_page: https://www.rediem.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rediem\naid: rediem\nurl: https://www.rediem.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Rediem may limit the availability of the Services to any person, geographic area or jurisdiction it chooses;\n    no specific countries are listed.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content\n  text: Some content is prohibited when accessing or using the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rediem/eligibility/rediem-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Rediem's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Loyalty
- Community
- Marketing
- No-Code
---
