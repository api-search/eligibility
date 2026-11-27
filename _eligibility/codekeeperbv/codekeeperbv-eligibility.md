---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'No software from the Service may be downloaded, exported or re-exported: (a) into any European Union and/or U.S. embargoed countries'
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
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
name: Codekeeperbv
provenance_date: '2026-11-09'
provider_name: Codekeeperbv
provider_slug: codekeeperbv
slug: codekeeperbv-eligibility
source_date: '2026-11-09'
source_filename: codekeeperbv-eligibility.yml
source_heading: Eligibility
source_page: https://codekeeper.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codekeeperbv\naid: codekeeperbv\nurl: https://codekeeper.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'No software from the Service may be downloaded, exported or re-exported: (a) into any European Union and/or\n    U.S. embargoed countries'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/codekeeperbv/eligibility/codekeeperbv-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Codekeeperbv's own page on 2026-11-09.
synthetic: false
tags:
- Software Escrow
- Continuity
- Software-as-a-Service
- Backup
- Artificial Intelligence
- Compliance
- Vendor Risk
---
