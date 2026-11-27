---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are designed for business use by organizations and their authorized users.
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Purpose limitation
    text: You may not access or use the Services for any purpose other than that for which we make the Services available.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Drivepoint
provenance_date: '2026-11-09'
provider_name: Drivepoint
provider_slug: drivepoint
slug: drivepoint-eligibility
source_date: '2026-11-09'
source_filename: drivepoint-eligibility.yml
source_heading: Eligibility
source_page: https://www.drivepoint.ai/terms/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Drivepoint\naid: drivepoint\nurl: https://www.drivepoint.ai/terms/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: The Services are designed for business use by organizations and their authorized users.\nrestricted_uses:\n- summary: Purpose limitation\n  text: You may not access or use the Services for any\
  \ purpose other than that for which we make the Services available.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/drivepoint/eligibility/drivepoint-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Drivepoint's own page on 2026-11-09.
synthetic: false
tags:
- AI Finance
- Consumer Brand
- Financial Modeling
- Forecasting
- Data Consolidation
- Reporting
- Finance Platform
---
