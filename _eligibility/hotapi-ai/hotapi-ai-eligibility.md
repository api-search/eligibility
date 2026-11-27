---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We restrict access from some jurisdictions, listed in the Acceptable Use Policy
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a contract to use the Service.
    type: individual
  - text: The Service is provided to businesses and developers for commercial use.
    type: business
  - text: The Service is provided to businesses and developers for commercial use.
    type: developer
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not a consumer content product
    text: It is not a consumer content product and we do not offer one.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The dashboard asks an owner or admin to confirm the age condition separately, and to accept these Terms and the Acceptable Use Policy on behalf of the organization.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: hotapi-ai
provenance_date: '2026-11-09'
provider_name: hotapi-ai
provider_slug: hotapi-ai
slug: hotapi-ai-eligibility
source_date: '2026-11-09'
source_filename: hotapi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://hotapi.ai/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hotapi-ai\naid: hotapi-ai\nurl: https://hotapi.ai/en/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We restrict access from some jurisdictions, listed in the Acceptable Use Policy\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Service.\n- type: business\n  text: The Service is provided to businesses and developers for commercial use.\n- type: developer\n  text: The Service is provided to businesses and developers for commercial use.\nrestricted_uses:\n- summary: Not a consumer content\
  \ product\n  text: It is not a consumer content product and we do not offer one.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The dashboard asks an owner or admin to confirm the age condition separately, and to accept these Terms\n    and the Acceptable Use Policy on behalf of the organization.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/hotapi-ai/eligibility/hotapi-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from hotapi-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- NSFW
- Chat
- Image Generation
- Video Generation
- Voice Generation
---
