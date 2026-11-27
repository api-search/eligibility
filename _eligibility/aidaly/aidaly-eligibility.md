---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting the terms of this Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal activity or IP violation
    text: use the Services either directly or indirectly to support any activity that is illegal or that violates the proprietary rights of others
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
name: Aidaly
provenance_date: '2026-11-09'
provider_name: Aidaly
provider_slug: aidaly
slug: aidaly-eligibility
source_date: '2026-11-09'
source_filename: aidaly-eligibility.yml
source_heading: Eligibility
source_page: https://aidaly.com/service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aidaly\naid: aidaly\nurl: https://aidaly.com/service-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting the terms of this Agreement on behalf of a company or other legal entity, you represent\n    and warrant that you have the authority to bind that company or other legal entity\nrestricted_uses:\n- summary: No illegal activity or IP violation\n  text: use the Services either directly or indirectly to support any activity that is illegal or that violates\n    the proprietary rights of others\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aidaly/eligibility/aidaly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Aidaly's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Home Care
- Caregiving
- Medicaid
- Health Tech
- Digital Health
- Benefits
- Workforce
- United States
- Company
---
