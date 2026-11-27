---
api_specs:
- filename: bundle-social-analytics-api-openapi.yml
  format: yaml
  label: bundle.social Analytics API
  slug: bundle-social-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-analytics-api-openapi.yml
- filename: bundle-social-app-api-openapi.yml
  format: yaml
  label: bundle.social App API
  slug: bundle-social-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-app-api-openapi.yml
- filename: bundle-social-automation-api-openapi.yml
  format: yaml
  label: bundle.social Automation API
  slug: bundle-social-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-automation-api-openapi.yml
- filename: bundle-social-comment-api-openapi.yml
  format: yaml
  label: bundle.social Comment API
  slug: bundle-social-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-comment-api-openapi.yml
- filename: bundle-social-conversation-api-openapi.yml
  format: yaml
  label: bundle.social Conversation API
  slug: bundle-social-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-conversation-api-openapi.yml
- filename: bundle-social-credit-api-openapi.yml
  format: yaml
  label: bundle.social Credit API
  slug: bundle-social-credit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-credit-api-openapi.yml
- filename: bundle-social-misc-api-openapi.yml
  format: yaml
  label: bundle.social Misc API
  slug: bundle-social-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-misc-api-openapi.yml
- filename: bundle-social-organization-api-openapi.yml
  format: yaml
  label: bundle.social Organization API
  slug: bundle-social-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-organization-api-openapi.yml
- filename: bundle-social-post-api-openapi.yml
  format: yaml
  label: bundle.social Post API
  slug: bundle-social-post-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-post-api-openapi.yml
- filename: bundle-social-postcsv-api-openapi.yml
  format: yaml
  label: bundle.social Post CSV API
  slug: bundle-social-postcsv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-postcsv-api-openapi.yml
- filename: bundle-social-postimport-api-openapi.yml
  format: yaml
  label: bundle.social Post Import API
  slug: bundle-social-postimport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-postimport-api-openapi.yml
- filename: bundle-social-socialaccount-api-openapi.yml
  format: yaml
  label: bundle.social Social Account API
  slug: bundle-social-socialaccount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-socialaccount-api-openapi.yml
- filename: bundle-social-team-api-openapi.yml
  format: yaml
  label: bundle.social Team API
  slug: bundle-social-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-team-api-openapi.yml
- filename: bundle-social-upload-api-openapi.yml
  format: yaml
  label: bundle.social Upload API
  slug: bundle-social-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bundle-social/openapi/bundle-social-upload-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other legal entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding agreement to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited content categories
    text: child sexual abuse material (CSAM), child sexual exploitation, grooming, and any content that sexualizes, endangers, or exploits minors
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
name: bundle.social
provenance_date: '2026-11-09'
provider_name: bundle.social
provider_slug: bundle-social
slug: bundle-social-eligibility
source_date: '2026-11-09'
source_filename: bundle-social-eligibility.yml
source_heading: Eligibility
source_page: https://bundle.social/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bundle.social\naid: bundle-social\nurl: https://bundle.social/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity.\nrestricted_uses:\n- summary: Prohibited content categories\n  text: child sexual abuse material (CSAM), child sexual exploitation, grooming, and any content that sexualizes,\n    endangers, or exploits minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding agreement to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bundle-social/eligibility/bundle-social-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from bundle.social's own page on 2026-11-09.
synthetic: false
tags:
- Social
- Media
- Integration
- Unlimited
- Automation
---
