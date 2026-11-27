---
api_specs:
- filename: didlogic-com-account-balance-api-openapi.yml
  format: yaml
  label: DID Logic Account Balance API
  slug: didlogic-com-account-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-account-balance-api-openapi.yml
- filename: didlogic-com-api-access-api-openapi.yml
  format: yaml
  label: DID Logic API Access API
  slug: didlogic-com-api-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-api-access-api-openapi.yml
- filename: didlogic-com-calls-api-openapi.yml
  format: yaml
  label: DID Logic Calls API
  slug: didlogic-com-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-calls-api-openapi.yml
- filename: didlogic-com-click2call-api-openapi.yml
  format: yaml
  label: DID Logic Click2 Call API
  slug: didlogic-com-click2call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-click2call-api-openapi.yml
- filename: didlogic-com-hlr-lookups-api-openapi.yml
  format: yaml
  label: DID Logic HLR Lookups API
  slug: didlogic-com-hlr-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-hlr-lookups-api-openapi.yml
- filename: didlogic-com-identities-api-openapi.yml
  format: yaml
  label: DID Logic Identities API
  slug: didlogic-com-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-identities-api-openapi.yml
- filename: didlogic-com-inbound-destinations-api-openapi.yml
  format: yaml
  label: DID Logic Inbound Destinations API
  slug: didlogic-com-inbound-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-inbound-destinations-api-openapi.yml
- filename: didlogic-com-kyc-documents-api-openapi.yml
  format: yaml
  label: DID Logic KYC Documents API
  slug: didlogic-com-kyc-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-kyc-documents-api-openapi.yml
- filename: didlogic-com-numbers-inventory-api-openapi.yml
  format: yaml
  label: DID Logic Numbers & Inventory API
  slug: didlogic-com-numbers-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-numbers-inventory-api-openapi.yml
- filename: didlogic-com-purchases-api-openapi.yml
  format: yaml
  label: DID Logic Purchases API
  slug: didlogic-com-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-purchases-api-openapi.yml
- filename: didlogic-com-reports-api-openapi.yml
  format: yaml
  label: DID Logic Reports API
  slug: didlogic-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-reports-api-openapi.yml
- filename: didlogic-com-risk-checks-api-openapi.yml
  format: yaml
  label: DID Logic Risk Checks API
  slug: didlogic-com-risk-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-risk-checks-api-openapi.yml
- filename: didlogic-com-sip-accounts-api-openapi.yml
  format: yaml
  label: DID Logic SIP Accounts API
  slug: didlogic-com-sip-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-sip-accounts-api-openapi.yml
- filename: didlogic-com-sms-api-openapi.yml
  format: yaml
  label: DID Logic SMS API
  slug: didlogic-com-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/didlogic-com/openapi/didlogic-com-sms-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - IN
    - NP
    - PK
    - LK
    - AL
    - DZ
    - TN
    - MA
    - EG
    - BD
    served: []
    text: Service is not available in India, Nepal, Pakistan, Sri-Lanka, Albania, Autonomous Province of Kosovo, Algeria, Tunisia, Morocco, Egypt and Bangladesh.
  entity_types:
  - text: Selling DID numbers is only available to facilities-based carriers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Mass, predictive or telemarketing dialing
    text: The Exchange Platform or any Services provided by Provider under these TOS may not be used for any type of mass dialing, predictive dialing, telemarketing or any other automated list dialing.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IN
- NP
- PK
- LK
- AL
- DZ
- TN
- MA
- EG
- BD
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DID Logic
provenance_date: '2026-11-09'
provider_name: DID Logic
provider_slug: didlogic-com
slug: didlogic-com-eligibility
source_date: '2026-11-09'
source_filename: didlogic-com-eligibility.yml
source_heading: Eligibility
source_page: https://didlogic.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DID Logic\naid: didlogic-com\nurl: https://didlogic.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - IN\n  - NP\n  - PK\n  - LK\n  - AL\n  - DZ\n  - TN\n  - MA\n  - EG\n  - BD\n  text: Service is not available in India, Nepal, Pakistan, Sri-Lanka, Albania, Autonomous Province of Kosovo, Algeria,\n    Tunisia, Morocco, Egypt and Bangladesh.\nentity_types:\n- type: business\n  text: Selling DID numbers is only available to facilities-based carriers.\nrestricted_uses:\n- summary: Mass, predictive or telemarketing dialing\n  text: The Exchange Platform\
  \ or any Services provided by Provider under these TOS may not be used for any type\n    of mass dialing, predictive dialing, telemarketing or any other automated list dialing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/didlogic-com/eligibility/didlogic-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from DID Logic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telecommunications
- VoIP
- SIP Trunking
- DID Numbers
- SMS
- Voice
- MCP
---
