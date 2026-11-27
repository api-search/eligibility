---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms and Conditions apply exclusively to customers acting in the course of a professional activity.
    type: business
  - text: The Service is not offered to consumers.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No End User personal data via SDK
    text: The Customer undertakes not to transmit any personal data of End Users through the SDK, whether directly or through a Mapping File
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By signing the Order Form, or by confirming a subscription taken online under Article 3.7, the Customer represents that it acts in the course of its professional activity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kotzilla
provenance_date: '2026-11-09'
provider_name: Kotzilla
provider_slug: kotzilla
slug: kotzilla-eligibility
source_date: '2026-11-09'
source_filename: kotzilla-eligibility.yml
source_heading: Eligibility
source_page: https://kotzilla.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kotzilla\naid: kotzilla\nurl: https://kotzilla.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms and Conditions apply exclusively to customers acting in the course of a professional activity.\n- type: individual\n  text: The Service is not offered to consumers.\nrestricted_uses:\n- summary: No End User personal data via SDK\n  text: The Customer undertakes not to transmit any personal data of End Users through the SDK, whether directly\n    or through a Mapping File\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: By signing the Order Form, or by confirming a subscription taken online under Article 3.7, the Customer\n    represents that it acts in the course of its professional activity\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kotzilla/eligibility/kotzilla-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Kotzilla's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Data
- Observability
- Monitoring
- Developer Tools
- Kotlin
- Android
- Mobile
- Dependency Injection
- Performance
- MCP
- Agents
---
