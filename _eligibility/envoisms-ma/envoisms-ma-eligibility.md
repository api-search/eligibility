---
api_specs:
- filename: envoisms-ma-api-openapi.json
  format: json
  label: EnvoiSMS API API
  slug: envoisms-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/envoisms-ma/openapi/_original/envoisms-ma-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited message content
    text: 'Strictly prohibited are : fraudulent content, disinformation, phishing/smishing messages, incitement to hatred, non-consented spam, bank or institutional brand impersonation, or any content harming a third party.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For the activation of a custom Sender ID, the customer must provide the required supporting documents (RC, ICE) in accordance with the regulations applicable to commercial communications.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: envoisms-ma
provenance_date: '2026-11-09'
provider_name: envoisms-ma
provider_slug: envoisms-ma
slug: envoisms-ma-eligibility
source_date: '2026-11-09'
source_filename: envoisms-ma-eligibility.yml
source_heading: Eligibility
source_page: https://envoisms.ma/en/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: envoisms-ma\naid: envoisms-ma\nurl: https://envoisms.ma/en/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited message content\n  text: 'Strictly prohibited are : fraudulent content, disinformation, phishing/smishing messages, incitement to\n    hatred, non-consented spam, bank or institutional brand impersonation, or any content harming a third party.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: For the activation of a custom Sender ID, the customer must provide the required\
  \ supporting documents (RC,\n    ICE) in accordance with the regulations applicable to commercial communications.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/envoisms-ma/eligibility/envoisms-ma-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from envoisms-ma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- WhatsApp
- Messaging
- Morocco
- CPaaS
---
