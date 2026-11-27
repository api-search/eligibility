---
api_specs:
- filename: wholechain-connect-api-openapi.yml
  format: yaml
  label: Wholechain Connect API
  slug: wholechain-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-connect-api-openapi.yml
- filename: wholechain-edi-api-openapi.yml
  format: yaml
  label: Wholechain Edi API
  slug: wholechain-edi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-edi-api-openapi.yml
- filename: wholechain-epcis-interface-api-openapi.yml
  format: yaml
  label: Wholechain EPCIS Interface API
  slug: wholechain-epcis-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-epcis-interface-api-openapi.yml
- filename: wholechain-epcis-legacy-interface-api-openapi.yml
  format: yaml
  label: Wholechain EPCIS Legacy Interface API
  slug: wholechain-epcis-legacy-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-epcis-legacy-interface-api-openapi.yml
- filename: wholechain-events-api-openapi.yml
  format: yaml
  label: Wholechain Events API
  slug: wholechain-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-events-api-openapi.yml
- filename: wholechain-externaloauth-api-openapi.yml
  format: yaml
  label: Wholechain External O Auth API
  slug: wholechain-externaloauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-externaloauth-api-openapi.yml
- filename: wholechain-health-api-openapi.yml
  format: yaml
  label: Wholechain Health API
  slug: wholechain-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wholechain/openapi/wholechain-health-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Customer ” means an entity, individual or Customer Agent who has accepted these Terms and Conditions to Access Wholechain’s Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: Wholechain’s direct competitors are prohibited from accessing Wholechain’s Services without the prior written consent of Wholechain.
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
name: Wholechain
provenance_date: '2026-11-10'
provider_name: Wholechain
provider_slug: wholechain
slug: wholechain-eligibility
source_date: '2026-11-10'
source_filename: wholechain-eligibility.yml
source_heading: Eligibility
source_page: https://wholechain.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wholechain\naid: wholechain\nurl: https://wholechain.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “ Customer ” means an entity, individual or Customer Agent who has accepted these Terms and Conditions to\n    Access Wholechain’s Services\nrestricted_uses:\n- summary: Direct competitors barred\n  text: Wholechain’s direct competitors are prohibited from accessing Wholechain’s Services without the prior written\n    consent of Wholechain.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wholechain/eligibility/wholechain-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Wholechain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Supply Chain
- Traceability
- Blockchain
- Food Safety
- Compliance
- GS1
- Logistics
---
