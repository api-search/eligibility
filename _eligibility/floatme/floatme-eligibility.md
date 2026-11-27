---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must (1) be a citizen or permanent legal resident of the United States
  entity_types:
  - text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Floats not available in certain states
    text: Due to state regulations, Floats are not available to residents of Connecticut, the District of Columbia, or a U.S. territory. As of January 1, 2025 residents of Nevada are not eligible for Floats.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize us to make any inquiries we consider necessary to validate your identity. If you do not respond to such inquiries or we cannot verify your identity, we can refuse to allow you to use any or all of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FloatMe
provenance_date: '2026-11-09'
provider_name: FloatMe
provider_slug: floatme
slug: floatme-eligibility
source_date: '2026-11-09'
source_filename: floatme-eligibility.yml
source_heading: Eligibility
source_page: https://floatme.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FloatMe\naid: floatme\nurl: https://floatme.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must (1) be a citizen or permanent legal resident of the United States\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction.\nrestricted_uses:\n- summary: Floats not available in certain states\n  text: Due to state regulations, Floats are not available to residents of Connecticut, the District of Columbia,\n    or a U.S. territory. As of January 1, 2025 residents of Nevada\
  \ are not eligible for Floats.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize us to make any inquiries we consider necessary to validate your identity. If you do not respond\n    to such inquiries or we cannot verify your identity, we can refuse to allow you to use any or all of the Services.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/floatme/eligibility/floatme-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from FloatMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Cash Advance
- Personal Finance
- Banking
- Financial Wellness
- Consumer
---
