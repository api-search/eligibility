---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Baselane provides the Services for use only by persons located in the United States.
  entity_types:
  - text: IF YOU ARE ENTERING INTO THE TERMS OF USE ON BEHALF OF AN ENTITY
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH BASELANE
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Persons barred under US or local law
    text: not a person barred from using the Services under the laws of the United States, your place of residence or any other applicable jurisdiction
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
name: Baselane
provenance_date: '2026-11-09'
provider_name: Baselane
provider_slug: baselane
slug: baselane-eligibility
source_date: '2026-11-09'
source_filename: baselane-eligibility.yml
source_heading: Eligibility
source_page: https://www.baselane.com/legal/general-agreements/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baselane\naid: baselane\nurl: https://www.baselane.com/legal/general-agreements/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Baselane provides the Services for use only by persons located in the United States.\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THE TERMS OF USE ON BEHALF OF AN ENTITY\nrestricted_uses:\n- summary: Persons barred under US or local law\n  text: not a person barred from using the Services under the laws of the United States, your place of residence\n    or any other applicable jurisdiction\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age to form a binding contract\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH BASELANE\n"
source_yaml_url: https://artifacts.apis.io/baselane/eligibility/baselane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Baselane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- PropTech
- Landlord Banking
- Rent Collection
- Real Estate
- Banking
- Bookkeeping
---
