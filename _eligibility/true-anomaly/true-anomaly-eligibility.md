---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
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
name: True Anomaly
provenance_date: '2026-11-10'
provider_name: True Anomaly
provider_slug: true-anomaly
slug: true-anomaly-eligibility
source_date: '2026-11-10'
source_filename: true-anomaly-eligibility.yml
source_heading: Eligibility
source_page: https://www.trueanomaly.space/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: True Anomaly\naid: true-anomaly\nurl: https://www.trueanomaly.space/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to the United States government embargo, or that has been\n    designated by the United States government as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/true-anomaly/eligibility/true-anomaly-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from True Anomaly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Space
- Defense
- Aerospace
- Autonomy
- Software
- National Security
- Spacecraft
---
