---
api_specs:
- filename: hm-land-registry-application-information-api-api-openapi.yml
  format: yaml
  label: HM Land Registry Application information API
  slug: hm-land-registry-application-information-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-application-information-api-api-openapi.yml
- filename: hm-land-registry-attach-a-document-api-openapi.yml
  format: yaml
  label: HM Land Registry Attach a document API
  slug: hm-land-registry-attach-a-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-attach-a-document-api-openapi.yml
- filename: hm-land-registry-attach-a-message-api-openapi.yml
  format: yaml
  label: HM Land Registry Attach a message API
  slug: hm-land-registry-attach-a-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-attach-a-message-api-openapi.yml
- filename: hm-land-registry-datasets-api-openapi.yml
  format: yaml
  label: HM Land Registry Datasets API
  slug: hm-land-registry-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-datasets-api-openapi.yml
- filename: hm-land-registry-download-a-document-api-api-openapi.yml
  format: yaml
  label: HM Land Registry Download a document API
  slug: hm-land-registry-download-a-document-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-download-a-document-api-api-openapi.yml
- filename: hm-land-registry-draft-titles-api-openapi.yml
  format: yaml
  label: HM Land Registry Draft Titles API
  slug: hm-land-registry-draft-titles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-draft-titles-api-openapi.yml
- filename: hm-land-registry-ecd-api-openapi.yml
  format: yaml
  label: HM Land Registry ECD API
  slug: hm-land-registry-ecd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-ecd-api-openapi.yml
- filename: hm-land-registry-notifications-api-api-openapi.yml
  format: yaml
  label: HM Land Registry Notifications API
  slug: hm-land-registry-notifications-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-notifications-api-api-openapi.yml
- filename: hm-land-registry-official-search-of-whole-with-data-api-openapi.yml
  format: yaml
  label: HM Land Registry Official Search of Whole with Data API
  slug: hm-land-registry-official-search-of-whole-with-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-official-search-of-whole-with-data-api-openapi.yml
- filename: hm-land-registry-registered-proprietor-names-api-openapi.yml
  format: yaml
  label: HM Land Registry Registered Proprietor Names API
  slug: hm-land-registry-registered-proprietor-names-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-registered-proprietor-names-api-openapi.yml
- filename: hm-land-registry-send-a-document-api-api-openapi.yml
  format: yaml
  label: HM Land Registry Send a document API
  slug: hm-land-registry-send-a-document-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-send-a-document-api-api-openapi.yml
- filename: hm-land-registry-submit-an-application-api-api-openapi.yml
  format: yaml
  label: HM Land Registry Submit an application API
  slug: hm-land-registry-submit-an-application-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-submit-an-application-api-api-openapi.yml
- filename: hm-land-registry-title-api-openapi.yml
  format: yaml
  label: HM Land Registry Title API
  slug: hm-land-registry-title-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-title-api-openapi.yml
- filename: hm-land-registry-titles-api-openapi.yml
  format: yaml
  label: HM Land Registry Titles API
  slug: hm-land-registry-titles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hm-land-registry/openapi/hm-land-registry-titles-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You can create an account for your: own use'
    type: individual
  - text: work in a UK company or charity
    type: business
  - text: work in an overseas company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or unlawful activity
    text: use the information for fraudulent or unlawful activity
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All other accounts will take up to one working day to be approved.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HM Land Registry
provenance_date: '2026-11-09'
provider_name: HM Land Registry
provider_slug: hm-land-registry
slug: hm-land-registry-eligibility
source_date: '2026-11-09'
source_filename: hm-land-registry-eligibility.yml
source_heading: Eligibility
source_page: https://use-land-property-data.service.gov.uk/service-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HM Land Registry\naid: hm-land-registry\nurl: https://use-land-property-data.service.gov.uk/service-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You can create an account for your: own use'\n- type: business\n  text: work in a UK company or charity\n- type: business\n  text: work in an overseas company\nrestricted_uses:\n- summary: Fraudulent or unlawful activity\n  text: use the information for fraudulent or unlawful activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All other accounts\
  \ will take up to one working day to be approved.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hm-land-registry/eligibility/hm-land-registry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from HM Land Registry's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United Kingdom
- Land Registry
- Open Data
- Title
- Conveyancing
- Property Records
- Price Paid Data
- Linked Data
- Geospatial
- Government
- PropTech
---
