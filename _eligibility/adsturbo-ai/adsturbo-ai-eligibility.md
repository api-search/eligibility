---
api_specs:
- filename: adsturbo-ai-adclone-api-openapi.yml
  format: yaml
  label: AdsTurbo Ad Clone API
  slug: adsturbo-ai-adclone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-adclone-api-openapi.yml
- filename: adsturbo-ai-adclone-v2beta-api-openapi.yml
  format: yaml
  label: AdsTurbo AdClone (v2beta) API
  slug: adsturbo-ai-adclone-v2beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-adclone-v2beta-api-openapi.yml
- filename: adsturbo-ai-aiactor-api-openapi.yml
  format: yaml
  label: AdsTurbo AI Actor API
  slug: adsturbo-ai-aiactor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-aiactor-api-openapi.yml
- filename: adsturbo-ai-image-api-openapi.yml
  format: yaml
  label: AdsTurbo Image API
  slug: adsturbo-ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-image-api-openapi.yml
- filename: adsturbo-ai-image-v2beta-api-openapi.yml
  format: yaml
  label: AdsTurbo Image (v2beta) API
  slug: adsturbo-ai-image-v2beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-image-v2beta-api-openapi.yml
- filename: adsturbo-ai-persona-api-openapi.yml
  format: yaml
  label: AdsTurbo Persona API
  slug: adsturbo-ai-persona-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-persona-api-openapi.yml
- filename: adsturbo-ai-video-api-openapi.yml
  format: yaml
  label: AdsTurbo Video API
  slug: adsturbo-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-video-api-openapi.yml
- filename: adsturbo-ai-video-v2beta-api-openapi.yml
  format: yaml
  label: AdsTurbo Video (v2beta) API
  slug: adsturbo-ai-video-v2beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-video-v2beta-api-openapi.yml
- filename: adsturbo-ai-work-api-openapi.yml
  format: yaml
  label: AdsTurbo Work API
  slug: adsturbo-ai-work-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-work-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use AdsTurbo.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use AdsTurbo.
    value: '18'
  restricted_uses:
  - summary: Non-consensual deepfakes
    text: Create content that impersonates any individual, celebrity, or public figure without their explicit, written consent.
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
name: AdsTurbo
provenance_date: '2026-11-09'
provider_name: AdsTurbo
provider_slug: adsturbo-ai
slug: adsturbo-ai-eligibility
source_date: '2026-11-09'
source_filename: adsturbo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://adsturbo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdsTurbo\naid: adsturbo-ai\nurl: https://adsturbo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use AdsTurbo.\nrestricted_uses:\n- summary: Non-consensual deepfakes\n  text: Create content that impersonates any individual, celebrity, or public figure without their explicit, written\n    consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at\
  \ least 18 years old (or the age of majority in your jurisdiction) to use AdsTurbo.\n"
source_yaml_url: https://artifacts.apis.io/adsturbo-ai/eligibility/adsturbo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AdsTurbo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Ads
- E-Commerce
- Marketing
- Automation
---
