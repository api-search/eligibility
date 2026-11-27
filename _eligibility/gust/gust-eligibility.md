---
api_specs:
- filename: gust-openapi-generated.yml
  format: yaml
  label: Gust API
  slug: gust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gust/openapi/_ae-authored/gust-openapi-generated.yml
- filename: gust-accounts-api-openapi.yml
  format: yaml
  label: Gust Accounts API
  slug: gust-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gust/openapi/gust-accounts-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under the age of 18, please do not sign up for an account.
    type: individual
  - text: Organizations may also register and will be overseen by the Organization Administrator.
    type: other
  minimum_age:
    text: If you are under the age of 18, please do not sign up for an account.
    value: '18'
  restricted_uses:
  - summary: Investor use requires accredited status
    text: if you wish to use the Gust platform as an investor, you must be an Accredited Investor and so represent to Gust.
  verification:
    approval_required: false
    kyb: false
    kyc: false
    text: Gust enables Users to self-accreditate, but Gust does not certify or verify the self-accreditation of any of its Users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gust
provenance_date: '2026-11-09'
provider_name: Gust
provider_slug: gust
slug: gust-eligibility
source_date: '2026-11-09'
source_filename: gust-eligibility.yml
source_heading: Eligibility
source_page: https://gust.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gust\naid: gust\nurl: https://gust.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under the age of 18, please do not sign up for an account.\n- type: other\n  text: Organizations may also register and will be overseen by the Organization Administrator.\nrestricted_uses:\n- summary: Investor use requires accredited status\n  text: if you wish to use the Gust platform as an investor, you must be an Accredited Investor and so represent\n    to Gust.\nverification:\n  kyc: false\n  kyb: false\n  approval_required:\
  \ false\n  text: Gust enables Users to self-accreditate, but Gust does not certify or verify the self-accreditation of any\n    of its Users.\nminimum_age:\n  value: '18'\n  text: If you are under the age of 18, please do not sign up for an account.\n"
source_yaml_url: https://artifacts.apis.io/gust/eligibility/gust-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gust's own page on 2026-11-09.
synthetic: false
tags:
- Incorporation
- Equity Management
- Fundraising
- Startup Tools
- Investor Tools
- Accelerator Management
---
