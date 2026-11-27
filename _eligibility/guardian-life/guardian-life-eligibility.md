---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Sites are directed to and are intended to be made available only to persons in the United States and are not intended for distribution to, or use by, any person in any other country or any jurisdiction where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: Software and other materials from Sites may be subject to export controls imposed by the United States and may not be downloaded or otherwise exported to any country or anyone prohibited by law.
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
name: Guardian Life
provenance_date: '2026-11-09'
provider_name: Guardian Life
provider_slug: guardian-life
slug: guardian-life-eligibility
source_date: '2026-11-09'
source_filename: guardian-life-eligibility.yml
source_heading: Eligibility
source_page: https://developer.guardianlife.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Guardian Life\naid: guardian-life\nurl: https://developer.guardianlife.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Sites are directed to and are intended to be made available only to persons in the United States and\n    are not intended for distribution to, or use by, any person in any other country or any jurisdiction where such\n    distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Export control restrictions\n  text: Software and other materials from Sites may be subject to export controls\
  \ imposed by the United States and\n    may not be downloaded or otherwise exported to any country or anyone prohibited by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/guardian-life/eligibility/guardian-life-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Guardian Life's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Life Insurance
- Disability Insurance
- Dental Insurance
- Employee Benefits
- Benefits Administration
- Group Insurance
- Underwriting
- Claims Processing
- LDEx
- Fortune 500
---
