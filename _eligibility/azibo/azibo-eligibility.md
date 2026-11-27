---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is offered and available to Users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
  entity_types:
  - text: This Website is offered and available to Users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  minimum_age:
    text: This Website is offered and available to Users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No legal advice
    text: The Services do not include or constitute legal advice.
  - summary: Prohibited content and conduct
    text: Provide false, inaccurate or misleading information;
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
name: Azibo
provenance_date: '2026-11-09'
provider_name: Azibo
provider_slug: azibo
slug: azibo-eligibility
source_date: '2026-11-09'
source_filename: azibo-eligibility.yml
source_heading: Eligibility
source_page: https://www.azibo.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azibo\naid: azibo\nurl: https://www.azibo.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is offered and available to Users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nentity_types:\n- type: individual\n  text: This Website is offered and available to Users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nrestricted_uses:\n- summary: No legal advice\n  text: The Services do not include or constitute legal advice.\n\
  - summary: Prohibited content and conduct\n  text: Provide false, inaccurate or misleading information;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to Users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/azibo/eligibility/azibo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Azibo's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Property Management
- Fintech
- Software-as-a-Service
- Landlord Tools
- Company
---
