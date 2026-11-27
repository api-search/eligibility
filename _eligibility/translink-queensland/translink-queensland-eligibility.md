---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Brand use needs approval
    text: If you or any third party wishes to convey information about the Translink network, logo or images in public material, you must gain approval by submitting a request and intended use
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: you must gain approval by submitting a request and intended use
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Translink
provenance_date: '2026-11-10'
provider_name: Translink
provider_slug: translink-queensland
slug: translink-queensland-eligibility
source_date: '2026-11-10'
source_filename: translink-queensland-eligibility.yml
source_heading: Eligibility
source_page: https://translink.com.au/about-translink/open-data/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Translink\naid: translink-queensland\nurl: https://translink.com.au/about-translink/open-data/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Brand use needs approval\n  text: If you or any third party wishes to convey information about the Translink network, logo or images in public\n    material, you must gain approval by submitting a request and intended use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: you must gain approval by submitting a request and intended use\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/translink-queensland/eligibility/translink-queensland-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Translink's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Public Transport
- Transit
- GTFS
- GTFS Realtime
- Open Data
- Government
- Queensland
- Australia
---
