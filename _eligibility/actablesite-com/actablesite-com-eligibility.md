---
api_specs:
- filename: actablesite-com-ai-crawler-check-api-openapi.yml
  format: yaml
  label: actablesite-com Ai Crawler Check API
  slug: actablesite-com-ai-crawler-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actablesite-com/openapi/actablesite-com-ai-crawler-check-api-openapi.yml
- filename: actablesite-com-audit-api-openapi.yml
  format: yaml
  label: actablesite-com Audit API
  slug: actablesite-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actablesite-com/openapi/actablesite-com-audit-api-openapi.yml
- filename: actablesite-com-health-api-openapi.yml
  format: yaml
  label: actablesite-com Health API
  slug: actablesite-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actablesite-com/openapi/actablesite-com-health-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No patient data or credentials
    text: must not place patient data, passwords, PECOS credentials, or private enrollment documents in the dashboard.
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
name: actablesite-com
provenance_date: '2026-11-09'
provider_name: actablesite-com
provider_slug: actablesite-com
slug: actablesite-com-eligibility
source_date: '2026-11-09'
source_filename: actablesite-com-eligibility.yml
source_heading: Eligibility
source_page: https://actablesite.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: actablesite-com\naid: actablesite-com\nurl: https://actablesite.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No patient data or credentials\n  text: must not place patient data, passwords, PECOS credentials, or private enrollment documents in the dashboard.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/actablesite-com/eligibility/actablesite-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from actablesite-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Platform
- Low-Code
- Analytics
- SEO
---
