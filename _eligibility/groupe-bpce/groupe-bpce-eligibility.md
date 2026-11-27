---
api_specs:
- filename: groupe-bpce-aisp-api-openapi.yml
  format: yaml
  label: Groupe BPCE AISP API
  slug: groupe-bpce-aisp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-aisp-api-openapi.yml
- filename: groupe-bpce-cbpii-api-openapi.yml
  format: yaml
  label: Groupe BPCE CBPII API
  slug: groupe-bpce-cbpii-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-cbpii-api-openapi.yml
- filename: groupe-bpce-external-accounts-api-openapi.yml
  format: yaml
  label: Groupe BPCE External Accounts API
  slug: groupe-bpce-external-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-external-accounts-api-openapi.yml
- filename: groupe-bpce-internal-accounts-api-openapi.yml
  format: yaml
  label: Groupe BPCE Internal Accounts API
  slug: groupe-bpce-internal-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-internal-accounts-api-openapi.yml
- filename: groupe-bpce-pisp-api-openapi.yml
  format: yaml
  label: Groupe BPCE PISP API
  slug: groupe-bpce-pisp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-pisp-api-openapi.yml
- filename: groupe-bpce-registration-api-openapi.yml
  format: yaml
  label: Groupe BPCE Registration API
  slug: groupe-bpce-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-registration-api-openapi.yml
- filename: groupe-bpce-transfers-api-openapi.yml
  format: yaml
  label: Groupe BPCE Transfers API
  slug: groupe-bpce-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groupe-bpce/openapi/groupe-bpce-transfers-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to all or part of the information and services provided on the Platform may be restricted for certain individuals or in certain countries.
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
name: Groupe BPCE
provenance_date: '2026-11-09'
provider_name: Groupe BPCE
provider_slug: groupe-bpce
slug: groupe-bpce-eligibility
source_date: '2026-11-09'
source_filename: groupe-bpce-eligibility.yml
source_heading: Eligibility
source_page: https://apistore.groupebpce.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Groupe BPCE\naid: groupe-bpce\nurl: https://apistore.groupebpce.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to all or part of the information and services provided on the Platform may be restricted for certain\n    individuals or in certain countries.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/groupe-bpce/eligibility/groupe-bpce-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Groupe BPCE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Financial Services
- Open Banking
- PSD2
- Payments
- Insurance
- France
---
