---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are permitted to use and access the Website on a personal, non-commercial basis.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or criminal purposes
    text: You may not misuse the Website, or any information, imagery or data from or underlying it, for or in connection with any unlawful or criminal purpose
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We are not obliged to approve your application, and we may revoke or limit your access to the Website or our approval at any time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Barclays7c03
provenance_date: '2026-11-09'
provider_name: Barclays7c03
provider_slug: barclays7c03
slug: barclays7c03-eligibility
source_date: '2026-11-09'
source_filename: barclays7c03-eligibility.yml
source_heading: Eligibility
source_page: https://home.barclays/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Barclays7c03\naid: barclays7c03\nurl: https://home.barclays/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are permitted to use and access the Website on a personal, non-commercial basis.\nrestricted_uses:\n- summary: Unlawful or criminal purposes\n  text: You may not misuse the Website, or any information, imagery or data from or underlying it, for or in connection\n    with any unlawful or criminal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We are not obliged to approve\
  \ your application, and we may revoke or limit your access to the Website or\n    our approval at any time\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/barclays7c03/eligibility/barclays7c03-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Barclays7c03's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Finance
- Global
- Corporate
---
