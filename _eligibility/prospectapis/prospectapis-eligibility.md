---
api_specs:
- filename: prospectapis-pricing-api-openapi.yml
  format: yaml
  label: ProspectAPIs Pricing API
  slug: prospectapis-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-pricing-api-openapi.yml
- filename: prospectapis-watchlists-api-openapi.yml
  format: yaml
  label: ProspectAPIs Watchlists API
  slug: prospectapis-watchlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-watchlists-api-openapi.yml
- filename: prospectapis-account-api-openapi.yml
  format: yaml
  label: ProspectAPIs Account API
  slug: prospectapis-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-account-api-openapi.yml
- filename: prospectapis-account-insights-api-openapi.yml
  format: yaml
  label: ProspectAPIs Account insights API
  slug: prospectapis-account-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-account-insights-api-openapi.yml
- filename: prospectapis-ads-api-openapi.yml
  format: yaml
  label: ProspectAPIs Ads API
  slug: prospectapis-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-ads-api-openapi.yml
- filename: prospectapis-companies-api-openapi.yml
  format: yaml
  label: ProspectAPIs Companies API
  slug: prospectapis-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-companies-api-openapi.yml
- filename: prospectapis-connected-account-api-openapi.yml
  format: yaml
  label: ProspectAPIs Connected account API
  slug: prospectapis-connected-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-connected-account-api-openapi.yml
- filename: prospectapis-email-verification-api-openapi.yml
  format: yaml
  label: ProspectAPIs Email verification API
  slug: prospectapis-email-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-email-verification-api-openapi.yml
- filename: prospectapis-events-api-openapi.yml
  format: yaml
  label: ProspectAPIs Events API
  slug: prospectapis-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-events-api-openapi.yml
- filename: prospectapis-funding-api-openapi.yml
  format: yaml
  label: ProspectAPIs Funding API
  slug: prospectapis-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-funding-api-openapi.yml
- filename: prospectapis-health-api-openapi.yml
  format: yaml
  label: ProspectAPIs Health API
  slug: prospectapis-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-health-api-openapi.yml
- filename: prospectapis-launches-api-openapi.yml
  format: yaml
  label: ProspectAPIs Launches API
  slug: prospectapis-launches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-launches-api-openapi.yml
- filename: prospectapis-messaging-reads-api-openapi.yml
  format: yaml
  label: ProspectAPIs Messaging reads API
  slug: prospectapis-messaging-reads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-messaging-reads-api-openapi.yml
- filename: prospectapis-meta-api-openapi.yml
  format: yaml
  label: ProspectAPIs Meta API
  slug: prospectapis-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-meta-api-openapi.yml
- filename: prospectapis-people-reads-api-openapi.yml
  format: yaml
  label: ProspectAPIs People reads API
  slug: prospectapis-people-reads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-people-reads-api-openapi.yml
- filename: prospectapis-people-writes-api-openapi.yml
  format: yaml
  label: ProspectAPIs People writes API
  slug: prospectapis-people-writes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-people-writes-api-openapi.yml
- filename: prospectapis-prospectapis-api-api-openapi.yml
  format: yaml
  label: ProspectAPIs ProspectAPIs API
  slug: prospectapis-prospectapis-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-prospectapis-api-api-openapi.yml
- filename: prospectapis-research-api-openapi.yml
  format: yaml
  label: ProspectAPIs Research API
  slug: prospectapis-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prospectapis/openapi/prospectapis-research-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service for a company, you agree for that company and confirm you may do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not sole basis for legal decisions
    text: do not use the service as the only basis for a decision with legal or similar effect on a person.
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
name: ProspectAPIs
provenance_date: '2026-11-10'
provider_name: ProspectAPIs
provider_slug: prospectapis
slug: prospectapis-eligibility
source_date: '2026-11-10'
source_filename: prospectapis-eligibility.yml
source_heading: Eligibility
source_page: https://prospectapis.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ProspectAPIs\naid: prospectapis\nurl: https://prospectapis.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service for a company, you agree for that company and confirm you may do so.\nrestricted_uses:\n- summary: Not sole basis for legal decisions\n  text: do not use the service as the only basis for a decision with legal or similar effect on a person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prospectapis/eligibility/prospectapis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ProspectAPIs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Funding
- Research
- Data
- Funding Data
- Prospect Research
- Email Verification
- LinkedIn data
- Watchlist
- MCP
---
