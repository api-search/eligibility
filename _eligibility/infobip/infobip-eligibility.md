---
api_specs:
- filename: infobip-ai-hub-api-openapi.yml
  format: yaml
  label: Infobip AI Hub API
  slug: infobip-ai-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-ai-hub-api-openapi.yml
- filename: infobip-channels-api-openapi.yml
  format: yaml
  label: Infobip Channels API
  slug: infobip-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-channels-api-openapi.yml
- filename: infobip-connectivity-api-openapi.yml
  format: yaml
  label: Infobip Connectivity API
  slug: infobip-connectivity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-connectivity-api-openapi.yml
- filename: infobip-customer-engagement-api-openapi.yml
  format: yaml
  label: Infobip Customer Engagement API
  slug: infobip-customer-engagement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-customer-engagement-api-openapi.yml
- filename: infobip-platform-api-openapi.yml
  format: yaml
  label: Infobip Platform API
  slug: infobip-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-platform-api-openapi.yml
- filename: infobip-tools-api-openapi.yml
  format: yaml
  label: Infobip Tools API
  slug: infobip-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-tools-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You accept these Terms of use of Our Service on behalf of Your employer or another person, You confirm that You have the consent of Your employer or that person to act on their behalf.
    type: business
  minimum_age:
    text: You are not eligible to accept these Terms or use Our Services if You are not of legal age to form a binding contract with Us or if You are barred by law to use Our Services.
    value: legal age
  restricted_uses:
  - summary: Marketing without consent
    text: Use the Services or permit the Services to be used to send Chargeable Events to any end-user for marketing purposes without that end-user’s explicit request for, or prior consent, to receiving them.
  - summary: South Africa messaging code
    text: CLIENT represents and warrants to INFOBIP that it shall, when using the INFOBIP Services in order to reach end-users in South Africa, comply with the Wireless Application Service Providers Association’s (WASPA) Code of Conduct
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
name: Infobip
provenance_date: '2026-11-09'
provider_name: Infobip
provider_slug: infobip
slug: infobip-eligibility
source_date: '2026-11-09'
source_filename: infobip-eligibility.yml
source_heading: Eligibility
source_page: https://www.infobip.com/policies/service-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infobip\naid: infobip\nurl: https://www.infobip.com/policies/service-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You accept these Terms of use of Our Service on behalf of Your employer or another person, You confirm\n    that You have the consent of Your employer or that person to act on their behalf.\nrestricted_uses:\n- summary: Marketing without consent\n  text: Use the Services or permit the Services to be used to send Chargeable Events to any end-user for marketing\n    purposes without that end-user’s explicit\
  \ request for, or prior consent, to receiving them.\n- summary: South Africa messaging code\n  text: CLIENT represents and warrants to INFOBIP that it shall, when using the INFOBIP Services in order to reach\n    end-users in South Africa, comply with the Wireless Application Service Providers Association’s (WASPA) Code\n    of Conduct\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You are not eligible to accept these Terms or use Our Services if You are not of legal age to form a binding\n    contract with Us or if You are barred by law to use Our Services.\n"
source_yaml_url: https://artifacts.apis.io/infobip/eligibility/infobip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Infobip's own page on 2026-11-09.
synthetic: false
tags:
- Telecommunications
- Croatia
- CPaaS
- Messaging
- SMS
- Voice
- RCS
- WhatsApp
- Email
- Network APIs
- CAMARA
- Open Gateway
- Identity Verification
- SIM Swap
- Number Verification
- Omnichannel
- Aggregator
- Customer Engagement
- Communications
---
