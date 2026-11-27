---
api_specs:
- filename: contactlint-com-openapi.json
  format: json
  label: ContactLint API
  slug: contactlint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-openapi.json
- filename: contactlint-com-demo-api-openapi.yml
  format: yaml
  label: contactlint-com Demo API
  slug: contactlint-com-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-demo-api-openapi.yml
- filename: contactlint-com-demo-preview-api-openapi.yml
  format: yaml
  label: contactlint-com Demo Preview API
  slug: contactlint-com-demo-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-demo-preview-api-openapi.yml
- filename: contactlint-com-demo-preview-rotation-api-openapi.yml
  format: yaml
  label: contactlint-com Demo Preview Rotation API
  slug: contactlint-com-demo-preview-rotation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-demo-preview-rotation-api-openapi.yml
- filename: contactlint-com-domain-api-openapi.yml
  format: yaml
  label: contactlint-com Domain API
  slug: contactlint-com-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-domain-api-openapi.yml
- filename: contactlint-com-go-api-openapi.yml
  format: yaml
  label: contactlint-com Go API
  slug: contactlint-com-go-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-go-api-openapi.yml
- filename: contactlint-com-health-api-openapi.yml
  format: yaml
  label: contactlint-com Health API
  slug: contactlint-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-health-api-openapi.yml
- filename: contactlint-com-lookup-api-openapi.yml
  format: yaml
  label: contactlint-com Lookup API
  slug: contactlint-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-lookup-api-openapi.yml
- filename: contactlint-com-metrics-api-openapi.yml
  format: yaml
  label: contactlint-com Metrics API
  slug: contactlint-com-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-metrics-api-openapi.yml
- filename: contactlint-com-monitor-api-openapi.yml
  format: yaml
  label: contactlint-com Monitor API
  slug: contactlint-com-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-monitor-api-openapi.yml
- filename: contactlint-com-payment-change-check-api-openapi.yml
  format: yaml
  label: contactlint-com Payment Change Check API
  slug: contactlint-com-payment-change-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-payment-change-check-api-openapi.yml
- filename: contactlint-com-report-api-openapi.yml
  format: yaml
  label: contactlint-com Report API
  slug: contactlint-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-report-api-openapi.yml
- filename: contactlint-com-reports-api-openapi.yml
  format: yaml
  label: contactlint-com Reports API
  slug: contactlint-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-reports-api-openapi.yml
- filename: contactlint-com-robots-txt-api-openapi.yml
  format: yaml
  label: contactlint-com Robots.txt API
  slug: contactlint-com-robots-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-robots-txt-api-openapi.yml
- filename: contactlint-com-sitemap-xml-api-openapi.yml
  format: yaml
  label: contactlint-com Sitemap.xml API
  slug: contactlint-com-sitemap-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-sitemap-xml-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for a company, you confirm you can bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive unrelated data
    text: Send data you are not allowed to share, such as sensitive data unrelated to contact validation.
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
name: contactlint-com
provenance_date: '2026-11-09'
provider_name: contactlint-com
provider_slug: contactlint-com
slug: contactlint-com-eligibility
source_date: '2026-11-09'
source_filename: contactlint-com-eligibility.yml
source_heading: Eligibility
source_page: https://contactlint.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: contactlint-com\naid: contactlint-com\nurl: https://contactlint.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a company, you confirm you can bind that company.\nrestricted_uses:\n- summary: Sensitive unrelated data\n  text: Send data you are not allowed to share, such as sensitive data unrelated to contact validation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/contactlint-com/eligibility/contactlint-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from contactlint-com's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Phone Validation
- MCP
- Developer Tools
- Company
---
