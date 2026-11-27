---
api_specs:
- filename: clinical-trials-gov-stats-api-openapi.yml
  format: yaml
  label: ClinicalTrials.gov Stats API
  slug: clinical-trials-gov-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinical-trials-gov/openapi/clinical-trials-gov-stats-api-openapi.yml
- filename: clinical-trials-gov-studies-api-openapi.yml
  format: yaml
  label: ClinicalTrials.gov Studies API
  slug: clinical-trials-gov-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinical-trials-gov/openapi/clinical-trials-gov-studies-api-openapi.yml
- filename: clinical-trials-gov-version-api-openapi.yml
  format: yaml
  label: ClinicalTrials.gov Version API
  slug: clinical-trials-gov-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinical-trials-gov/openapi/clinical-trials-gov-version-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: ClinicalTrials.gov data are available to all requesters, both within and outside the United States, at no charge.
  entity_types:
  - text: available to all requesters
    type: other
  minimum_age:
    text: null
    value: null
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
name: ClinicalTrials.gov
provenance_date: '2026-11-09'
provider_name: ClinicalTrials.gov
provider_slug: clinical-trials-gov
slug: clinical-trials-gov-eligibility
source_date: '2026-11-09'
source_filename: clinical-trials-gov-eligibility.yml
source_heading: Eligibility
source_page: https://clinicaltrials.gov/about-site/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClinicalTrials.gov\naid: clinical-trials-gov\nurl: https://clinicaltrials.gov/about-site/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: ClinicalTrials.gov data are available to all requesters, both within and outside the United States, at no\n    charge.\nentity_types:\n- type: other\n  text: available to all requesters\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clinical-trials-gov/eligibility/clinical-trials-gov-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from ClinicalTrials.gov's own page on 2026-11-09.
synthetic: false
tags:
- Clinical Trials
- Government
- Health
- NIH
- Open Data
- Public Health
- Research
---
