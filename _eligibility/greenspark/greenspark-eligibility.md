---
api_specs:
- filename: greenspark-account-api-openapi.yml
  format: yaml
  label: Greenspark Account API
  slug: greenspark-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-account-api-openapi.yml
- filename: greenspark-email-api-openapi.yml
  format: yaml
  label: Greenspark Email API
  slug: greenspark-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-email-api-openapi.yml
- filename: greenspark-estimations-api-openapi.yml
  format: yaml
  label: Greenspark Estimations API
  slug: greenspark-estimations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-estimations-api-openapi.yml
- filename: greenspark-impacts-api-openapi.yml
  format: yaml
  label: Greenspark Impacts API
  slug: greenspark-impacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-impacts-api-openapi.yml
- filename: greenspark-projects-api-openapi.yml
  format: yaml
  label: Greenspark Projects API
  slug: greenspark-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-projects-api-openapi.yml
- filename: greenspark-reports-api-openapi.yml
  format: yaml
  label: Greenspark Reports API
  slug: greenspark-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-reports-api-openapi.yml
- filename: greenspark-widgets-api-openapi.yml
  format: yaml
  label: Greenspark Widgets API
  slug: greenspark-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greenspark/openapi/greenspark-widgets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By entering into an agreement under these Terms on behalf of a company or other legal entity, you represent that you have the appropriate authority to bind such entity and its affiliates to these Terms.
    type: business
  minimum_age:
    text: you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorised use
    text: you comply with all applicable laws, rules, regulations and court orders
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
name: Greenspark
provenance_date: '2026-11-09'
provider_name: Greenspark
provider_slug: greenspark
slug: greenspark-eligibility
source_date: '2026-11-09'
source_filename: greenspark-eligibility.yml
source_heading: Eligibility
source_page: https://www.getgreenspark.com/utility/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greenspark\naid: greenspark\nurl: https://www.getgreenspark.com/utility/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By entering into an agreement under these Terms on behalf of a company or other legal entity, you represent\n    that you have the appropriate authority to bind such entity and its affiliates to these Terms.\nrestricted_uses:\n- summary: Unlawful or unauthorised use\n  text: you comply with all applicable laws, rules, regulations and court orders\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/greenspark/eligibility/greenspark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Greenspark's own page on 2026-11-09.
synthetic: false
tags:
- Sustainability
- Carbon Offset
- Climate
- Impact
- Carbon Estimation
- Reporting
- ESG
- Fintech
---
