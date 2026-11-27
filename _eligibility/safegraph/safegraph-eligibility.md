---
claim_count: 4
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
  - summary: Identifying known individuals
    text: use the Data to attempt to identify behavior of a known individual for any reason
  - summary: Health care POI ad targeting
    text: use the Data to do advertising targeting or attribution of individuals based on visits to any health care point of interest
  - summary: Protest analysis
    text: use the Data to analyze, study, or report on protests or social demonstrations
  - summary: Financial investing with Spend data
    text: as it solely relates to Data referred to as Spend, use the Data for purposes of investing in financial instruments
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
name: SafeGraph
provenance_date: '2026-11-10'
provider_name: SafeGraph
provider_slug: safegraph
slug: safegraph-eligibility
source_date: '2026-11-10'
source_filename: safegraph-eligibility.yml
source_heading: Eligibility
source_page: https://www.safegraph.com/terms-of-services/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SafeGraph\naid: safegraph\nurl: https://www.safegraph.com/terms-of-services/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Identifying known individuals\n  text: use the Data to attempt to identify behavior of a known individual for any reason\n- summary: Health care POI ad targeting\n  text: use the Data to do advertising targeting or attribution of individuals based on visits to any health care\n    point of interest\n- summary: Protest analysis\n  text: use the Data to analyze, study, or report on protests or social demonstrations\n\
  - summary: Financial investing with Spend data\n  text: as it solely relates to Data referred to as Spend, use the Data for purposes of investing in financial instruments\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/safegraph/eligibility/safegraph-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 4 quoted statements, read from SafeGraph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Analytics
- Location Intelligence
- Points of Interest
- Geospatial
- Geocoding
- Foot Traffic
- Data Delivery
---
