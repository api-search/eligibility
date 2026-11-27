---
api_specs:
- filename: buckybuild-com-addresses-api-openapi.yml
  format: yaml
  label: Bucky Addresses API
  slug: buckybuild-com-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-addresses-api-openapi.yml
- filename: buckybuild-com-citations-api-openapi.yml
  format: yaml
  label: Bucky Citations API
  slug: buckybuild-com-citations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-citations-api-openapi.yml
- filename: buckybuild-com-coverage-api-openapi.yml
  format: yaml
  label: Bucky Coverage API
  slug: buckybuild-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-coverage-api-openapi.yml
- filename: buckybuild-com-credentials-api-openapi.yml
  format: yaml
  label: Bucky Credentials API
  slug: buckybuild-com-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-credentials-api-openapi.yml
- filename: buckybuild-com-feasibility-api-openapi.yml
  format: yaml
  label: Bucky Feasibility API
  slug: buckybuild-com-feasibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-feasibility-api-openapi.yml
- filename: buckybuild-com-marketplace-api-openapi.yml
  format: yaml
  label: Bucky Marketplace API
  slug: buckybuild-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-marketplace-api-openapi.yml
- filename: buckybuild-com-sites-api-openapi.yml
  format: yaml
  label: Bucky Sites API
  slug: buckybuild-com-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-sites-api-openapi.yml
- filename: buckybuild-com-usage-api-openapi.yml
  format: yaml
  label: Bucky Usage API
  slug: buckybuild-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live, and able to form a contract.
    type: individual
  - text: If you use Bucky for an organization, you represent that you can bind it.
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live
    value: '18'
  restricted_uses:
  - summary: No formal opinions or approvals
    text: Present Bucky outputs as a survey, legal opinion, architectural stamp, or municipal approval.
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
name: Bucky
provenance_date: '2026-11-09'
provider_name: Bucky
provider_slug: buckybuild-com
slug: buckybuild-com-eligibility
source_date: '2026-11-09'
source_filename: buckybuild-com-eligibility.yml
source_heading: Eligibility
source_page: https://buckybuild.com/en-us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bucky\naid: buckybuild-com\nurl: https://buckybuild.com/en-us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live, and able to form a contract.\n- type: business\n  text: If you use Bucky for an organization, you represent that you can bind it.\nrestricted_uses:\n- summary: No formal opinions or approvals\n  text: Present Bucky outputs as a survey, legal opinion, architectural stamp, or municipal approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/buckybuild-com/eligibility/buckybuild-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bucky's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Zoning
- Mapping
- Data API
- Visualization
- Company
---
