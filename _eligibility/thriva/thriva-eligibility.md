---
api_specs:
- filename: thriva-appointments-api-api-openapi.yml
  format: yaml
  label: Thriva Appointments API
  slug: thriva-appointments-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-appointments-api-api-openapi.yml
- filename: thriva-auth-api-api-openapi.yml
  format: yaml
  label: Thriva Auth API
  slug: thriva-auth-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-auth-api-api-openapi.yml
- filename: thriva-biomarkers-api-api-openapi.yml
  format: yaml
  label: Thriva Biomarkers API
  slug: thriva-biomarkers-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-biomarkers-api-api-openapi.yml
- filename: thriva-bulk-orders-api-api-openapi.yml
  format: yaml
  label: Thriva Bulk Orders API
  slug: thriva-bulk-orders-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-bulk-orders-api-api-openapi.yml
- filename: thriva-escalations-api-api-openapi.yml
  format: yaml
  label: Thriva Escalations API
  slug: thriva-escalations-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-escalations-api-api-openapi.yml
- filename: thriva-orders-api-api-openapi.yml
  format: yaml
  label: Thriva Orders API
  slug: thriva-orders-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-orders-api-api-openapi.yml
- filename: thriva-result-attachments-api-api-openapi.yml
  format: yaml
  label: Thriva Result attachments API
  slug: thriva-result-attachments-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-result-attachments-api-api-openapi.yml
- filename: thriva-results-api-api-openapi.yml
  format: yaml
  label: Thriva Results API
  slug: thriva-results-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-results-api-api-openapi.yml
- filename: thriva-tracking-api-api-openapi.yml
  format: yaml
  label: Thriva Tracking API
  slug: thriva-tracking-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-tracking-api-api-openapi.yml
- filename: thriva-users-api-api-openapi.yml
  format: yaml
  label: Thriva Users API
  slug: thriva-users-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thriva/openapi/thriva-users-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Ifyouareabusiness,theseTerms,itssubjectmatteranditsformation(andanynon-contractualdisputesorclaims)aregovernedbyEnglishlaw.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: no commercial or business purposes
    text: YouagreenottousetheSiteandanyservicesWeenableforanycommercialorbusinesspurposes
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
name: Thriva
provenance_date: '2026-11-10'
provider_name: Thriva
provider_slug: thriva
slug: thriva-eligibility
source_date: '2026-11-10'
source_filename: thriva-eligibility.yml
source_heading: Eligibility
source_page: https://s3-eu-west-1.amazonaws.com/thriva/legal/Website+Terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thriva\naid: thriva\nurl: https://s3-eu-west-1.amazonaws.com/thriva/legal/Website+Terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Ifyouareabusiness,theseTerms,itssubjectmatteranditsformation(andanynon-contractualdisputesorclaims)aregovernedbyEnglishlaw.\nrestricted_uses:\n- summary: no commercial or business purposes\n  text: YouagreenottousetheSiteandanyservicesWeenableforanycommercialorbusinesspurposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thriva/eligibility/thriva-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Thriva's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Diagnostics
- Blood Testing
- At-Home Testing
- Digital Health
- Lab Testing
- Webhook
- United Kingdom
---
