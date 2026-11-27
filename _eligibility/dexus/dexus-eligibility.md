---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The information contained in this site is provided for Australian residents only and is not provided to any person who is a resident of any other country.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Financial products offered only in Australia
    text: Any financial products included on this site are only intended for offer within Australia and may only be subscribed for by an Australian resident.
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
name: Dexus
provenance_date: '2026-11-09'
provider_name: Dexus
provider_slug: dexus
slug: dexus-eligibility
source_date: '2026-11-09'
source_filename: dexus-eligibility.yml
source_heading: Eligibility
source_page: https://www.dexus.com/general/terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dexus\naid: dexus\nurl: https://www.dexus.com/general/terms-and-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The information contained in this site is provided for Australian residents only and is not provided to\n    any person who is a resident of any other country.\nentity_types: []\nrestricted_uses:\n- summary: Financial products offered only in Australia\n  text: Any financial products included on this site are only intended for offer within Australia and may only be\n    subscribed for by an Australian resident.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dexus/eligibility/dexus-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Dexus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Real Assets
- Funds Management
- Infrastructure
- Property Management
- Australia
---
