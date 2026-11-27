---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Website is designed for the use of adults (18 years or older) and is not intended for minors.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful material
    text: send and/or store infringing, obscene, threatening, libelous, or otherwise unlawful material, including material harmful to children or violating third party rights
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
name: Dualbird
provenance_date: '2026-11-09'
provider_name: Dualbird
provider_slug: dualbird
slug: dualbird-eligibility
source_date: '2026-11-09'
source_filename: dualbird-eligibility.yml
source_heading: Eligibility
source_page: https://dualbird.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dualbird\naid: dualbird\nurl: https://dualbird.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: send and/or store infringing, obscene, threatening, libelous, or otherwise unlawful material, including\n    material harmful to children or violating third party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is designed for the use of adults (18 years or older) and is not intended for minors.\n"
source_yaml_url: https://artifacts.apis.io/dualbird/eligibility/dualbird-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Dualbird's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Data Processing
- AI Infrastructure
- Apache Spark
- Amazon EMR
- Analytics
- Hardware Acceleration
- Big Data
---
