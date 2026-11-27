---
api_specs:
- filename: asoskill-com-authentication-api-openapi.yml
  format: yaml
  label: asoskill-com Authentication API
  slug: asoskill-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-authentication-api-openapi.yml
- filename: asoskill-com-billing-api-openapi.yml
  format: yaml
  label: asoskill-com Billing API
  slug: asoskill-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-billing-api-openapi.yml
- filename: asoskill-com-credits-api-openapi.yml
  format: yaml
  label: asoskill-com Credits API
  slug: asoskill-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-credits-api-openapi.yml
- filename: asoskill-com-data-api-openapi.yml
  format: yaml
  label: asoskill-com Data API
  slug: asoskill-com-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-data-api-openapi.yml
- filename: asoskill-com-mcp-api-openapi.yml
  format: yaml
  label: asoskill-com MCP API
  slug: asoskill-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-mcp-api-openapi.yml
- filename: asoskill-com-operations-api-openapi.yml
  format: yaml
  label: asoskill-com Operations API
  slug: asoskill-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-operations-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for an organization, you confirm that you have authority to accept these Terms for it.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Sensitive data in search terms
    text: Do not submit personal data, confidential information, or sensitive information as search terms unless you have a lawful basis and have determined that sending it to ASO Skill and the relevant upstream provider is appropriate.
  - summary: No implied endorsement
    text: You must not imply that your product is operated, approved, or endorsed by ASO Skill or Apple unless separately authorized.
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
name: asoskill-com
provenance_date: '2026-11-09'
provider_name: asoskill-com
provider_slug: asoskill-com
slug: asoskill-com-eligibility
source_date: '2026-11-09'
source_filename: asoskill-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.asoskill.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: asoskill-com\naid: asoskill-com\nurl: https://www.asoskill.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for an organization, you confirm that you have authority to accept these Terms for\n    it.\nrestricted_uses:\n- summary: Sensitive data in search terms\n  text: Do not submit personal data, confidential information, or sensitive information as search terms unless you\n    have a lawful basis and have determined that sending it to ASO Skill and the relevant upstream provider is appropriate.\n- summary:\
  \ No implied endorsement\n  text: You must not imply that your product is operated, approved, or endorsed by ASO Skill or Apple unless separately\n    authorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/asoskill-com/eligibility/asoskill-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from asoskill-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ASO
- App Store
- Data
---
