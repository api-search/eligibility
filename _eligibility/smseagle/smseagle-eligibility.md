---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: CONSUMER – a natural person entering into a legal transaction with an entrepreneur that is not directly related to that person’s business or professional activity.
    type: individual
  - text: (2) a legal person
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal content
    text: The Service Recipient is prohibited from supplying content of an unlawful nature, including Illegal Content within the meaning of the Digital Services Act.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: DEMO REGISTRATION – the act of completing the registration form available on the Demo page of the Website and verifying identity by means of an SMS code, enabling the Service Recipient to activate the Demo Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SMSEagle
provenance_date: '2026-11-10'
provider_name: SMSEagle
provider_slug: smseagle
slug: smseagle-eligibility
source_date: '2026-11-10'
source_filename: smseagle-eligibility.yml
source_heading: Eligibility
source_page: https://www.smseagle.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SMSEagle\naid: smseagle\nurl: https://www.smseagle.eu/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: CONSUMER – a natural person entering into a legal transaction with an entrepreneur that is not directly\n    related to that person’s business or professional activity.\n- type: business\n  text: (2) a legal person\nrestricted_uses:\n- summary: Illegal content\n  text: The Service Recipient is prohibited from supplying content of an unlawful nature, including Illegal Content\n    within the meaning of the Digital Services Act.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: DEMO REGISTRATION – the act of completing the registration form available on the Demo page of the Website\n    and verifying identity by means of an SMS code, enabling the Service Recipient to activate the Demo Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smseagle/eligibility/smseagle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from SMSEagle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Alerting
- IoT
- Critical-Systems
---
