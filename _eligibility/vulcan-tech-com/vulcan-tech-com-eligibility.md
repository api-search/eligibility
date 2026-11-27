---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is a government entity, you access the Service solely in your official capacity
    type: government
  - text: Each account is assigned to one individual, and credentials may not be shared.
    type: individual
  minimum_age:
    text: The Service is intended for use by professionals and is not directed to anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No use violating law or Customer policy
    text: use the Service in violation of applicable law or Customer’s policies
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
name: Vulcan Technologies
provenance_date: '2026-11-10'
provider_name: Vulcan Technologies
provider_slug: vulcan-tech-com
slug: vulcan-tech-com-eligibility
source_date: '2026-11-10'
source_filename: vulcan-tech-com-eligibility.yml
source_heading: Eligibility
source_page: https://vulcan.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vulcan Technologies\naid: vulcan-tech-com\nurl: https://vulcan.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If Customer is a government entity, you access the Service solely in your official capacity\n- type: individual\n  text: Each account is assigned to one individual, and credentials may not be shared.\nrestricted_uses:\n- summary: No use violating law or Customer policy\n  text: use the Service in violation of applicable law or Customer’s policies\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for use by professionals and is not directed to anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/vulcan-tech-com/eligibility/vulcan-tech-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vulcan Technologies's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Government
---
