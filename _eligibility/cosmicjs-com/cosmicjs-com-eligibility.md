---
api_specs:
- filename: cosmicjs-com-blocks-api-openapi.yml
  format: yaml
  label: Cosmic Blocks API
  slug: cosmicjs-com-blocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmicjs-com/openapi/cosmicjs-com-blocks-api-openapi.yml
- filename: cosmicjs-com-media-api-openapi.yml
  format: yaml
  label: Cosmic Media API
  slug: cosmicjs-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmicjs-com/openapi/cosmicjs-com-media-api-openapi.yml
- filename: cosmicjs-com-object-revisions-api-openapi.yml
  format: yaml
  label: Cosmic Object revisions API
  slug: cosmicjs-com-object-revisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmicjs-com/openapi/cosmicjs-com-object-revisions-api-openapi.yml
- filename: cosmicjs-com-object-types-api-openapi.yml
  format: yaml
  label: Cosmic Object types API
  slug: cosmicjs-com-object-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmicjs-com/openapi/cosmicjs-com-object-types-api-openapi.yml
- filename: cosmicjs-com-objects-api-openapi.yml
  format: yaml
  label: Cosmic Objects API
  slug: cosmicjs-com-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmicjs-com/openapi/cosmicjs-com-objects-api-openapi.yml
- filename: cosmicjs-com-status-api-openapi.yml
  format: yaml
  label: Cosmic Status API
  slug: cosmicjs-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmicjs-com/openapi/cosmicjs-com-status-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be 18 years or older to register.
    type: individual
  - text: If you are agreeing to these Terms of Use on behalf of someone else (your employer for example), then you are warranting to us that you have full legal authority to bind that third party.
    type: business
  minimum_age:
    text: You need to be 18 years or older to register.
    value: '18'
  restricted_uses:
  - summary: Export law violations
    text: violate U.S. export laws, including, without limitation, violations of the Export Administration Act and the Export Administration Regulations administered by the Department of Commerce
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to publish your Site, you will have to become a registered user.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cosmic
provenance_date: '2026-11-09'
provider_name: Cosmic
provider_slug: cosmicjs-com
slug: cosmicjs-com-eligibility
source_date: '2026-11-09'
source_filename: cosmicjs-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.cosmicjs.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cosmic\naid: cosmicjs-com\nurl: https://www.cosmicjs.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be 18 years or older to register.\n- type: business\n  text: If you are agreeing to these Terms of Use on behalf of someone else (your employer for example), then you\n    are warranting to us that you have full legal authority to bind that third party.\nrestricted_uses:\n- summary: Export law violations\n  text: violate U.S. export laws, including, without limitation, violations of the Export Administration\
  \ Act and\n    the Export Administration Regulations administered by the Department of Commerce\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to publish your Site, you will have to become a registered user.\nminimum_age:\n  value: '18'\n  text: You need to be 18 years or older to register.\n"
source_yaml_url: https://artifacts.apis.io/cosmicjs-com/eligibility/cosmicjs-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Cosmic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Headless CMS
- Content Management
- Content API
- AI Agents
- MCP
- Webhooks
- JAMstack
---
