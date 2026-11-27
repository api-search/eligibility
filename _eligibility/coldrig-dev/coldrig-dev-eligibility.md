---
api_specs:
- filename: coldrig-dev-account-api-openapi.yml
  format: yaml
  label: Coldrig Account API
  slug: coldrig-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-account-api-openapi.yml
- filename: coldrig-dev-bootstrap-api-openapi.yml
  format: yaml
  label: Coldrig Bootstrap API
  slug: coldrig-dev-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-bootstrap-api-openapi.yml
- filename: coldrig-dev-byo-domains-api-openapi.yml
  format: yaml
  label: Coldrig Byo Domains API
  slug: coldrig-dev-byo-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-byo-domains-api-openapi.yml
- filename: coldrig-dev-campaigns-api-openapi.yml
  format: yaml
  label: Coldrig Campaigns API
  slug: coldrig-dev-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-campaigns-api-openapi.yml
- filename: coldrig-dev-compliance-api-openapi.yml
  format: yaml
  label: Coldrig Compliance API
  slug: coldrig-dev-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-compliance-api-openapi.yml
- filename: coldrig-dev-dashboard-api-openapi.yml
  format: yaml
  label: Coldrig Dashboard API
  slug: coldrig-dev-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-dashboard-api-openapi.yml
- filename: coldrig-dev-inbox-api-openapi.yml
  format: yaml
  label: Coldrig Inbox API
  slug: coldrig-dev-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-inbox-api-openapi.yml
- filename: coldrig-dev-infrastructure-api-openapi.yml
  format: yaml
  label: Coldrig Infrastructure API
  slug: coldrig-dev-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-infrastructure-api-openapi.yml
- filename: coldrig-dev-leads-api-openapi.yml
  format: yaml
  label: Coldrig Leads API
  slug: coldrig-dev-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-leads-api-openapi.yml
- filename: coldrig-dev-messages-api-openapi.yml
  format: yaml
  label: Coldrig Messages API
  slug: coldrig-dev-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-messages-api-openapi.yml
- filename: coldrig-dev-sandbox-api-openapi.yml
  format: yaml
  label: Coldrig Sandbox API
  slug: coldrig-dev-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-sandbox-api-openapi.yml
- filename: coldrig-dev-webhooks-api-openapi.yml
  format: yaml
  label: Coldrig Webhooks API
  slug: coldrig-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Prohibits sending from a jurisdiction subject to comprehensive U.S. sanctions; no specific countries named.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned or denied parties
    text: Sanctioned or denied parties — using the Service to contact, or on behalf of, any individual or entity on a U.S. Treasury OFAC sanctions list or other applicable denied-party list
  verification:
    approval_required: null
    kyb: null
    kyc: null
    source: https://coldrig.dev/terms
    text: EpiphanyMade then finishes authorizing each mailbox to send before real sending starts.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coldrig
provenance_date: '2026-11-09'
provider_name: Coldrig
provider_slug: coldrig-dev
slug: coldrig-dev-eligibility
source_date: '2026-11-09'
source_filename: coldrig-dev-eligibility.yml
source_heading: Eligibility
source_page: https://coldrig.dev/aup
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coldrig\naid: coldrig-dev\nurl: https://coldrig.dev/aup\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://coldrig.dev/aup\n  - https://coldrig.dev/terms\ncountries:\n  served: []\n  excluded: []\n  text: Prohibits sending from a jurisdiction subject to comprehensive U.S. sanctions; no specific countries named.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned or denied parties\n  text: Sanctioned or denied parties — using the Service to contact, or on behalf of, any individual or entity on\n    a U.S. Treasury OFAC sanctions list or other applicable denied-party list\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: EpiphanyMade then finishes authorizing each mailbox to send before real sending starts.\n  source: https://coldrig.dev/terms\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coldrig-dev/eligibility/coldrig-dev-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Coldrig's own page on 2026-11-09.
synthetic: false
tags:
- Cold Email
- Outreach
- AI Agents
- Email Infrastructure
---
