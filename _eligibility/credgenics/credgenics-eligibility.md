---
api_specs:
- filename: credgenics-authentication-api-openapi.yml
  format: yaml
  label: Credgenics Authentication API
  slug: credgenics-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credgenics/openapi/credgenics-authentication-api-openapi.yml
- filename: credgenics-credit-line-api-openapi.yml
  format: yaml
  label: Credgenics Credit Line API
  slug: credgenics-credit-line-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credgenics/openapi/credgenics-credit-line-api-openapi.yml
- filename: credgenics-lending-api-openapi.yml
  format: yaml
  label: Credgenics Lending API
  slug: credgenics-lending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credgenics/openapi/credgenics-lending-api-openapi.yml
claim_count: 1
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
  - summary: Lawyer ethics compliance
    text: If you are an attorney/lawyer participating in any aspect of this Web Site, including but not limited to message(s), chats or e-mail forums, you acknowledge that the Bar Council Rules of Professional Conduct in India ("Rules") apply to all aspects of your participation
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
name: Credgenics
provenance_date: '2026-11-09'
provider_name: Credgenics
provider_slug: credgenics
slug: credgenics-eligibility
source_date: '2026-11-09'
source_filename: credgenics-eligibility.yml
source_heading: Eligibility
source_page: https://www.credgenics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Credgenics\naid: credgenics\nurl: https://www.credgenics.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawyer ethics compliance\n  text: If you are an attorney/lawyer participating in any aspect of this Web Site, including but not limited to\n    message(s), chats or e-mail forums, you acknowledge that the Bar Council Rules of Professional Conduct in India\n    (\"Rules\") apply to all aspects of your participation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/credgenics/eligibility/credgenics-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Credgenics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Financial Services
- Debt Collection
- Loan Recovery
- Lending
- Collection
- Fintech
- India
---
