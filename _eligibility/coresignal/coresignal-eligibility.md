---
api_specs:
- filename: coresignal-collect-api-openapi.yml
  format: yaml
  label: Coresignal Collect API
  slug: coresignal-collect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coresignal/openapi/coresignal-collect-api-openapi.yml
- filename: coresignal-search-api-openapi.yml
  format: yaml
  label: Coresignal Search API
  slug: coresignal-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coresignal/openapi/coresignal-search-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Website
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Website
    type: business
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Advertising or marketing
    text: using this Website to engage in any advertising or marketing.
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
name: Coresignal
provenance_date: '2026-11-09'
provider_name: Coresignal
provider_slug: coresignal
slug: coresignal-eligibility
source_date: '2026-11-09'
source_filename: coresignal-eligibility.yml
source_heading: Eligibility
source_page: https://coresignal.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coresignal\naid: coresignal\nurl: https://coresignal.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Website\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Website\nrestricted_uses:\n- summary: Advertising or marketing\n  text: using this Website to engage in any advertising or marketing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/coresignal/eligibility/coresignal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Coresignal's own page on 2026-11-09.
synthetic: false
tags:
- Agentic Search
- B2B Data
- Companies
- Company Data
- Data as a Service
- Elasticsearch
- Employee Data
- Employees
- Data Enrichment
- Firmographics
- Job Postings
- Job
- Lead Generation
- People Data
- Sales Intelligence
- Talent Intelligence
- Web Data
---
