---
api_specs:
- filename: plunk-campaigns-api-openapi.yml
  format: yaml
  label: Plunk Campaigns API
  slug: plunk-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-campaigns-api-openapi.yml
- filename: plunk-contacts-api-openapi.yml
  format: yaml
  label: Plunk Contacts API
  slug: plunk-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-contacts-api-openapi.yml
- filename: plunk-events-api-openapi.yml
  format: yaml
  label: Plunk Events API
  slug: plunk-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-events-api-openapi.yml
- filename: plunk-transactional-api-openapi.yml
  format: yaml
  label: Plunk Transactional API
  slug: plunk-transactional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-transactional-api-openapi.yml
- filename: plunk-public-api-api-openapi.yml
  format: yaml
  label: Plunk Public API
  slug: plunk-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-public-api-api-openapi.yml
- filename: plunk-segments-api-openapi.yml
  format: yaml
  label: Plunk Segments API
  slug: plunk-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-segments-api-openapi.yml
- filename: plunk-templates-api-openapi.yml
  format: yaml
  label: Plunk Templates API
  slug: plunk-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to use Plunk.
    value: '16'
  restricted_uses:
  - summary: Illegal or adult content
    text: No illegal pornography or adult content
  - summary: Hate speech
    text: No hate speech or discriminatory content
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
name: Plunk
provenance_date: '2026-11-10'
provider_name: Plunk
provider_slug: plunk
slug: plunk-eligibility
source_date: '2026-11-10'
source_filename: plunk-eligibility.yml
source_heading: Eligibility
source_page: https://www.useplunk.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plunk\naid: plunk\nurl: https://www.useplunk.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or adult content\n  text: No illegal pornography or adult content\n- summary: Hate speech\n  text: No hate speech or discriminatory content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use Plunk.\n"
source_yaml_url: https://artifacts.apis.io/plunk/eligibility/plunk-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Plunk's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Transactional Email
- Marketing
- Automation
- Open Source
- Software-as-a-Service
- Email API
- Webhook
- Segmentation
- Workflow Automation
- Self-Hosted
- Developer Tools
---
