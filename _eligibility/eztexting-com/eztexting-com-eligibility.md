---
api_specs:
- filename: eztexting-com-blocks-api-openapi.yml
  format: yaml
  label: EZ Texting Blocks API
  slug: eztexting-com-blocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-blocks-api-openapi.yml
- filename: eztexting-com-contact-fields-api-openapi.yml
  format: yaml
  label: EZ Texting Contact Fields API
  slug: eztexting-com-contact-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-contact-fields-api-openapi.yml
- filename: eztexting-com-contact-groups-api-openapi.yml
  format: yaml
  label: EZ Texting Contact Groups API
  slug: eztexting-com-contact-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-contact-groups-api-openapi.yml
- filename: eztexting-com-contacts-api-openapi.yml
  format: yaml
  label: EZ Texting Contacts API
  slug: eztexting-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-contacts-api-openapi.yml
- filename: eztexting-com-conversations-api-openapi.yml
  format: yaml
  label: EZ Texting Conversations API
  slug: eztexting-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-conversations-api-openapi.yml
- filename: eztexting-com-credits-api-openapi.yml
  format: yaml
  label: EZ Texting Credits API
  slug: eztexting-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-credits-api-openapi.yml
- filename: eztexting-com-keywords-api-openapi.yml
  format: yaml
  label: EZ Texting Keywords API
  slug: eztexting-com-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-keywords-api-openapi.yml
- filename: eztexting-com-media-files-api-openapi.yml
  format: yaml
  label: EZ Texting Media Files API
  slug: eztexting-com-media-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-media-files-api-openapi.yml
- filename: eztexting-com-message-reports-api-openapi.yml
  format: yaml
  label: EZ Texting Message Reports API
  slug: eztexting-com-message-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-message-reports-api-openapi.yml
- filename: eztexting-com-message-templates-api-openapi.yml
  format: yaml
  label: EZ Texting Message Templates API
  slug: eztexting-com-message-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-message-templates-api-openapi.yml
- filename: eztexting-com-messages-api-openapi.yml
  format: yaml
  label: EZ Texting Messages API
  slug: eztexting-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-messages-api-openapi.yml
- filename: eztexting-com-tokens-api-openapi.yml
  format: yaml
  label: EZ Texting Tokens API
  slug: eztexting-com-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-tokens-api-openapi.yml
- filename: eztexting-com-webhooks-api-openapi.yml
  format: yaml
  label: EZ Texting Webhooks API
  slug: eztexting-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eztexting-com/openapi/eztexting-com-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services may or may not be available in all countries or regions of the world.
  entity_types:
  - text: Our services are for commercial/business use and are not for personal or household use.
    type: business
  minimum_age:
    text: By accessing one of our Services, you represent that you have reached the age of majority for where you live or, if you are under the age of majority (a “Minor”), that you have received your parent’s or legal guardian’s permission
    value: null
  restricted_uses:
  - summary: Emergency services access
    text: You will not attempt to use our Services to access or allow access to Emergency Services.
  - summary: Loan promotion restriction
    text: Messages promoting loans are prohibited unless the sender is a direct lender licensed to operate in the applicable jurisdiction.
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
name: EZ Texting
provenance_date: '2026-11-09'
provider_name: EZ Texting
provider_slug: eztexting-com
slug: eztexting-com-eligibility
source_date: '2026-11-09'
source_filename: eztexting-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.eztexting.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EZ Texting\naid: eztexting-com\nurl: https://www.eztexting.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Services may or may not be available in all countries or regions of the world.\nentity_types:\n- type: business\n  text: Our services are for commercial/business use and are not for personal or household use.\nrestricted_uses:\n- summary: Emergency services access\n  text: You will not attempt to use our Services to access or allow access to Emergency Services.\n- summary: Loan promotion restriction\n  text: Messages promoting loans are prohibited\
  \ unless the sender is a direct lender licensed to operate in the\n    applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By accessing one of our Services, you represent that you have reached the age of majority for where you\n    live or, if you are under the age of majority (a “Minor”), that you have received your parent’s or legal guardian’s\n    permission\n"
source_yaml_url: https://artifacts.apis.io/eztexting-com/eligibility/eztexting-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from EZ Texting's own page on 2026-11-09.
synthetic: false
tags:
- SMS
- Marketing
- Communications
- Text Messaging
---
