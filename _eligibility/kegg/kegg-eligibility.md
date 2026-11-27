---
api_specs:
- filename: kegg-conv-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) conv API
  slug: kegg-conv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-conv-api-openapi.yml
- filename: kegg-ddi-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) ddi API
  slug: kegg-ddi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-ddi-api-openapi.yml
- filename: kegg-find-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) Find API
  slug: kegg-find-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-find-api-openapi.yml
- filename: kegg-get-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) Get API
  slug: kegg-get-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-get-api-openapi.yml
- filename: kegg-info-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) Info API
  slug: kegg-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-info-api-openapi.yml
- filename: kegg-link-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) Link API
  slug: kegg-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-link-api-openapi.yml
- filename: kegg-list-api-openapi.yml
  format: yaml
  label: Kyoto Encyclopedia of Genes and Genomes (KEGG) List API
  slug: kegg-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kegg/openapi/kegg-list-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Non-academic use of KEGG requires a commercial license.
    type: business
  - text: Academic users may freely use the KEGG website at https://www.kegg.jp/ or its mirror site at GenomeNet https://www.genome.jp/kegg/
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-academic use requires commercial license
    text: Non-academic use of KEGG requires a commercial license.
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
name: Kyoto Encyclopedia of Genes and Genomes (KEGG)
provenance_date: '2026-11-09'
provider_name: Kyoto Encyclopedia of Genes and Genomes (KEGG)
provider_slug: kegg
slug: kegg-eligibility
source_date: '2026-11-09'
source_filename: kegg-eligibility.yml
source_heading: Eligibility
source_page: https://www.kegg.jp/kegg/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kyoto Encyclopedia of Genes and Genomes (KEGG)\naid: kegg\nurl: https://www.kegg.jp/kegg/legal.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Non-academic use of KEGG requires a commercial license.\n- type: other\n  text: Academic users may freely use the KEGG website at https://www.kegg.jp/ or its mirror site at GenomeNet https://www.genome.jp/kegg/\nrestricted_uses:\n- summary: Non-academic use requires commercial license\n  text: Non-academic use of KEGG requires a commercial license.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kegg/eligibility/kegg-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kyoto Encyclopedia of Genes and Genomes (KEGG)'s own page on 2026-11-09.
synthetic: false
tags:
- Bioinformatics
- Genomics
- Life Sciences
- Pathways
- Metabolomics
- Drug Targets
- Disease
- Chemical Compounds
- Enzymes
- Orthology
---
