---
api_specs:
- filename: shipstar-ai-authentication-api-openapi.yml
  format: yaml
  label: shipstar-ai Authentication API
  slug: shipstar-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-authentication-api-openapi.yml
- filename: shipstar-ai-banner-api-openapi.yml
  format: yaml
  label: shipstar-ai Banner API
  slug: shipstar-ai-banner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-banner-api-openapi.yml
- filename: shipstar-ai-blog-api-openapi.yml
  format: yaml
  label: shipstar-ai Blog API
  slug: shipstar-ai-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-blog-api-openapi.yml
- filename: shipstar-ai-changelog-api-openapi.yml
  format: yaml
  label: shipstar-ai Changelog API
  slug: shipstar-ai-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-changelog-api-openapi.yml
- filename: shipstar-ai-changelog-subscriptions-api-openapi.yml
  format: yaml
  label: shipstar-ai Changelog Subscriptions API
  slug: shipstar-ai-changelog-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-changelog-subscriptions-api-openapi.yml
- filename: shipstar-ai-health-api-openapi.yml
  format: yaml
  label: shipstar-ai Health API
  slug: shipstar-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-health-api-openapi.yml
- filename: shipstar-ai-kb-api-openapi.yml
  format: yaml
  label: shipstar-ai Kb API
  slug: shipstar-ai-kb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-kb-api-openapi.yml
- filename: shipstar-ai-mailing-lists-api-openapi.yml
  format: yaml
  label: shipstar-ai Mailing Lists API
  slug: shipstar-ai-mailing-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-mailing-lists-api-openapi.yml
- filename: shipstar-ai-team-invitations-api-openapi.yml
  format: yaml
  label: shipstar-ai Team Invitations API
  slug: shipstar-ai-team-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-team-invitations-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other organization, you agree to these Terms for it and confirm you have authority to do so
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: US sanctions and sanctioned persons
    text: use the Service if you are subject to US sanctions, or for a sanctioned person or country
  - summary: Special categories or children's personal data
    text: send us special categories of personal data, or personal data of children
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
name: shipstar-ai
provenance_date: '2026-11-10'
provider_name: shipstar-ai
provider_slug: shipstar-ai
slug: shipstar-ai-eligibility
source_date: '2026-11-10'
source_filename: shipstar-ai-eligibility.yml
source_heading: Eligibility
source_page: https://shipstar.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: shipstar-ai\naid: shipstar-ai\nurl: https://shipstar.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you agree to these Terms for it and\n    confirm you have authority to do so\nrestricted_uses:\n- summary: US sanctions and sanctioned persons\n  text: use the Service if you are subject to US sanctions, or for a sanctioned person or country\n- summary: Special categories or children's personal data\n  text: send us special categories of personal data, or personal\
  \ data of children\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/shipstar-ai/eligibility/shipstar-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from shipstar-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Developer Tools
- Automation
- Open Source
---
