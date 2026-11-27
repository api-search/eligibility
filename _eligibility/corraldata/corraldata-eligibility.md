---
api_specs:
- filename: corraldata-openapi-generated.yml
  format: yaml
  label: CorralData API
  slug: corraldata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corraldata/openapi/_ae-authored/corraldata-openapi-generated.yml
- filename: corraldata-kb-api-openapi.yml
  format: yaml
  label: CorralData Kb API
  slug: corraldata-kb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corraldata/openapi/corraldata-kb-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You" means the individual person using the Service.'
    type: individual
  - text: '"Customer" means the organization that has a Services Order Form with CorralData, or that invited you to use the Service.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing uploads
    text: Upload or transmit anything that is unlawful, infringing, harmful or deceptive, or that you don't have the right to share.
  - summary: Export law
    text: use it in violation of U.S. export laws.
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
name: CorralData
provenance_date: '2026-11-09'
provider_name: CorralData
provider_slug: corraldata
slug: corraldata-eligibility
source_date: '2026-11-09'
source_filename: corraldata-eligibility.yml
source_heading: Eligibility
source_page: https://corraldata.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CorralData\naid: corraldata\nurl: https://corraldata.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"You\" means the individual person using the Service.'\n- type: business\n  text: '\"Customer\" means the organization that has a Services Order Form with CorralData, or that invited you to\n    use the Service.'\nrestricted_uses:\n- summary: Unlawful or infringing uploads\n  text: Upload or transmit anything that is unlawful, infringing, harmful or deceptive, or that you don't have the\n    right to share.\n- summary:\
  \ Export law\n  text: use it in violation of U.S. export laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corraldata/eligibility/corraldata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CorralData's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Analytics
- Healthcare
- Artificial Intelligence
- Platform
---
