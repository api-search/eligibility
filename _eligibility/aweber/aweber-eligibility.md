---
api_specs:
- filename: aweber-accounts-api-openapi.yml
  format: yaml
  label: AWeber Accounts API
  slug: aweber-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-accounts-api-openapi.yml
- filename: aweber-broadcasts-api-openapi.yml
  format: yaml
  label: AWeber Broadcasts API
  slug: aweber-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-broadcasts-api-openapi.yml
- filename: aweber-campaigns-api-openapi.yml
  format: yaml
  label: AWeber Campaigns API
  slug: aweber-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-campaigns-api-openapi.yml
- filename: aweber-custom-fields-api-openapi.yml
  format: yaml
  label: AWeber Custom Fields API
  slug: aweber-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-custom-fields-api-openapi.yml
- filename: aweber-landing-pages-api-openapi.yml
  format: yaml
  label: AWeber Landing Pages API
  slug: aweber-landing-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-landing-pages-api-openapi.yml
- filename: aweber-lists-api-openapi.yml
  format: yaml
  label: AWeber Lists API
  slug: aweber-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-lists-api-openapi.yml
- filename: aweber-segments-api-openapi.yml
  format: yaml
  label: AWeber Segments API
  slug: aweber-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-segments-api-openapi.yml
- filename: aweber-subscribers-api-openapi.yml
  format: yaml
  label: AWeber Subscribers API
  slug: aweber-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-subscribers-api-openapi.yml
- filename: aweber-integrations-api-openapi.yml
  format: yaml
  label: AWeber Integrations API
  slug: aweber-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-integrations-api-openapi.yml
- filename: aweber-beta-endpoints-api-openapi.yml
  format: yaml
  label: AWeber Beta Endpoints API
  slug: aweber-beta-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-beta-endpoints-api-openapi.yml
- filename: aweber-oauth-1-0a-reference-api-openapi.yml
  format: yaml
  label: AWeber OAuth 1.0a Reference API
  slug: aweber-oauth-1-0a-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-oauth-1-0a-reference-api-openapi.yml
- filename: aweber-oauth-2-0-reference-api-openapi.yml
  format: yaml
  label: AWeber OAuth 2.0 Reference API
  slug: aweber-oauth-2-0-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-oauth-2-0-reference-api-openapi.yml
- filename: aweber-webforms-api-openapi.yml
  format: yaml
  label: AWeber Webforms API
  slug: aweber-webforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aweber/openapi/aweber-webforms-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: No individual under the age of sixteen (16) may use the Services, provide any personal information to AWeber, or otherwise submit personal information through AWeber Services
    value: '16'
  restricted_uses:
  - summary: Pornography and sex-related merchandising
    text: Pornography and sex-related merchandising are prohibited on any AWeber server.
  - source: https://www.aweber.com/antispam.htm
    summary: Spamming or attempted spamming
    text: If we find that you are spamming, or trying to spam, with your AWeber account
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
name: AWeber
provenance_date: '2026-11-09'
provider_name: AWeber
provider_slug: aweber
slug: aweber-eligibility
source_date: '2026-11-09'
source_filename: aweber-eligibility.yml
source_heading: Eligibility
source_page: https://www.aweber.com/service-agreement.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AWeber\naid: aweber\nurl: https://www.aweber.com/service-agreement.htm\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.aweber.com/antispam.htm\n  - https://www.aweber.com/service-agreement.htm\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Pornography and sex-related merchandising\n  text: Pornography and sex-related merchandising are prohibited on any AWeber server.\n- summary: Spamming or attempted spamming\n  text: If we find that you are spamming, or trying to spam, with your AWeber account\n  source: https://www.aweber.com/antispam.htm\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: No individual under the age of sixteen (16) may use the Services, provide any personal information to AWeber,\n    or otherwise submit personal information through AWeber Services\n"
source_yaml_url: https://artifacts.apis.io/aweber/eligibility/aweber-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AWeber's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Marketing Automation
- Email
- Newsletters
- Subscribers
- Campaigns
- Landing Pages
- Web Forms
- Segments
- Webhook
- OAuth
- Small Business
- Authentication
---
