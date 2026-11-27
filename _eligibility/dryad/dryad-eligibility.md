---
api_specs:
- filename: dryad-datasets-api-openapi.yml
  format: yaml
  label: Dryad Datasets API
  slug: dryad-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-datasets-api-openapi.yml
- filename: dryad-files-api-openapi.yml
  format: yaml
  label: Dryad Files API
  slug: dryad-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-files-api-openapi.yml
- filename: dryad-internal-api-openapi.yml
  format: yaml
  label: Dryad Internal API
  slug: dryad-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-internal-api-openapi.yml
- filename: dryad-reports-api-openapi.yml
  format: yaml
  label: Dryad Reports API
  slug: dryad-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-reports-api-openapi.yml
- filename: dryad-root-api-openapi.yml
  format: yaml
  label: Dryad Root API
  slug: dryad-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-root-api-openapi.yml
- filename: dryad-search-api-openapi.yml
  format: yaml
  label: Dryad Search API
  slug: dryad-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-search-api-openapi.yml
- filename: dryad-versions-api-openapi.yml
  format: yaml
  label: Dryad Versions API
  slug: dryad-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dryad/openapi/dryad-versions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If an End User is prohibited under any U.S. laws or any other regulations from receiving U.S. origin services or software, they may not use the Dryad Infrastructure and Services.
  entity_types:
  - text: These Terms apply with equal force to individuals and entities using Dryad Infrastructure and Services.
    type: individual
  - text: These Terms apply with equal force to individuals and entities using Dryad Infrastructure and Services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or service-impairing use
    text: 'End Users may not use the Dryad Infrastructure and Services : in any unlawful manner;'
  - summary: Sanctioned persons
    text: The Submitter warrants that neither s/he nor any co-author(s) or co-creator(s) is a person whose name appears on the list of Specially Designated Nationals and Blocked Persons published by the Office of Foreign Assets Control, U.S. Department of Treasury (“OFAC”);
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
name: Dryad
provenance_date: '2026-11-09'
provider_name: Dryad
provider_slug: dryad
slug: dryad-eligibility
source_date: '2026-11-09'
source_filename: dryad-eligibility.yml
source_heading: Eligibility
source_page: https://datadryad.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dryad\naid: dryad\nurl: https://datadryad.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If an End User is prohibited under any U.S. laws or any other regulations from receiving U.S. origin services\n    or software, they may not use the Dryad Infrastructure and Services.\nentity_types:\n- type: individual\n  text: These Terms apply with equal force to individuals and entities using Dryad Infrastructure and Services.\n- type: business\n  text: These Terms apply with equal force to individuals and entities using Dryad Infrastructure and Services.\nrestricted_uses:\n- summary:\
  \ Unlawful or service-impairing use\n  text: 'End Users may not use the Dryad Infrastructure and Services : in any unlawful manner;'\n- summary: Sanctioned persons\n  text: The Submitter warrants that neither s/he nor any co-author(s) or co-creator(s) is a person whose name appears\n    on the list of Specially Designated Nationals and Blocked Persons published by the Office of Foreign Assets\n    Control, U.S. Department of Treasury (“OFAC”);\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dryad/eligibility/dryad-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Dryad's own page on 2026-11-09.
synthetic: false
tags:
- Research Data
- Open Science
- Research Repository
- Datasets
- Biology
- Ecology
- Open Access
---
