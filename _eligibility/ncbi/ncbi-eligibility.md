---
api_specs:
- filename: ncbi-biosample-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) BioSample API
  slug: ncbi-biosample-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-biosample-api-openapi.yml
- filename: ncbi-gene-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Gene API
  slug: ncbi-gene-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-gene-api-openapi.yml
- filename: ncbi-genome-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Genome API
  slug: ncbi-genome-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-genome-api-openapi.yml
- filename: ncbi-organelle-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Organelle API
  slug: ncbi-organelle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-organelle-api-openapi.yml
- filename: ncbi-prokaryote-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Prokaryote API
  slug: ncbi-prokaryote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-prokaryote-api-openapi.yml
- filename: ncbi-taxonomy-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Taxonomy API
  slug: ncbi-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-taxonomy-api-openapi.yml
- filename: ncbi-version-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Version API
  slug: ncbi-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-version-api-openapi.yml
- filename: ncbi-virus-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Virus API
  slug: ncbi-virus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-virus-api-openapi.yml
- filename: ncbi-blast-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) BLAST API
  slug: ncbi-blast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-blast-api-openapi.yml
- filename: ncbi-fetch-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Fetch API
  slug: ncbi-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-fetch-api-openapi.yml
- filename: ncbi-info-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Info API
  slug: ncbi-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-info-api-openapi.yml
- filename: ncbi-link-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Link API
  slug: ncbi-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-link-api-openapi.yml
- filename: ncbi-search-api-openapi.yml
  format: yaml
  label: National Center for Biotechnology Information (NCBI) Search API
  slug: ncbi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ncbi/openapi/ncbi-search-api-openapi.yml
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
  - summary: Scripted retrieval timing
    text: Run retrieval scripts on weekends or between 9 pm and 5 am Eastern Time weekdays for any series of more than 100 requests.
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
name: National Center for Biotechnology Information (NCBI)
provenance_date: '2026-11-10'
provider_name: National Center for Biotechnology Information (NCBI)
provider_slug: ncbi
slug: ncbi-eligibility
source_date: '2026-11-10'
source_filename: ncbi-eligibility.yml
source_heading: Eligibility
source_page: https://www.ncbi.nlm.nih.gov/home/about/policies/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: National Center for Biotechnology Information (NCBI)\naid: ncbi\nurl: https://www.ncbi.nlm.nih.gov/home/about/policies/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Scripted retrieval timing\n  text: Run retrieval scripts on weekends or between 9 pm and 5 am Eastern Time weekdays for any series of more\n    than 100 requests.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ncbi/eligibility/ncbi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from National Center for Biotechnology Information (NCBI)'s own page on 2026-11-10.
synthetic: false
tags:
- Bioinformatics
- Genomics
- Life Sciences
- PubMed
- Sequences
- BLAST
- Taxonomy
- Chemistry
- Open Access
- Research Data
- OAI-PMH
---
