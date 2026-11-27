---
api_specs:
- filename: deepdub-dubbing-api-openapi.yml
  format: yaml
  label: Deepdub Dubbing API
  slug: deepdub-dubbing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-dubbing-api-openapi.yml
- filename: deepdub-gender-detection-api-openapi.yml
  format: yaml
  label: Deepdub Gender Detection API
  slug: deepdub-gender-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-gender-detection-api-openapi.yml
- filename: deepdub-infrastructure-api-openapi.yml
  format: yaml
  label: Deepdub Infrastructure API
  slug: deepdub-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-infrastructure-api-openapi.yml
- filename: deepdub-issues-api-openapi.yml
  format: yaml
  label: Deepdub Issues API
  slug: deepdub-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-issues-api-openapi.yml
- filename: deepdub-tts-api-openapi.yml
  format: yaml
  label: Deepdub TTS API
  slug: deepdub-tts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-tts-api-openapi.yml
- filename: deepdub-usage-api-openapi.yml
  format: yaml
  label: Deepdub Usage API
  slug: deepdub-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-usage-api-openapi.yml
- filename: deepdub-voice-api-openapi.yml
  format: yaml
  label: Deepdub Voice API
  slug: deepdub-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-voice-api-openapi.yml
- filename: deepdub-provenance-api-openapi.yml
  format: yaml
  label: Deepdub Provenance API
  slug: deepdub-provenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-provenance-api-openapi.yml
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
  - summary: Illegal use or jurisdictions where use is illegal
    text: make use of the Website in any jurisdiction where same are illegal or which would subject Deepdub or its affiliates to any registration requirement within such jurisdiction or country
  - summary: Illegal, harmful or offensive use
    text: use, or encourage, promote, facilitate or instruct others to use the Website for any illegal, harmful or offensive use
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
name: Deepdub
provenance_date: '2026-11-09'
provider_name: Deepdub
provider_slug: deepdub
slug: deepdub-eligibility
source_date: '2026-11-09'
source_filename: deepdub-eligibility.yml
source_heading: Eligibility
source_page: https://deepdub.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deepdub\naid: deepdub\nurl: https://deepdub.ai/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal use or jurisdictions where use is illegal\n  text: make use of the Website in any jurisdiction where same are illegal or which would subject Deepdub or its\n    affiliates to any registration requirement within such jurisdiction or country\n- summary: Illegal, harmful or offensive use\n  text: use, or encourage, promote, facilitate or instruct others to use the Website for any illegal, harmful or\n    offensive\
  \ use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deepdub/eligibility/deepdub-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Deepdub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice
- Text-to-Speech
- Dubbing
- Localization
- Speech Synthesis
- Voice Cloning
- Media
- Artificial Intelligence
- Audio
---
