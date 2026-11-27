---
api_specs:
- filename: chadwin-companies-api-openapi.yml
  format: yaml
  label: Chadwin Companies API
  slug: chadwin-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-companies-api-openapi.yml
- filename: chadwin-company-kpis-api-openapi.yml
  format: yaml
  label: Chadwin Company KPIs API
  slug: chadwin-company-kpis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-company-kpis-api-openapi.yml
- filename: chadwin-company-reports-api-openapi.yml
  format: yaml
  label: Chadwin Company reports API
  slug: chadwin-company-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-company-reports-api-openapi.yml
- filename: chadwin-current-reports-api-openapi.yml
  format: yaml
  label: Chadwin Current reports API
  slug: chadwin-current-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-current-reports-api-openapi.yml
- filename: chadwin-insider-activity-api-openapi.yml
  format: yaml
  label: Chadwin Insider activity API
  slug: chadwin-insider-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-insider-activity-api-openapi.yml
- filename: chadwin-institutional-holdings-api-openapi.yml
  format: yaml
  label: Chadwin Institutional holdings API
  slug: chadwin-institutional-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-institutional-holdings-api-openapi.yml
- filename: chadwin-normalized-financial-statements-api-openapi.yml
  format: yaml
  label: Chadwin Normalized financial statements API
  slug: chadwin-normalized-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-normalized-financial-statements-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to buy a Personal subscription.
    type: individual
  - text: If you use Chadwin on behalf of an organization, you confirm that you are authorized to accept these Terms for that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to buy a Personal subscription.
    value: '18'
  restricted_uses:
  - summary: Personal plan no employer or business use
    text: It does not permit use on behalf of an employer, client, or other business.
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
name: Chadwin
provenance_date: '2026-11-09'
provider_name: Chadwin
provider_slug: chadwin
slug: chadwin-eligibility
source_date: '2026-11-09'
source_filename: chadwin-eligibility.yml
source_heading: Eligibility
source_page: https://www.chadwin.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chadwin\naid: chadwin\nurl: https://www.chadwin.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to buy a Personal subscription.\n- type: business\n  text: If you use Chadwin on behalf of an organization, you confirm that you are authorized to accept these Terms\n    for that organization.\nrestricted_uses:\n- summary: Personal plan no employer or business use\n  text: It does not permit use on behalf of an employer, client, or other business.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to buy a Personal subscription.\n"
source_yaml_url: https://artifacts.apis.io/chadwin/eligibility/chadwin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chadwin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Analytics
- Integration
- Enterprise
---
