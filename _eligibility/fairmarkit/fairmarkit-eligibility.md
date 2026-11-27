---
api_specs:
- filename: fairmarkit-business-units-api-openapi.yml
  format: yaml
  label: Fairmarkit Business Units API
  slug: fairmarkit-business-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-business-units-api-openapi.yml
- filename: fairmarkit-categories-api-openapi.yml
  format: yaml
  label: Fairmarkit Categories API
  slug: fairmarkit-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-categories-api-openapi.yml
- filename: fairmarkit-data-exports-api-openapi.yml
  format: yaml
  label: Fairmarkit Data Exports API
  slug: fairmarkit-data-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-data-exports-api-openapi.yml
- filename: fairmarkit-data-fields-api-openapi.yml
  format: yaml
  label: Fairmarkit Data Fields API
  slug: fairmarkit-data-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-data-fields-api-openapi.yml
- filename: fairmarkit-erp-systems-api-openapi.yml
  format: yaml
  label: Fairmarkit ERP Systems API
  slug: fairmarkit-erp-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-erp-systems-api-openapi.yml
- filename: fairmarkit-event-api-openapi.yml
  format: yaml
  label: Fairmarkit Event API
  slug: fairmarkit-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-event-api-openapi.yml
- filename: fairmarkit-file-attachments-api-openapi.yml
  format: yaml
  label: Fairmarkit File attachments API
  slug: fairmarkit-file-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-file-attachments-api-openapi.yml
- filename: fairmarkit-identity-api-openapi.yml
  format: yaml
  label: Fairmarkit Identity API
  slug: fairmarkit-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-identity-api-openapi.yml
- filename: fairmarkit-price-books-api-openapi.yml
  format: yaml
  label: Fairmarkit Price Books API
  slug: fairmarkit-price-books-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-price-books-api-openapi.yml
- filename: fairmarkit-purchase-orders-api-openapi.yml
  format: yaml
  label: Fairmarkit Purchase Orders API
  slug: fairmarkit-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-purchase-orders-api-openapi.yml
- filename: fairmarkit-requests-api-openapi.yml
  format: yaml
  label: Fairmarkit Requests API
  slug: fairmarkit-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-requests-api-openapi.yml
- filename: fairmarkit-responses-api-openapi.yml
  format: yaml
  label: Fairmarkit Responses API
  slug: fairmarkit-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-responses-api-openapi.yml
- filename: fairmarkit-rfp-api-openapi.yml
  format: yaml
  label: Fairmarkit RFP API
  slug: fairmarkit-rfp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-rfp-api-openapi.yml
- filename: fairmarkit-rfq-api-openapi.yml
  format: yaml
  label: Fairmarkit RFQ API
  slug: fairmarkit-rfq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-rfq-api-openapi.yml
- filename: fairmarkit-schema-api-openapi.yml
  format: yaml
  label: Fairmarkit Schema API
  slug: fairmarkit-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-schema-api-openapi.yml
- filename: fairmarkit-supplier-api-openapi.yml
  format: yaml
  label: Fairmarkit Supplier API
  slug: fairmarkit-supplier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-supplier-api-openapi.yml
- filename: fairmarkit-uom-api-openapi.yml
  format: yaml
  label: Fairmarkit UOM API
  slug: fairmarkit-uom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-uom-api-openapi.yml
- filename: fairmarkit-user-profiles-api-openapi.yml
  format: yaml
  label: Fairmarkit User Profiles API
  slug: fairmarkit-user-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fairmarkit/openapi/fairmarkit-user-profiles-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are registering on behalf of a company, You represent and warrant that you have authority to bind such company to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive analysis or benchmarking
    text: access or use any Feature in a manner intended to enable or assist any competitive analysis, benchmarking, or development of competing services
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
name: Fairmarkit
provenance_date: '2026-11-09'
provider_name: Fairmarkit
provider_slug: fairmarkit
slug: fairmarkit-eligibility
source_date: '2026-11-09'
source_filename: fairmarkit-eligibility.yml
source_heading: Eligibility
source_page: https://www.fairmarkit.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fairmarkit\naid: fairmarkit\nurl: https://www.fairmarkit.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are registering on behalf of a company, You represent and warrant that you have authority to bind\n    such company to these Terms.\nrestricted_uses:\n- summary: Competitive analysis or benchmarking\n  text: access or use any Feature in a manner intended to enable or assist any competitive analysis, benchmarking,\n    or development of competing services\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fairmarkit/eligibility/fairmarkit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Fairmarkit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Procurement
- Sourcing
- Supply Chain
- Purchasing
- Suppliers
- RFQ
- RFP
- Spend Management
- Webhook
---
