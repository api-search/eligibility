---
api_specs:
- filename: joinblink-com-access-api-openapi.yml
  format: yaml
  label: Blink Access API
  slug: joinblink-com-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-access-api-openapi.yml
- filename: joinblink-com-chats-api-openapi.yml
  format: yaml
  label: Blink Chats API
  slug: joinblink-com-chats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-chats-api-openapi.yml
- filename: joinblink-com-feed-api-openapi.yml
  format: yaml
  label: Blink Feed API
  slug: joinblink-com-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-feed-api-openapi.yml
- filename: joinblink-com-forms-api-openapi.yml
  format: yaml
  label: Blink Forms API
  slug: joinblink-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-forms-api-openapi.yml
- filename: joinblink-com-group-api-openapi.yml
  format: yaml
  label: Blink Group API
  slug: joinblink-com-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-group-api-openapi.yml
- filename: joinblink-com-linked-account-api-openapi.yml
  format: yaml
  label: Blink Linked Account API
  slug: joinblink-com-linked-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-linked-account-api-openapi.yml
- filename: joinblink-com-linked-accounts-api-openapi.yml
  format: yaml
  label: Blink Linked Accounts API
  slug: joinblink-com-linked-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-linked-accounts-api-openapi.yml
- filename: joinblink-com-members-api-openapi.yml
  format: yaml
  label: Blink Members API
  slug: joinblink-com-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-members-api-openapi.yml
- filename: joinblink-com-messages-api-openapi.yml
  format: yaml
  label: Blink Messages API
  slug: joinblink-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-messages-api-openapi.yml
- filename: joinblink-com-user-api-openapi.yml
  format: yaml
  label: Blink User API
  slug: joinblink-com-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-user-api-openapi.yml
- filename: joinblink-com-service-provider-config-api-openapi.yml
  format: yaml
  label: Blink Service Provider Config API
  slug: joinblink-com-service-provider-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinblink-com/openapi/joinblink-com-service-provider-config-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity you warrant that you have authority to bind such company or other legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive use
    text: You must not use the App in any unlawful manner, for any unlawful purpose, or in any manner inconsistent with these Terms, or act fraudulently or maliciously.
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
name: Blink
provenance_date: '2026-11-09'
provider_name: Blink
provider_slug: joinblink-com
slug: joinblink-com-eligibility
source_date: '2026-11-09'
source_filename: joinblink-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinblink.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blink\naid: joinblink-com\nurl: https://www.joinblink.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity you warrant that you have\n    authority to bind such company or other legal entity.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: You must not use the App in any unlawful manner, for any unlawful purpose, or in any manner inconsistent\n    with these Terms, or act fraudulently or maliciously.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/joinblink-com/eligibility/joinblink-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Blink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employee Experience
- MobileFirst
- Frontline Workers
- Communications
---
