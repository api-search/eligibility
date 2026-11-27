---
api_specs:
- filename: biorxiv-details-api-openapi.yml
  format: yaml
  label: bioRxiv Details API
  slug: biorxiv-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-details-api-openapi.yml
- filename: biorxiv-funder-api-openapi.yml
  format: yaml
  label: bioRxiv Funder API
  slug: biorxiv-funder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-funder-api-openapi.yml
- filename: biorxiv-pub-api-openapi.yml
  format: yaml
  label: bioRxiv Pub API
  slug: biorxiv-pub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-pub-api-openapi.yml
- filename: biorxiv-publisher-api-openapi.yml
  format: yaml
  label: bioRxiv Publisher API
  slug: biorxiv-publisher-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-publisher-api-openapi.yml
- filename: biorxiv-pubs-api-openapi.yml
  format: yaml
  label: bioRxiv Pubs API
  slug: biorxiv-pubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-pubs-api-openapi.yml
- filename: biorxiv-sum-api-openapi.yml
  format: yaml
  label: bioRxiv Sum API
  slug: biorxiv-sum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-sum-api-openapi.yml
- filename: biorxiv-usage-api-openapi.yml
  format: yaml
  label: bioRxiv Usage API
  slug: biorxiv-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biorxiv/openapi/biorxiv-usage-api-openapi.yml
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
  - summary: Screening for offensive or non-scientific content
    text: all articles undergo a basic screening process for offensive and/or non-scientific content and for material that might pose a health risk or be considered dual use research of concern
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
name: bioRxiv
provenance_date: '2026-11-09'
provider_name: bioRxiv
provider_slug: biorxiv
slug: biorxiv-eligibility
source_date: '2026-11-09'
source_filename: biorxiv-eligibility.yml
source_heading: Eligibility
source_page: https://www.biorxiv.org/content/about-biorxiv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bioRxiv\naid: biorxiv\nurl: https://www.biorxiv.org/content/about-biorxiv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Screening for offensive or non-scientific content\n  text: all articles undergo a basic screening process for offensive and/or non-scientific content and for material\n    that might pose a health risk or be considered dual use research of concern\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/biorxiv/eligibility/biorxiv-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from bioRxiv's own page on 2026-11-09.
synthetic: false
tags:
- Biology
- Preprints
- Research
- Open Access
- Life Sciences
- Scientific Publications
- Research Repository
---
