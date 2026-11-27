---
api_specs:
- filename: wbiztool-com-account-api-openapi.yml
  format: yaml
  label: wbiztool-com Account API
  slug: wbiztool-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wbiztool-com/openapi/wbiztool-com-account-api-openapi.yml
- filename: wbiztool-com-media-api-openapi.yml
  format: yaml
  label: wbiztool-com Media API
  slug: wbiztool-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wbiztool-com/openapi/wbiztool-com-media-api-openapi.yml
- filename: wbiztool-com-messages-api-openapi.yml
  format: yaml
  label: wbiztool-com Messages API
  slug: wbiztool-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wbiztool-com/openapi/wbiztool-com-messages-api-openapi.yml
- filename: wbiztool-com-number-verification-api-openapi.yml
  format: yaml
  label: wbiztool-com Number verification API
  slug: wbiztool-com-number-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wbiztool-com/openapi/wbiztool-com-number-verification-api-openapi.yml
- filename: wbiztool-com-reminders-api-openapi.yml
  format: yaml
  label: wbiztool-com Reminders API
  slug: wbiztool-com-reminders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wbiztool-com/openapi/wbiztool-com-reminders-api-openapi.yml
- filename: wbiztool-com-whatsapp-numbers-api-openapi.yml
  format: yaml
  label: wbiztool-com WhatsApp numbers API
  slug: wbiztool-com-whatsapp-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wbiztool-com/openapi/wbiztool-com-whatsapp-numbers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: The services/projects are not available to minors under the age of 18
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: wbiztool-com
provenance_date: '2026-11-10'
provider_name: wbiztool-com
provider_slug: wbiztool-com
slug: wbiztool-com-eligibility
source_date: '2026-11-10'
source_filename: wbiztool-com-eligibility.yml
source_heading: Eligibility
source_page: https://wbiztool.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: wbiztool-com\naid: wbiztool-com\nurl: https://wbiztool.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any\
  \ illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The services/projects are not available to minors under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/wbiztool-com/eligibility/wbiztool-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from wbiztool-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- WhatsApp
- Messaging
- Automation
- Business
---
