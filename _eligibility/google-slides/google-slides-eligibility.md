---
api_specs:
- filename: google-slides-presentations-api-openapi.yml
  format: yaml
  label: Google Slides Presentations API
  slug: google-slides-presentations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-slides/openapi/google-slides-presentations-api-openapi.yml
claim_count: 10
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs if you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google
    type: individual
  - text: Unless prohibited by applicable law, if you are a business, you will defend and indemnify Google
    type: business
  - source: https://policies.google.com/terms
    text: If you’re under the age required to manage your own Google Account , you must have your parent or legal guardian’s permission to use a Google Account.
    type: individual
  - source: https://policies.google.com/terms
    text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: HIPAA
    text: If you are (or become) a "covered entity" or "business associate" as defined in HIPAA, you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  - source: https://policies.google.com/terms
    summary: Legal and sanctions compliance
    text: comply with applicable laws, including export control, sanctions, and human trafficking laws
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
name: Google Slides
provenance_date: '2026-11-09'
provider_name: Google Slides
provider_slug: google-slides
slug: google-slides-eligibility
source_date: '2026-11-09'
source_filename: google-slides-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Slides\naid: google-slides\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://developers.google.com/terms\n  - https://policies.google.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs if you are a person barred from using or receiving the APIs under the applicable\n    laws of the United States or other countries including the country in which you are resident or from which you\n    use the APIs.\nentity_types:\n- type: individual\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age\
  \ to form a binding\n    contract with Google\n- type: business\n  text: Unless prohibited by applicable law, if you are a business, you will defend and indemnify Google\n- type: individual\n  text: If you’re under the age required to manage your own Google Account , you must have your parent or legal\n    guardian’s permission to use a Google Account.\n  source: https://policies.google.com/terms\n- type: business\n  text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .\n  source: https://policies.google.com/terms\nrestricted_uses:\n- summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: HIPAA\n  text: If you are (or become)\
  \ a \"covered entity\" or \"business associate\" as defined in HIPAA, you will not use\n    the APIs for any purpose or in any manner involving transmitting protected health information to Google unless\n    you have received prior written consent to such use from Google.\n- summary: Legal and sanctions compliance\n  text: comply with applicable laws, including export control, sanctions, and human trafficking laws\n  source: https://policies.google.com/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-slides/eligibility/google-slides-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 10 quoted statements, read from Google Slides's own page on 2026-11-09.
synthetic: false
tags:
- Collaboration
- Google Workspace
- Presentations
- Productivity
- Slides
---
