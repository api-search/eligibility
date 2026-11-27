---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Licensee is barred from accessing or using the API... under the laws of the country in which Licensee is located
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical and manned aircraft control
    text: No Application will be designed, marketed, or used for control of manned aircraft or vehicles, any machinery that is not a UAV, or for any emergency or life-saving purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Airspace Link may allocate or decline to allocate a Key to Licensee or an End User on an API-by-API basis
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Airspace Link
provenance_date: '2026-11-09'
provider_name: Airspace Link
provider_slug: airspace-link
slug: airspace-link-eligibility
source_date: '2026-11-09'
source_filename: airspace-link-eligibility.yml
source_heading: Eligibility
source_page: https://airspacelink.com/terms-conditions-api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airspace Link\naid: airspace-link\nurl: https://airspacelink.com/terms-conditions-api\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Licensee is barred from accessing or using the API... under the laws of the country in which Licensee is\n    located\nentity_types: []\nrestricted_uses:\n- summary: Safety-critical and manned aircraft control\n  text: No Application will be designed, marketed, or used for control of manned aircraft or vehicles, any machinery\n    that is not a UAV, or for any emergency or life-saving purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Airspace Link may allocate or decline to allocate a Key to Licensee or an End User on an API-by-API basis\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airspace-link/eligibility/airspace-link-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Airspace Link's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Drones
- UAS
- Airspace
- Aviation
- LAANC
- UTM
- Geospatial
- Public Safety
- Logistics
---
