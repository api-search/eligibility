---
api_specs:
- filename: djamo-webhooks-asyncapi.yml
  format: yaml
  label: Djamo Business API
  slug: djamo-business-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/djamo/asyncapi/djamo-webhooks-asyncapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - CI
    - SN
    text: Sélectionnez votre pays Côte d'Ivoire Côte d'Ivoire Sénégal
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
name: Djamo
provenance_date: '2026-11-09'
provider_name: Djamo
provider_slug: djamo
slug: djamo-eligibility
source_date: '2026-11-09'
source_filename: djamo-eligibility.yml
source_heading: Eligibility
source_page: https://www.djamo.com/fr-ci/conditions-generales-et-tarifaires
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Djamo\naid: djamo\nurl: https://www.djamo.com/fr-ci/conditions-generales-et-tarifaires\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CI\n  - SN\n  excluded: []\n  text: Sélectionnez votre pays Côte d'Ivoire Côte d'Ivoire Sénégal\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/djamo/eligibility/djamo-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Djamo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Payments
- Banking
- Money Transfer
- Africa
- Côte d'Ivoire
- Sénégal
---
