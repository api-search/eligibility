---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country that is subject to a Canadian or U.S. Government embargo, or that has been designated by the Canadian or U.S. Government as a “terrorist supporting” country
  minimum_age:
    text: If you are residing in a jurisdiction which restricts the use of internet-based applications according to age
    value: not stated
  restricted_uses:
  - summary: No commercial or third-party benefit use
    text: You will not use the Services for any commercial purposes or for the benefit of any third party
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
name: Metricwire
provenance_date: '2026-11-10'
provider_name: Metricwire
provider_slug: metricwire
slug: metricwire-eligibility
source_date: '2026-11-10'
source_filename: metricwire-eligibility.yml
source_heading: Eligibility
source_page: https://metricwire.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metricwire\naid: metricwire\nurl: https://metricwire.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country that is subject to a Canadian or U.S. Government embargo,\n    or that has been designated by the Canadian or U.S. Government as a “terrorist supporting” country\nentity_types: []\nrestricted_uses:\n- summary: No commercial or third-party benefit use\n  text: You will not use the Services for any commercial purposes or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: not stated\n  text: If you are residing in a jurisdiction which restricts the use of internet-based applications according to\n    age\n"
source_yaml_url: https://artifacts.apis.io/metricwire/eligibility/metricwire-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Metricwire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Research
- Data Collection
- Ecological Momentary Assessment
- Experience Sampling
- Digital Health
- Clinical Trials
- Surveys
- Patient Reported Outcomes
- Mobile
---
