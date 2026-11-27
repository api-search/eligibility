---
api_specs:
- filename: sarvam-pronunciationdictionary-api-openapi.yml
  format: yaml
  label: Sarvam Pronunciation Dictionary API
  slug: sarvam-pronunciationdictionary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-pronunciationdictionary-api-openapi.yml
- filename: sarvam-speechtotextjob-api-openapi.yml
  format: yaml
  label: Sarvam Speech To Text Job API
  slug: sarvam-speechtotextjob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-speechtotextjob-api-openapi.yml
- filename: sarvam-speechtotexttranslatejob-api-openapi.yml
  format: yaml
  label: Sarvam Speech To Text Translate Job API
  slug: sarvam-speechtotexttranslatejob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-speechtotexttranslatejob-api-openapi.yml
- filename: sarvam-text-api-openapi.yml
  format: yaml
  label: Sarvam Text API
  slug: sarvam-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-text-api-openapi.yml
- filename: sarvam-chat-completions-api-openapi.yml
  format: yaml
  label: Sarvam Chat Completions API
  slug: sarvam-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-chat-completions-api-openapi.yml
- filename: sarvam-document-intelligence-api-openapi.yml
  format: yaml
  label: Sarvam Document Intelligence API
  slug: sarvam-document-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-document-intelligence-api-openapi.yml
- filename: sarvam-speech-to-text-api-openapi.yml
  format: yaml
  label: Sarvam Speech To Text API
  slug: sarvam-speech-to-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-speech-to-text-api-openapi.yml
- filename: sarvam-text-to-speech-api-openapi.yml
  format: yaml
  label: Sarvam Text To Speech API
  slug: sarvam-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-text-to-speech-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Offerings may not be available in all countries, regions or languages, and access to certain features may be blocked in certain locations.
  minimum_age:
    text: If you are under the age of eighteen (18) years, you may access or use the Offerings only where verifiable consent has been provided by your parent or lawful guardian
    value: '18'
  restricted_uses:
  - summary: Lawful and responsible use; prohibited content and uses
    text: You must use the Offerings responsibly and lawfully and must not misuse them.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We are not obliged to verify the actual identity or authority of any user.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sarvam
provenance_date: '2026-11-10'
provider_name: Sarvam
provider_slug: sarvam
slug: sarvam-eligibility
source_date: '2026-11-10'
source_filename: sarvam-eligibility.yml
source_heading: Eligibility
source_page: https://www.sarvam.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sarvam\naid: sarvam\nurl: https://www.sarvam.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Offerings may not be available in all countries, regions or languages, and access to certain features\n    may be blocked in certain locations.\nentity_types: []\nrestricted_uses:\n- summary: Lawful and responsible use; prohibited content and uses\n  text: You must use the Offerings responsibly and lawfully and must not misuse them.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We are not obliged to verify the actual identity or authority\
  \ of any user.\nminimum_age:\n  value: '18'\n  text: If you are under the age of eighteen (18) years, you may access or use the Offerings only where verifiable\n    consent has been provided by your parent or lawful guardian\n"
source_yaml_url: https://artifacts.apis.io/sarvam/eligibility/sarvam-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sarvam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Speech-to-Text
- Text-to-Speech
- Translation
- LLM
- Document Intelligence
- Indian Languages
- Voice
- Real-Time
---
