---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Marketplace is offered and available to Users 18 years of age or older who reside in the United States or any of its territories or possessions.
  minimum_age:
    text: This Marketplace is offered and available to Users 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Use outside US law
    text: access to it is prohibited from territories where the Marketplace or services available through the Marketplace are illegal.
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
name: CareRev
provenance_date: '2026-11-09'
provider_name: CareRev
provider_slug: carerev
slug: carerev-eligibility
source_date: '2026-11-09'
source_filename: carerev-eligibility.yml
source_heading: Eligibility
source_page: https://www.carerev.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CareRev\naid: carerev\nurl: https://www.carerev.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Marketplace is offered and available to Users 18 years of age or older who reside in the United States\n    or any of its territories or possessions.\nentity_types: []\nrestricted_uses:\n- summary: Use outside US law\n  text: access to it is prohibited from territories where the Marketplace or services available through the Marketplace\n    are illegal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: This Marketplace is offered and available to Users 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/carerev/eligibility/carerev-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CareRev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Systems
- Workforce Management
- Staffing
- Nursing
- Marketplace
- Scheduling
- Human Resources
- Labor Marketplace
---
