---
api_specs:
- filename: majr-app-audit-api-openapi.yml
  format: yaml
  label: majr-app Audit API
  slug: majr-app-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-audit-api-openapi.yml
- filename: majr-app-discovery-api-openapi.yml
  format: yaml
  label: majr-app Discovery API
  slug: majr-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-discovery-api-openapi.yml
- filename: majr-app-drafting-api-openapi.yml
  format: yaml
  label: majr-app Drafting API
  slug: majr-app-drafting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-drafting-api-openapi.yml
- filename: majr-app-encode-api-openapi.yml
  format: yaml
  label: majr-app Encode API
  slug: majr-app-encode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-encode-api-openapi.yml
- filename: majr-app-generation-api-openapi.yml
  format: yaml
  label: majr-app Generation API
  slug: majr-app-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-generation-api-openapi.yml
- filename: majr-app-healthz-api-openapi.yml
  format: yaml
  label: majr-app Healthz API
  slug: majr-app-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-healthz-api-openapi.yml
- filename: majr-app-jobs-api-openapi.yml
  format: yaml
  label: majr-app Jobs API
  slug: majr-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-jobs-api-openapi.yml
- filename: majr-app-uploads-api-openapi.yml
  format: yaml
  label: majr-app Uploads API
  slug: majr-app-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-uploads-api-openapi.yml
- filename: majr-app-usage-api-openapi.yml
  format: yaml
  label: majr-app Usage API
  slug: majr-app-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-usage-api-openapi.yml
- filename: majr-app-voice-api-openapi.yml
  format: yaml
  label: majr-app Voice API
  slug: majr-app-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-voice-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally able to enter a contract.
    type: individual
  - text: If you are agreeing on behalf of a company, you confirm you can bind it, and "you" means that company.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Generate or distribute material that sexually exploits children, incites violence, harasses a person, or is designed to defraud or deceive someone to their detriment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'During beta you get keys yourself: sign in at majr.app/keys with a one-time code sent to your email, name a product, and a key is created for it on the spot.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: majr-app
provenance_date: '2026-11-10'
provider_name: majr-app
provider_slug: majr-app
slug: majr-app-eligibility
source_date: '2026-11-10'
source_filename: majr-app-eligibility.yml
source_heading: Eligibility
source_page: https://majr.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: majr-app\naid: majr-app\nurl: https://majr.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter a contract.\n- type: business\n  text: If you are agreeing on behalf of a company, you confirm you can bind it, and \"you\" means that company.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Generate or distribute material that sexually exploits children, incites violence, harasses a person, or\n    is designed to defraud or deceive someone to their detriment.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'During beta you get keys yourself: sign in at majr.app/keys with a one-time code sent to your email, name\n    a product, and a key is created for it on the spot.'\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/majr-app/eligibility/majr-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from majr-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Media
- SEO
- Encoding
- Agent Services
---
