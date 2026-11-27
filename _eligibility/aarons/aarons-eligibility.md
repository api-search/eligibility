---
api_specs:
- filename: aarons-authorizesession-api-openapi.yml
  format: yaml
  label: Aaron's Authorize Session API
  slug: aarons-authorizesession-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-authorizesession-api-openapi.yml
- filename: aarons-autopaycustomerretry-api-openapi.yml
  format: yaml
  label: Aaron's Auto Pay Customer Retry API
  slug: aarons-autopaycustomerretry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-autopaycustomerretry-api-openapi.yml
- filename: aarons-createtoken-api-openapi.yml
  format: yaml
  label: Aaron's Create Token API
  slug: aarons-createtoken-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-createtoken-api-openapi.yml
- filename: aarons-fiservpostback-api-openapi.yml
  format: yaml
  label: Aaron's Fiserv Postback API
  slug: aarons-fiservpostback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-fiservpostback-api-openapi.yml
- filename: aarons-memorybearertoken-api-openapi.yml
  format: yaml
  label: Aaron's Memory Bearer Token API
  slug: aarons-memorybearertoken-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-memorybearertoken-api-openapi.yml
- filename: aarons-memorytokenguid-api-openapi.yml
  format: yaml
  label: Aaron's Memory Token Guid API
  slug: aarons-memorytokenguid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-memorytokenguid-api-openapi.yml
- filename: aarons-ping-api-openapi.yml
  format: yaml
  label: Aaron's Ping API
  slug: aarons-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-ping-api-openapi.yml
- filename: aarons-repayauthpostback-api-openapi.yml
  format: yaml
  label: Aaron's Repay Auth Postback API
  slug: aarons-repayauthpostback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-repayauthpostback-api-openapi.yml
- filename: aarons-repaycardvaultpostback-api-openapi.yml
  format: yaml
  label: Aaron's Repay Card Vault Postback API
  slug: aarons-repaycardvaultpostback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-repaycardvaultpostback-api-openapi.yml
- filename: aarons-savedeviceintelligence-api-openapi.yml
  format: yaml
  label: Aaron's Save Device Intelligence API
  slug: aarons-savedeviceintelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-savedeviceintelligence-api-openapi.yml
- filename: aarons-savetoken-api-openapi.yml
  format: yaml
  label: Aaron's Save Token API
  slug: aarons-savetoken-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-savetoken-api-openapi.yml
- filename: aarons-updatecustomerretrynotification-api-openapi.yml
  format: yaml
  label: Aaron's Update Customer Retry Notification API
  slug: aarons-updatecustomerretrynotification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-updatecustomerretrynotification-api-openapi.yml
- filename: aarons-create-session-api-openapi.yml
  format: yaml
  label: Aaron's Create Session API
  slug: aarons-create-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-create-session-api-openapi.yml
- filename: aarons-customer-data-api-openapi.yml
  format: yaml
  label: Aaron's CUSTOMER DATA API
  slug: aarons-customer-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aarons/openapi/aarons-customer-data-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: (iii) represent that you are 18 or older
    type: individual
  minimum_age:
    text: (iii) represent that you are 18 or older
    value: '18'
  restricted_uses:
  - summary: No sales or services to children
    text: Aaron's does not sell or lease products or provide services to children.
  - summary: Sanctioned persons
    text: You may not use any of the Aaron's Services if you are the subject of U.S. sanctions
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
name: Aaron's
provenance_date: '2026-11-09'
provider_name: Aaron's
provider_slug: aarons
slug: aarons-eligibility
source_date: '2026-11-09'
source_filename: aarons-eligibility.yml
source_heading: Eligibility
source_page: https://www.aarons.com/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aaron's\naid: aarons\nurl: https://www.aarons.com/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: (iii) represent that you are 18 or older\nrestricted_uses:\n- summary: No sales or services to children\n  text: Aaron's does not sell or lease products or provide services to children.\n- summary: Sanctioned persons\n  text: You may not use any of the Aaron's Services if you are the subject of U.S. sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: (iii) represent that you are 18 or older\n"
source_yaml_url: https://artifacts.apis.io/aarons/eligibility/aarons-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aaron's's own page on 2026-11-09.
synthetic: false
tags:
- Lease-to-Own
- Retail
- Furniture
- Electronics
- Appliances
- Consumer Finance
- Fortune 1000
---
