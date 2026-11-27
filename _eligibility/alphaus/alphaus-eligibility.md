---
api_specs:
- filename: alphaus-admin-api-openapi.yml
  format: yaml
  label: Alphaus Admin API
  slug: alphaus-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-admin-api-openapi.yml
- filename: alphaus-billing-api-openapi.yml
  format: yaml
  label: Alphaus Billing API
  slug: alphaus-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-billing-api-openapi.yml
- filename: alphaus-cost-api-openapi.yml
  format: yaml
  label: Alphaus Cost API
  slug: alphaus-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-cost-api-openapi.yml
- filename: alphaus-cover-api-openapi.yml
  format: yaml
  label: Alphaus Cover API
  slug: alphaus-cover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-cover-api-openapi.yml
- filename: alphaus-flags-api-openapi.yml
  format: yaml
  label: Alphaus Flags API
  slug: alphaus-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-flags-api-openapi.yml
- filename: alphaus-flow-api-openapi.yml
  format: yaml
  label: Alphaus Flow API
  slug: alphaus-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-flow-api-openapi.yml
- filename: alphaus-guaranteedcommitments-api-openapi.yml
  format: yaml
  label: Alphaus GuaranteedCommitments API
  slug: alphaus-guaranteedcommitments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-guaranteedcommitments-api-openapi.yml
- filename: alphaus-iam-api-openapi.yml
  format: yaml
  label: Alphaus Iam API
  slug: alphaus-iam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-iam-api-openapi.yml
- filename: alphaus-luster-api-openapi.yml
  format: yaml
  label: Alphaus Luster API
  slug: alphaus-luster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-luster-api-openapi.yml
- filename: alphaus-operations-api-openapi.yml
  format: yaml
  label: Alphaus Operations API
  slug: alphaus-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-operations-api-openapi.yml
- filename: alphaus-organization-api-openapi.yml
  format: yaml
  label: Alphaus Organization API
  slug: alphaus-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-organization-api-openapi.yml
- filename: alphaus-preferences-api-openapi.yml
  format: yaml
  label: Alphaus Preferences API
  slug: alphaus-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-preferences-api-openapi.yml
- filename: alphaus-pricing-api-openapi.yml
  format: yaml
  label: Alphaus Pricing API
  slug: alphaus-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-pricing-api-openapi.yml
- filename: alphaus-prism-api-openapi.yml
  format: yaml
  label: Alphaus Prism API
  slug: alphaus-prism-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-prism-api-openapi.yml
- filename: alphaus-vortex-api-openapi.yml
  format: yaml
  label: Alphaus Vortex API
  slug: alphaus-vortex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-vortex-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When the Applicant for Registration is either a minor, adult ward, person under curatorship, or person under assistance and has not obtained the approval of its statutory agent, guardian, authorized assistant, or assistant;
    value: null
  restricted_uses:
  - summary: Competing services refused
    text: When the Applicant for Registration is operating, or cooperating with the operation of, a website or a service that is similar toor competes with the Service;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Company shall, in accordance with its internal standards, make decisions as to the registration of the Registration Requester who has applied for registration
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alphaus
provenance_date: '2026-11-09'
provider_name: Alphaus
provider_slug: alphaus
slug: alphaus-eligibility
source_date: '2026-11-09'
source_filename: alphaus-eligibility.yml
source_heading: Eligibility
source_page: https://www.alphaus.cloud/en/ripple-wave-terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alphaus\naid: alphaus\nurl: https://www.alphaus.cloud/en/ripple-wave-terms-of-services\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competing services refused\n  text: When the Applicant for Registration is operating, or cooperating with the operation of, a website or a service\n    that is similar toor competes with the Service;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Company shall, in accordance with its internal standards, make decisions as to the registration of the\n    Registration\
  \ Requester who has applied for registration\nminimum_age:\n  value: null\n  text: When the Applicant for Registration is either a minor, adult ward, person under curatorship, or person under\n    assistance and has not obtained the approval of its statutory agent, guardian, authorized assistant, or assistant;\n"
source_yaml_url: https://artifacts.apis.io/alphaus/eligibility/alphaus-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Alphaus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- FinOps
- Cloud Cost Management
- Cloud
- Billing
- Multi-Cloud
- Amazon Web Services
- Microsoft Azure
- GCP
- gRPC
- Cost Optimization
- Reseller Billing
---
