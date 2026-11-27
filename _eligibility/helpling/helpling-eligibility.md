---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: einer selbstständigen Tätigkeit in Deutschland nachzugehen
  entity_types:
  - text: Diese AGB gelten nur gegenüber Unternehmern im Sinne von § 14 BGB.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Helpling
provenance_date: '2026-11-09'
provider_name: Helpling
provider_slug: helpling
slug: helpling-eligibility
source_date: '2026-11-09'
source_filename: helpling-eligibility.yml
source_heading: Eligibility
source_page: https://www.helpling.de/agb-reinigungskraft-14112025/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Helpling\naid: helpling\nurl: https://www.helpling.de/agb-reinigungskraft-14112025/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: einer selbstständigen Tätigkeit in Deutschland nachzugehen\nentity_types:\n- type: business\n  text: Diese AGB gelten nur gegenüber Unternehmern im Sinne von § 14 BGB.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/helpling/eligibility/helpling-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Helpling's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cleaning Services
- Home Services
- Marketplace
- On-Demand
- Gig Economy
- Consumer
- Germany
---
