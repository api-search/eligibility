---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Registered Users must not be a person barred from using Rylo Properties under the laws of the United States, the Registered User's place of residence or any other applicable jurisdiction.
  entity_types:
  - text: for your personal or internal business purposes
    type: business
  minimum_age:
    text: YOU ARE AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Free captioned calls limited to users with disability
    text: you will not allow others who do not have a hearing or speech disability to utilize the Services to make or receive calls through the App or Website
  - summary: No commercial advertising or solicitation
    text: Use Rylo Properties or any part thereof for any commercial purpose
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
name: Rylo
provenance_date: '2026-11-10'
provider_name: Rylo
provider_slug: rylo
slug: rylo-eligibility
source_date: '2026-11-10'
source_filename: rylo-eligibility.yml
source_heading: Eligibility
source_page: https://rylo.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rylo\naid: rylo\nurl: https://rylo.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Registered Users must not be a person barred from using Rylo Properties under the laws of the United States,\n    the Registered User's place of residence or any other applicable jurisdiction.\nentity_types:\n- type: business\n  text: for your personal or internal business purposes\nrestricted_uses:\n- summary: Free captioned calls limited to users with disability\n  text: you will not allow others who do not have a hearing or speech disability to utilize the Services\
  \ to make\n    or receive calls through the App or Website\n- summary: No commercial advertising or solicitation\n  text: Use Rylo Properties or any part thereof for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you are required to complete a self-certification of your eligibility in the form and manner set forth by\n    the FCC\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/rylo/eligibility/rylo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Rylo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Accessibility
- Captioning
- Transcription
- Communications
- Deaf and Hard of Hearing
- Mobile App
---
