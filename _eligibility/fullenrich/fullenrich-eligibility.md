---
api_specs:
- filename: fullenrich-account-api-openapi.yml
  format: yaml
  label: FullEnrich Account API
  slug: fullenrich-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-account-api-openapi.yml
- filename: fullenrich-company-api-openapi.yml
  format: yaml
  label: FullEnrich Company API
  slug: fullenrich-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-company-api-openapi.yml
- filename: fullenrich-contact-api-openapi.yml
  format: yaml
  label: FullEnrich Contact API
  slug: fullenrich-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-contact-api-openapi.yml
- filename: fullenrich-people-api-openapi.yml
  format: yaml
  label: FullEnrich People API
  slug: fullenrich-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullenrich/openapi/fullenrich-people-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company that has subscribed to the Services via FullEnrich's website or via an order form
    type: business
  - text: If the Client is an individual using the Service for non-commercial purposes
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No covered data transactions
    text: Client shall not transfer, or otherwise make available or provide access to, FullEnrich data to any party in a manner that would qualify as a "covered data transaction"
  - summary: No storing Sensitive Data
    text: the Client will not use the Service to store Sensitive Data and will not submit, post, or otherwise transmit through the Service any Client Data that includes or constitutes Sensitive Data.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: FullEnrich may request confirmation from the Client of their information and may request any proof whatsoever.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FullEnrich
provenance_date: '2026-11-09'
provider_name: FullEnrich
provider_slug: fullenrich
slug: fullenrich-eligibility
source_date: '2026-11-09'
source_filename: fullenrich-eligibility.yml
source_heading: Eligibility
source_page: https://fullenrich.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FullEnrich\naid: fullenrich\nurl: https://fullenrich.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company that has subscribed to the Services via FullEnrich's website or via an order form\n- type: individual\n  text: If the Client is an individual using the Service for non-commercial purposes\nrestricted_uses:\n- summary: No covered data transactions\n  text: Client shall not transfer, or otherwise make available or provide access to, FullEnrich data to any party\n    in a manner that would qualify as\
  \ a \"covered data transaction\"\n- summary: No storing Sensitive Data\n  text: the Client will not use the Service to store Sensitive Data and will not submit, post, or otherwise transmit\n    through the Service any Client Data that includes or constitutes Sensitive Data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: FullEnrich may request confirmation from the Client of their information and may request any proof whatsoever.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fullenrich/eligibility/fullenrich-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from FullEnrich's own page on 2026-11-09.
synthetic: false
tags:
- B2B Data
- Contact Enrichment
- Email Finder
- Phone Finder
- Waterfall Enrichment
- Sales Intelligence
- People Search
- Company Search
- Reverse Email Lookup
- A2A
- Data Enrichment
---
