---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Rapchat makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: You may use the Services only if you are over eighteen (18) years of age and can form a binding contract with Rapchat or are using the Services under the direct direction of a parent or guardian
    type: individual
  - text: If you are accepting these Terms and using the Services on behalf of a company, organization, government, or other legal entity, you represent and warrant that you are authorized to do so.
    type: business
  minimum_age:
    text: You may use the Services only if you are over eighteen (18) years of age and can form a binding contract with Rapchat or are using the Services under the direct direction of a parent or guardian that can accept these terms on your behalf. No user under thirteen (13) years of age may use the Services for any reason.
    value: '18'
  restricted_uses:
  - summary: Commercial uses requiring approval
    text: 'You agree not to use the Service for any of the following uses unless you obtain Rapchat''s prior written approval: the sale of access to the Service;'
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
name: Rapchat
provenance_date: '2026-11-10'
provider_name: Rapchat
provider_slug: rapchat
slug: rapchat-eligibility
source_date: '2026-11-10'
source_filename: rapchat-eligibility.yml
source_heading: Eligibility
source_page: https://rapchat.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rapchat\naid: rapchat\nurl: https://rapchat.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Rapchat makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You may use the Services only if you are over eighteen (18) years of age and can form a binding contract\n    with Rapchat or are using the Services under the direct direction of a parent or guardian\n- type: business\n  text: If you are accepting these Terms and using the Services on behalf of a company, organization, government,\n\
  \    or other legal entity, you represent and warrant that you are authorized to do so.\nrestricted_uses:\n- summary: Commercial uses requiring approval\n  text: 'You agree not to use the Service for any of the following uses unless you obtain Rapchat''s prior written\n    approval: the sale of access to the Service;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are over eighteen (18) years of age and can form a binding contract\n    with Rapchat or are using the Services under the direct direction of a parent or guardian that can accept these\n    terms on your behalf. No user under thirteen (13) years of age may use the Services for any reason.\n"
source_yaml_url: https://artifacts.apis.io/rapchat/eligibility/rapchat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Rapchat's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Music Creation
- Audio
- Beats
- Recording
- Consumer App
- Mobile App
- Creator Tools
---
