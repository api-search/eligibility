---
api_specs:
- filename: ibanforge-api-keys-api-openapi.yml
  format: yaml
  label: IBANforge API Keys API
  slug: ibanforge-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-api-keys-api-openapi.yml
- filename: ibanforge-bic-api-openapi.yml
  format: yaml
  label: IBANforge BIC API
  slug: ibanforge-bic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-bic-api-openapi.yml
- filename: ibanforge-compliance-api-openapi.yml
  format: yaml
  label: IBANforge Compliance API
  slug: ibanforge-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-compliance-api-openapi.yml
- filename: ibanforge-credits-api-openapi.yml
  format: yaml
  label: IBANforge Credits API
  slug: ibanforge-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-credits-api-openapi.yml
- filename: ibanforge-free-api-openapi.yml
  format: yaml
  label: IBANforge Free API
  slug: ibanforge-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-free-api-openapi.yml
- filename: ibanforge-iban-api-openapi.yml
  format: yaml
  label: IBANforge IBAN API
  slug: ibanforge-iban-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-iban-api-openapi.yml
- filename: ibanforge-mcp-api-openapi.yml
  format: yaml
  label: IBANforge MCP API
  slug: ibanforge-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-mcp-api-openapi.yml
- filename: ibanforge-swiss-clearing-api-openapi.yml
  format: yaml
  label: IBANforge Swiss Clearing API
  slug: ibanforge-swiss-clearing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-swiss-clearing-api-openapi.yml
- filename: ibanforge-account-api-openapi.yml
  format: yaml
  label: IBANforge Account API
  slug: ibanforge-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-account-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'IBANforge is built for, and sold to, businesses and professionals: companies, self-employed people, and developers working for a business.'
    type: business
  - text: self-employed people
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sanctions/AML law violations
    text: (b) use the Service to violate sanctions, AML or data-protection law
  - summary: Not regulated compliance opinion
    text: (d) misrepresent IBANforge results as a regulated compliance opinion
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A free API key is issued on request and requires no e-mail address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: IBANforge
provenance_date: '2026-11-09'
provider_name: IBANforge
provider_slug: ibanforge
slug: ibanforge-eligibility
source_date: '2026-11-09'
source_filename: ibanforge-eligibility.yml
source_heading: Eligibility
source_page: https://ibanforge.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IBANforge\naid: ibanforge\nurl: https://ibanforge.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'IBANforge is built for, and sold to, businesses and professionals: companies, self-employed people, and\n    developers working for a business.'\n- type: individual\n  text: self-employed people\nrestricted_uses:\n- summary: No sanctions/AML law violations\n  text: (b) use the Service to violate sanctions, AML or data-protection law\n- summary: Not regulated compliance opinion\n  text: (d) misrepresent IBANforge results\
  \ as a regulated compliance opinion\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A free API key is issued on request and requires no e-mail address\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ibanforge/eligibility/ibanforge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from IBANforge's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banking
- Compliance
- MCP
- A2A
---
