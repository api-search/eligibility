---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (h) You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services and have gotten your parent or guardian to agree to these Terms on your behalf).
    value: null
  restricted_uses:
  - summary: Not for emergencies or medical advice
    text: THE SERVICES SHOULD NEVER BE USED AS A SUBSTITUTE FOR EMERGENCY CARE.
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
name: Alife
provenance_date: '2026-11-09'
provider_name: Alife
provider_slug: alife
slug: alife-eligibility
source_date: '2026-11-09'
source_filename: alife-eligibility.yml
source_heading: Eligibility
source_page: https://www.alifehealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alife\naid: alife\nurl: https://www.alifehealth.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (h) You represent and warrant that you are not located in a country subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\nrestricted_uses:\n- summary: Not for emergencies\
  \ or medical advice\n  text: THE SERVICES SHOULD NEVER BE USED AS A SUBSTITUTE FOR EMERGENCY CARE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services and have gotten your parent or guardian\n    to agree to these Terms on your behalf).\n"
source_yaml_url: https://artifacts.apis.io/alife/eligibility/alife-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alife's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Fertility
- IVF
- Reproductive Health
- Artificial Intelligence
- Machine Learning
- Clinical Decision Support
- Digital Health
---
