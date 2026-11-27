---
api_specs:
- filename: videogen-io-account-api-openapi.yml
  format: yaml
  label: VideoGen Account API
  slug: videogen-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-account-api-openapi.yml
- filename: videogen-io-assistant-api-openapi.yml
  format: yaml
  label: VideoGen Assistant API
  slug: videogen-io-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-assistant-api-openapi.yml
- filename: videogen-io-entities-api-openapi.yml
  format: yaml
  label: VideoGen Entities API
  slug: videogen-io-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-entities-api-openapi.yml
- filename: videogen-io-files-api-openapi.yml
  format: yaml
  label: VideoGen Files API
  slug: videogen-io-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-files-api-openapi.yml
- filename: videogen-io-projects-api-openapi.yml
  format: yaml
  label: VideoGen Projects API
  slug: videogen-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-projects-api-openapi.yml
- filename: videogen-io-resources-api-openapi.yml
  format: yaml
  label: VideoGen Resources API
  slug: videogen-io-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-resources-api-openapi.yml
- filename: videogen-io-text-api-openapi.yml
  format: yaml
  label: VideoGen Text API
  slug: videogen-io-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-text-api-openapi.yml
- filename: videogen-io-tools-api-openapi.yml
  format: yaml
  label: VideoGen Tools API
  slug: videogen-io-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-tools-api-openapi.yml
- filename: videogen-io-webhook-events-api-openapi.yml
  format: yaml
  label: VideoGen Webhook events API
  slug: videogen-io-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-webhook-events-api-openapi.yml
- filename: videogen-io-webhooks-api-openapi.yml
  format: yaml
  label: VideoGen Webhooks API
  slug: videogen-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-webhooks-api-openapi.yml
- filename: videogen-io-workflows-api-openapi.yml
  format: yaml
  label: VideoGen Workflows API
  slug: videogen-io-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/videogen-io/openapi/videogen-io-workflows-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Industry-regulated data (HIPAA, FISMA)
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA-regulated use
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VideoGen
provenance_date: '2026-11-10'
provider_name: VideoGen
provider_slug: videogen-io
slug: videogen-io-eligibility
source_date: '2026-11-10'
source_filename: videogen-io-eligibility.yml
source_heading: Eligibility
source_page: https://videogen.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VideoGen\naid: videogen-io\nurl: https://videogen.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Industry-regulated data (HIPAA, FISMA)\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security\
  \ Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA-regulated use\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/videogen-io/eligibility/videogen-io-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from VideoGen's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Automation
- Platform
---
