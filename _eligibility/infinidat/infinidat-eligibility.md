---
api_specs:
- filename: infinidat-components-api-openapi.yml
  format: yaml
  label: Infinidat Components API
  slug: infinidat-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-components-api-openapi.yml
- filename: infinidat-config-api-openapi.yml
  format: yaml
  label: Infinidat Config API
  slug: infinidat-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-config-api-openapi.yml
- filename: infinidat-filesystems-api-openapi.yml
  format: yaml
  label: Infinidat Filesystems API
  slug: infinidat-filesystems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-filesystems-api-openapi.yml
- filename: infinidat-hosts-api-openapi.yml
  format: yaml
  label: Infinidat Hosts API
  slug: infinidat-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-hosts-api-openapi.yml
- filename: infinidat-metadata-api-openapi.yml
  format: yaml
  label: Infinidat Metadata API
  slug: infinidat-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-metadata-api-openapi.yml
- filename: infinidat-pools-api-openapi.yml
  format: yaml
  label: Infinidat Pools API
  slug: infinidat-pools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-pools-api-openapi.yml
- filename: infinidat-system-api-openapi.yml
  format: yaml
  label: Infinidat System API
  slug: infinidat-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-system-api-openapi.yml
- filename: infinidat-users-api-openapi.yml
  format: yaml
  label: Infinidat Users API
  slug: infinidat-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infinidat/openapi/infinidat-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Distributor” means a legal entity which, on a non-exclusive basis, is engaged with Infinidat
    type: business
  - text: If Purchaser is an agency, department, employee or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use prohibited by U.S. law
    text: it will not use Products or technology for any purposes prohibited by U.S. law
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Purchase Orders are subject to credit approval and acceptance by Infinidat.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Infinidat
provenance_date: '2026-11-09'
provider_name: Infinidat
provider_slug: infinidat
slug: infinidat-eligibility
source_date: '2026-11-09'
source_filename: infinidat-eligibility.yml
source_heading: Eligibility
source_page: https://www.infinidat.com/en/sites/default/files/resource-pdfs/INFINIDAT-Customer-Product-Online-TCs.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infinidat\naid: infinidat\nurl: https://www.infinidat.com/en/sites/default/files/resource-pdfs/INFINIDAT-Customer-Product-Online-TCs.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Distributor” means a legal entity which, on a non-exclusive basis, is engaged with Infinidat\n- type: government\n  text: If Purchaser is an agency, department, employee or other entity of the United States Government\nrestricted_uses:\n- summary: No use prohibited by U.S. law\n  text: it will not use Products or technology for any\
  \ purposes prohibited by U.S. law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Purchase Orders are subject to credit approval and acceptance by Infinidat.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infinidat/eligibility/infinidat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Infinidat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Storage
- Enterprise Storage
- Data Infrastructure
- Data Protection
- Cyber Resilience
- Backup and Recovery
- Kubernetes
- Infrastructure
- On-Premises
---
