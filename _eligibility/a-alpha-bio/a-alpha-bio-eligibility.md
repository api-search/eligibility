---
api_specs:
- filename: a-alpha-bio-datasets-api-openapi.yml
  format: yaml
  label: A-Alpha Bio Datasets API
  slug: a-alpha-bio-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-alpha-bio/openapi/a-alpha-bio-datasets-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company or entity on whose behalf you entered this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No infringing or unlawful use
    text: use the Services in any manner or for any purpose that infringes, misappropriates, or otherwise violates any Intellectual Property Rights or other right of any person or entity, or that violates any applicable law
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
name: A-Alpha Bio
provenance_date: '2026-11-09'
provider_name: A-Alpha Bio
provider_slug: a-alpha-bio
slug: a-alpha-bio-eligibility
source_date: '2026-11-09'
source_filename: a-alpha-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.aalphabio.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A-Alpha Bio\naid: a-alpha-bio\nurl: https://www.aalphabio.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company or entity on whose behalf you entered this Agreement\nrestricted_uses:\n- summary: No infringing or unlawful use\n  text: use the Services in any manner or for any purpose that infringes, misappropriates, or otherwise violates\n    any Intellectual Property Rights or other right of any person or entity, or that violates any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a-alpha-bio/eligibility/a-alpha-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from A-Alpha Bio's own page on 2026-11-09.
synthetic: false
tags:
- protein-interactions
- Biotechnology
- Drug Discovery
- Antibody Engineering
- Synthetic Biology
- Machine Learning
- Training Data
- Data Licensing
- Life Sciences
- Datasets
- Protein Design
- Bioinformatics
---
