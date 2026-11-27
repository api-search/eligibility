---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist-supporting" country;
  minimum_age:
    text: Are at least 18 years old .
    value: '18'
  restricted_uses:
  - summary: Not for emergency or critical situations
    text: Assindo is not designed for use in emergencies or critical situations.
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
name: Assindo
provenance_date: '2026-11-09'
provider_name: Assindo
provider_slug: assindo-com
slug: assindo-com-eligibility
source_date: '2026-11-09'
source_filename: assindo-com-eligibility.yml
source_heading: Eligibility
source_page: https://assindo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assindo\naid: assindo-com\nurl: https://assindo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a \"terrorist-supporting\" country;\nentity_types: []\nrestricted_uses:\n- summary: Not for emergency or critical situations\n  text: Assindo is not designed for use in emergencies or critical situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Are at least 18 years\
  \ old .\n"
source_yaml_url: https://artifacts.apis.io/assindo-com/eligibility/assindo-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Assindo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- PhoneAssistant
- Communications
- Software-as-a-Service
- Voice
---
