---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: be resident in a country where the Service is available
  entity_types:
  - text: even if you are using our Service on behalf of a company, in which case you are entering into these Terms on behalf of such company and represent that you have the authority to do this
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unacceptable use
    text: You must not use the Service for any purpose which we consider to be unacceptable.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We may refuse to register your account without giving reasons and without liability to you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jaxsta
provenance_date: '2026-11-09'
provider_name: Jaxsta
provider_slug: jaxsta
slug: jaxsta-eligibility
source_date: '2026-11-09'
source_filename: jaxsta-eligibility.yml
source_heading: Eligibility
source_page: https://jaxsta.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jaxsta\naid: jaxsta\nurl: https://jaxsta.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: be resident in a country where the Service is available\nentity_types:\n- type: business\n  text: even if you are using our Service on behalf of a company, in which case you are entering into these Terms\n    on behalf of such company and represent that you have the authority to do this\nrestricted_uses:\n- summary: Unacceptable use\n  text: You must not use the Service for any purpose which we consider to be unacceptable.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ false\n  text: We may refuse to register your account without giving reasons and without liability to you.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jaxsta/eligibility/jaxsta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Jaxsta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Data
- Platform
---
