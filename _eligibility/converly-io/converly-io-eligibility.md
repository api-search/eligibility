---
api_specs:
- filename: converly-io-action-types-api-openapi.yml
  format: yaml
  label: Converly Action Types API
  slug: converly-io-action-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-action-types-api-openapi.yml
- filename: converly-io-billing-api-openapi.yml
  format: yaml
  label: Converly Billing API
  slug: converly-io-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-billing-api-openapi.yml
- filename: converly-io-destination-types-api-openapi.yml
  format: yaml
  label: Converly Destination Types API
  slug: converly-io-destination-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-destination-types-api-openapi.yml
- filename: converly-io-destinations-api-openapi.yml
  format: yaml
  label: Converly Destinations API
  slug: converly-io-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-destinations-api-openapi.yml
- filename: converly-io-events-api-openapi.yml
  format: yaml
  label: Converly Events API
  slug: converly-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-events-api-openapi.yml
- filename: converly-io-flows-api-openapi.yml
  format: yaml
  label: Converly Flows API
  slug: converly-io-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-flows-api-openapi.yml
- filename: converly-io-handoffs-api-openapi.yml
  format: yaml
  label: Converly Handoffs API
  slug: converly-io-handoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-handoffs-api-openapi.yml
- filename: converly-io-invoices-api-openapi.yml
  format: yaml
  label: Converly Invoices API
  slug: converly-io-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-invoices-api-openapi.yml
- filename: converly-io-plans-api-openapi.yml
  format: yaml
  label: Converly Plans API
  slug: converly-io-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-plans-api-openapi.yml
- filename: converly-io-signup-api-openapi.yml
  format: yaml
  label: Converly Signup API
  slug: converly-io-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-signup-api-openapi.yml
- filename: converly-io-site-integrations-api-openapi.yml
  format: yaml
  label: Converly Site Integrations API
  slug: converly-io-site-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-site-integrations-api-openapi.yml
- filename: converly-io-sites-api-openapi.yml
  format: yaml
  label: Converly Sites API
  slug: converly-io-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-sites-api-openapi.yml
- filename: converly-io-subscription-api-openapi.yml
  format: yaml
  label: Converly Subscription API
  slug: converly-io-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-subscription-api-openapi.yml
- filename: converly-io-test-event-api-openapi.yml
  format: yaml
  label: Converly Test Event API
  slug: converly-io-test-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-test-event-api-openapi.yml
- filename: converly-io-trigger-types-api-openapi.yml
  format: yaml
  label: Converly Trigger Types API
  slug: converly-io-trigger-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-trigger-types-api-openapi.yml
- filename: converly-io-usage-api-openapi.yml
  format: yaml
  label: Converly Usage API
  slug: converly-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are provided from the United States.
  entity_types:
  - text: If you are using the Services on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: You must comply with all domestic and international export laws and regulations that apply to your use of the Services, such as software.
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
name: Converly
provenance_date: '2026-11-09'
provider_name: Converly
provider_slug: converly-io
slug: converly-io-eligibility
source_date: '2026-11-09'
source_filename: converly-io-eligibility.yml
source_heading: Eligibility
source_page: https://converly.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Converly\naid: converly-io\nurl: https://converly.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are provided from the United States.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you are agreeing to these Terms for that organization\nrestricted_uses:\n- summary: Export law compliance\n  text: You must comply with all domestic and international export laws and regulations that apply to your use of\n    the Services, such as software.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/converly-io/eligibility/converly-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Converly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Conversion Tracking
- Marketing
- Advertising
- Analytics
- MCP
- REST API
---
