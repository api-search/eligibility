---
api_specs:
- filename: commonelements-com-aggregates-and-compliance-api-openapi.yml
  format: yaml
  label: Common Elements Aggregates and compliance API
  slug: commonelements-com-aggregates-and-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-aggregates-and-compliance-api-openapi.yml
- filename: commonelements-com-association-resources-api-openapi.yml
  format: yaml
  label: Common Elements Association resources API
  slug: commonelements-com-association-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-association-resources-api-openapi.yml
- filename: commonelements-com-associations-api-openapi.yml
  format: yaml
  label: Common Elements Associations API
  slug: commonelements-com-associations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-associations-api-openapi.yml
- filename: commonelements-com-bulk-delivery-api-openapi.yml
  format: yaml
  label: Common Elements Bulk delivery API
  slug: commonelements-com-bulk-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-bulk-delivery-api-openapi.yml
- filename: commonelements-com-bulk-export-api-openapi.yml
  format: yaml
  label: Common Elements Bulk export API
  slug: commonelements-com-bulk-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-bulk-export-api-openapi.yml
- filename: commonelements-com-change-feed-api-openapi.yml
  format: yaml
  label: Common Elements Change feed API
  slug: commonelements-com-change-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-change-feed-api-openapi.yml
- filename: commonelements-com-cross-association-collections-api-openapi.yml
  format: yaml
  label: Common Elements Cross-association collections API
  slug: commonelements-com-cross-association-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-cross-association-collections-api-openapi.yml
- filename: commonelements-com-dataset-catalog-api-openapi.yml
  format: yaml
  label: Common Elements Dataset catalog API
  slug: commonelements-com-dataset-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-dataset-catalog-api-openapi.yml
- filename: commonelements-com-meta-api-openapi.yml
  format: yaml
  label: Common Elements Meta API
  slug: commonelements-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-meta-api-openapi.yml
- filename: commonelements-com-professionals-and-licenses-api-openapi.yml
  format: yaml
  label: Common Elements Professionals and licenses API
  slug: commonelements-com-professionals-and-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-professionals-and-licenses-api-openapi.yml
- filename: commonelements-com-statutes-api-openapi.yml
  format: yaml
  label: Common Elements Statutes API
  slug: commonelements-com-statutes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-statutes-api-openapi.yml
- filename: commonelements-com-vendors-api-openapi.yml
  format: yaml
  label: Common Elements Vendors API
  slug: commonelements-com-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commonelements-com/openapi/commonelements-com-vendors-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use Common Elements.
    value: '18'
  restricted_uses:
  - summary: Fair Credit Reporting Act screening
    text: Use directory or profile data for any purpose regulated by the Fair Credit Reporting Act, including tenant, credit, insurance, or employment screening.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Common Elements verifies certain credentials (LCAM, state-issued contractor licenses, attorney bar admissions, insurance licenses, organizational ownership).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Common Elements
provenance_date: '2026-11-09'
provider_name: Common Elements
provider_slug: commonelements-com
slug: commonelements-com-eligibility
source_date: '2026-11-09'
source_filename: commonelements-com-eligibility.yml
source_heading: Eligibility
source_page: https://commonelements.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Common Elements\naid: commonelements-com\nurl: https://commonelements.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fair Credit Reporting Act screening\n  text: Use directory or profile data for any purpose regulated by the Fair Credit Reporting Act, including tenant,\n    credit, insurance, or employment screening.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Common Elements verifies certain credentials (LCAM, state-issued contractor licenses, attorney bar admissions,\n    insurance\
  \ licenses, organizational ownership).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Common Elements.\n"
source_yaml_url: https://artifacts.apis.io/commonelements-com/eligibility/commonelements-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Common Elements's own page on 2026-11-09.
synthetic: false
tags:
- Company
- HOA
- Community Associations
- Real Estate
- PropTech
- Property Data
- Compliance
- Flood Risk
---
