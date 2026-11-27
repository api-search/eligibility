---
api_specs:
- filename: jobopportunitiesapi-org-companies-api-openapi.yml
  format: yaml
  label: jobopportunitiesapi-org Companies API
  slug: jobopportunitiesapi-org-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobopportunitiesapi-org/openapi/jobopportunitiesapi-org-companies-api-openapi.yml
- filename: jobopportunitiesapi-org-jobs-api-openapi.yml
  format: yaml
  label: jobopportunitiesapi-org Jobs API
  slug: jobopportunitiesapi-org-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobopportunitiesapi-org/openapi/jobopportunitiesapi-org-jobs-api-openapi.yml
- filename: jobopportunitiesapi-org-meta-api-openapi.yml
  format: yaml
  label: jobopportunitiesapi-org Meta API
  slug: jobopportunitiesapi-org-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobopportunitiesapi-org/openapi/jobopportunitiesapi-org-meta-api-openapi.yml
- filename: jobopportunitiesapi-org-public-api-openapi.yml
  format: yaml
  label: jobopportunitiesapi-org Public API
  slug: jobopportunitiesapi-org-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobopportunitiesapi-org/openapi/jobopportunitiesapi-org-public-api-openapi.yml
claim_count: 2
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
  - summary: No fees on Teaching Vacancies jobs
    text: You must not use them to charge any fee or commission for contacting, interviewing or hiring candidates who respond to those jobs.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: There is no separate account setup, waiting period or approval step.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: jobopportunitiesapi-org
provenance_date: '2026-11-09'
provider_name: Job Opportunities API
provider_slug: jobopportunitiesapi-org
slug: jobopportunitiesapi-org-eligibility
source_date: '2026-11-09'
source_filename: jobopportunitiesapi-org-eligibility.yml
source_heading: Eligibility
source_page: https://jobopportunitiesapi.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: jobopportunitiesapi-org\naid: jobopportunitiesapi-org\nurl: https://jobopportunitiesapi.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No fees on Teaching Vacancies jobs\n  text: You must not use them to charge any fee or commission for contacting, interviewing or hiring candidates\n    who respond to those jobs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: There is no separate account setup, waiting period or approval step.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jobopportunitiesapi-org/eligibility/jobopportunitiesapi-org-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from jobopportunitiesapi-org's own page on 2026-11-09.
synthetic: false
tags:
- Job
- Employment Data
- Data Provenance
- Job Board
- AI Agents
---
