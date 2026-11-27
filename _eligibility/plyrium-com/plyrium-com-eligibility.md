---
api_specs:
- filename: plyrium-com-discovery-api-openapi.yml
  format: yaml
  label: Plyrium Discovery API
  slug: plyrium-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plyrium-com/openapi/plyrium-com-discovery-api-openapi.yml
- filename: plyrium-com-purchase-api-openapi.yml
  format: yaml
  label: Plyrium Purchase API
  slug: plyrium-com-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plyrium-com/openapi/plyrium-com-purchase-api-openapi.yml
- filename: plyrium-com-verification-api-openapi.yml
  format: yaml
  label: Plyrium Verification API
  slug: plyrium-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plyrium-com/openapi/plyrium-com-verification-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Built in Coolidge, Arizona · Serving U.S. + Canada
  entity_types:
  - text: If you are creating an account on behalf of a business, you represent that you have authority to bind that business to these Terms.
    type: business
  - text: You must be at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or non-consented outbound calls
    text: Make outbound calls or send messages to numbers for which you have not collected the consent required by Section 5
  - summary: Deceiving callers about AI nature
    text: Use the AI Voice Receptionist to deceive callers about its AI nature when directly asked
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
name: Plyrium
provenance_date: '2026-11-10'
provider_name: Plyrium
provider_slug: plyrium-com
slug: plyrium-com-eligibility
source_date: '2026-11-10'
source_filename: plyrium-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.plyrium.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plyrium\naid: plyrium-com\nurl: https://www.plyrium.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Built in Coolidge, Arizona · Serving U.S. + Canada\nentity_types:\n- type: business\n  text: If you are creating an account on behalf of a business, you represent that you have authority to bind that\n    business to these Terms.\n- type: individual\n  text: You must be at least 18 years old.\nrestricted_uses:\n- summary: Unlawful or non-consented outbound calls\n  text: Make outbound calls or send messages to numbers for which you have not collected the consent\
  \ required by\n    Section 5\n- summary: Deceiving callers about AI nature\n  text: Use the AI Voice Receptionist to deceive callers about its AI nature when directly asked\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/plyrium-com/eligibility/plyrium-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Plyrium's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agent Skills
- Supply Chain Security
- Software Provenance
- x402
- Agentic Commerce
- A2A
- MCP
- Field Service Management
- Home Services
---
