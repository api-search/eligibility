---
api_specs:
- filename: ex2-com-compare-api-openapi.yml
  format: yaml
  label: ex2-com Compare API
  slug: ex2-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-compare-api-openapi.yml
- filename: ex2-com-domains-api-openapi.yml
  format: yaml
  label: ex2-com Domains API
  slug: ex2-com-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-domains-api-openapi.yml
- filename: ex2-com-ex2-catalogue-api-api-openapi.yml
  format: yaml
  label: ex2-com Ex2 Catalogue API
  slug: ex2-com-ex2-catalogue-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-ex2-catalogue-api-api-openapi.yml
- filename: ex2-com-migration-api-openapi.yml
  format: yaml
  label: ex2-com Migration API
  slug: ex2-com-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-migration-api-openapi.yml
- filename: ex2-com-plans-api-openapi.yml
  format: yaml
  label: ex2-com Plans API
  slug: ex2-com-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-plans-api-openapi.yml
- filename: ex2-com-status-api-openapi.yml
  format: yaml
  label: ex2-com Status API
  slug: ex2-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-status-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Toute personne physique ou morale ayant passé commande d’une prestation d’hébergement et signataire du contrat.
    type: individual
  - text: Toute personne physique ou morale ayant passé commande d’une prestation d’hébergement et signataire du contrat.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adult sites
    text: Tout site à caractère pornographique doit se conformer aux lois en vigueur au Canada et en France et présenter uniquement des modèles consentants âgés de 18 ans ou plus.
  - summary: Sanctioned parties
    text: Ex2 se réserve le droit de résilier le présent contrat, en tout ou partie, de plein droit, sans préavis, avec effet immédiat
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
name: ex2-com
provenance_date: '2026-11-09'
provider_name: ex2-com
provider_slug: ex2-com
slug: ex2-com-eligibility
source_date: '2026-11-09'
source_filename: ex2-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.ex2.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ex2-com\naid: ex2-com\nurl: https://www.ex2.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Toute personne physique ou morale ayant passé commande d’une prestation d’hébergement et signataire du contrat.\n- type: business\n  text: Toute personne physique ou morale ayant passé commande d’une prestation d’hébergement et signataire du contrat.\nrestricted_uses:\n- summary: Adult sites\n  text: Tout site à caractère pornographique doit se conformer aux lois en vigueur au Canada et en France et présenter\n    uniquement\
  \ des modèles consentants âgés de 18 ans ou plus.\n- summary: Sanctioned parties\n  text: Ex2 se réserve le droit de résilier le présent contrat, en tout ou partie, de plein droit, sans préavis,\n    avec effet immédiat\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ex2-com/eligibility/ex2-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ex2-com's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- Sustainability
- Web Hosting
- Quebec
- GreenTech
---
