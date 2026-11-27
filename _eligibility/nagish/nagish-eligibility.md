---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not a person barred from using Rylo Properties under the laws of the United States
  entity_types:
  - text: THE TERM "YOU" REFERS TO THE INDIVIDUAL, AS APPLICABLE, USING THE SERVICES OR IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE APP OR WEBSITE.
    type: individual
  minimum_age:
    text: You represent that the Registered User is (a) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: Use Rylo Properties or any part thereof for any commercial purpose
  - summary: Free captioned service limited to users with disability
    text: you will not allow others who do not have a hearing or speech disability to utilize the Services to make or receive calls through the App or Website
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you are required to complete a self-certification of your eligibility in the form and manner set forth by the FCC
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nagish
provenance_date: '2026-11-10'
provider_name: Nagish
provider_slug: nagish
slug: nagish-eligibility
source_date: '2026-11-10'
source_filename: nagish-eligibility.yml
source_heading: Eligibility
source_page: https://rylo.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nagish\naid: nagish\nurl: https://rylo.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: not a person barred from using Rylo Properties under the laws of the United States\nentity_types:\n- type: individual\n  text: THE TERM \"YOU\" REFERS TO THE INDIVIDUAL, AS APPLICABLE, USING THE SERVICES OR IDENTIFIED AS THE USER WHEN\n    YOU REGISTERED ON THE APP OR WEBSITE.\nrestricted_uses:\n- summary: Commercial purposes\n  text: Use Rylo Properties or any part thereof for any commercial purpose\n- summary: Free captioned service limited to users with disability\n\
  \  text: you will not allow others who do not have a hearing or speech disability to utilize the Services to make\n    or receive calls through the App or Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you are required to complete a self-certification of your eligibility in the form and manner set forth by\n    the FCC\nminimum_age:\n  value: '18'\n  text: You represent that the Registered User is (a) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/nagish/eligibility/nagish-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Nagish's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Accessibility
- Captioning
- Transcription
- Telecommunications
- Deaf and Hard of Hearing
- Consumer App
---
