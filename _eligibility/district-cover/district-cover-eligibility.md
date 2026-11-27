---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you have reached the age of majority in your jurisdiction of residence, as our Services are not intended for minors.
    value: age of majority
  restricted_uses:
  - summary: Commercial solicitation via communication systems
    text: Use the communication systems provided by our Services for any commercial solicitation purposes, including to send unsolicited or unauthorized advertisements, spam, or chain letters;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To obtain coverage you must submit an application to District Cover, whether on our Site or otherwise. All applications are subject to underwriting approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: District Cover
provenance_date: '2026-11-09'
provider_name: District Cover
provider_slug: district-cover
slug: district-cover-eligibility
source_date: '2026-11-09'
source_filename: district-cover-eligibility.yml
source_heading: Eligibility
source_page: https://www.districtcover.com/our-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: District Cover\naid: district-cover\nurl: https://www.districtcover.com/our-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial solicitation via communication systems\n  text: Use the communication systems provided by our Services for any commercial solicitation purposes, including\n    to send unsolicited or unauthorized advertisements, spam, or chain letters;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To obtain coverage you must submit an application to District Cover, whether\
  \ on our Site or otherwise. All\n    applications are subject to underwriting approval.\nminimum_age:\n  value: age of majority\n  text: you have reached the age of majority in your jurisdiction of residence, as our Services are not intended\n    for minors.\n"
source_yaml_url: https://artifacts.apis.io/district-cover/eligibility/district-cover-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from District Cover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Commercial Insurance
- Underwriting
- Risk Management
- Surplus Lines
- Brokerage
---
