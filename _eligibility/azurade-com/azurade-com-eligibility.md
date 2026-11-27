---
api_specs:
- filename: azurade-com-account-api-openapi.yml
  format: yaml
  label: Azurade AI Account API
  slug: azurade-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-account-api-openapi.yml
- filename: azurade-com-generations-api-openapi.yml
  format: yaml
  label: Azurade AI Generations API
  slug: azurade-com-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-generations-api-openapi.yml
- filename: azurade-com-models-api-openapi.yml
  format: yaml
  label: Azurade AI Models API
  slug: azurade-com-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-models-api-openapi.yml
- filename: azurade-com-prompts-api-openapi.yml
  format: yaml
  label: Azurade AI Prompts API
  slug: azurade-com-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-prompts-api-openapi.yml
- filename: azurade-com-uploads-api-openapi.yml
  format: yaml
  label: Azurade AI Uploads API
  slug: azurade-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-uploads-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to enter into a binding contract.
    type: individual
  - text: “You” means the individual or organisation that registers for or uses the Service. If you use it on behalf of an organisation, you confirm that you are authorised to bind it to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Prohibited content categories
    text: is pornographic, sexually explicit or sexually suggestive (NSFW content), including nudity
  - summary: Political or electoral disinformation
    text: or to create political or electoral disinformation.
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
name: Azurade AI
provenance_date: '2026-11-09'
provider_name: Azurade AI
provider_slug: azurade-com
slug: azurade-com-eligibility
source_date: '2026-11-09'
source_filename: azurade-com-eligibility.yml
source_heading: Eligibility
source_page: https://azurade.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azurade AI\naid: azurade-com\nurl: https://azurade.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter into a binding contract.\n- type: business\n  text: “You” means the individual or organisation that registers for or uses the Service. If you use it on behalf\n    of an organisation, you confirm that you are authorised to bind it to these Terms.\nrestricted_uses:\n- summary: Prohibited content categories\n  text: is pornographic, sexually explicit or sexually suggestive (NSFW\
  \ content), including nudity\n- summary: Political or electoral disinformation\n  text: or to create political or electoral disinformation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/azurade-com/eligibility/azurade-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Azurade AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Platform
- Creative
---
