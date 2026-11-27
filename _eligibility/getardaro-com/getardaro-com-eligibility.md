---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms of Service are a binding agreement between the business or other organization accepting them, including its authorized users
    type: business
  - text: you agree to these Terms and represent that you are at least 18 years old and authorized to bind Customer.
    type: individual
  minimum_age:
    text: you are at least 18 years old and authorized to bind Customer
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: A workspace request is an application for service. It is not an acceptance by Ardaro, does not guarantee activation, and does not by itself create a paid subscription or charge.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: getardaro-com
provenance_date: '2026-11-09'
provider_name: getardaro-com
provider_slug: getardaro-com
slug: getardaro-com-eligibility
source_date: '2026-11-09'
source_filename: getardaro-com-eligibility.yml
source_heading: Eligibility
source_page: https://getardaro.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: getardaro-com\naid: getardaro-com\nurl: https://getardaro.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms of Service are a binding agreement between the business or other organization accepting them,\n    including its authorized users\n- type: individual\n  text: you agree to these Terms and represent that you are at least 18 years old and authorized to bind Customer.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: A workspace request is an application for\
  \ service. It is not an acceptance by Ardaro, does not guarantee\n    activation, and does not by itself create a paid subscription or charge.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old and authorized to bind Customer\n"
source_yaml_url: https://artifacts.apis.io/getardaro-com/eligibility/getardaro-com-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from getardaro-com's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Software
- Contractors
- Field Management
- Voice Notes
---
