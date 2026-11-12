---
api_specs:
- filename: corporary-com-change-api-openapi.yml
  format: yaml
  label: corporary Change API
  slug: corporary-com-change-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-change-api-openapi.yml
- filename: corporary-com-company-api-openapi.yml
  format: yaml
  label: corporary Company API
  slug: corporary-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-company-api-openapi.yml
- filename: corporary-com-search-api-openapi.yml
  format: yaml
  label: corporary Search API
  slug: corporary-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-search-api-openapi.yml
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
  - summary: Personal data reuse
    text: Les données relatives à des personnes physiques, notamment les dirigeants, ne peuvent être réutilisées que dans le respect du règlement général sur la protection des données.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Un compte, ouvert par un lien de connexion envoyé par courriel
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: corporary
provenance_date: '2026-11-09'
provider_name: corporary
provider_slug: corporary-com
slug: corporary-com-eligibility
source_date: '2026-11-09'
source_filename: corporary-com-eligibility.yml
source_heading: Eligibility
source_page: https://corporary.com/fr/conditions-utilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: corporary\naid: corporary-com\nurl: https://corporary.com/fr/conditions-utilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal data reuse\n  text: Les données relatives à des personnes physiques, notamment les dirigeants, ne peuvent être réutilisées que\n    dans le respect du règlement général sur la protection des données.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Un compte, ouvert par un lien de connexion envoyé par courriel\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corporary-com/eligibility/corporary-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from corporary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Business Registry
- France
- Financial Data
- Legal Announcements
- MCP
- Open Data
---
