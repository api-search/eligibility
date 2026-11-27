---
api_specs:
- filename: campfiresms-com-auth-api-openapi.yml
  format: yaml
  label: Campfire SMS Auth API
  slug: campfiresms-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-auth-api-openapi.yml
- filename: campfiresms-com-bridges-api-openapi.yml
  format: yaml
  label: Campfire SMS Bridges API
  slug: campfiresms-com-bridges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-bridges-api-openapi.yml
- filename: campfiresms-com-credential-api-openapi.yml
  format: yaml
  label: Campfire SMS Credential API
  slug: campfiresms-com-credential-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-credential-api-openapi.yml
- filename: campfiresms-com-enrollment-api-openapi.yml
  format: yaml
  label: Campfire SMS Enrollment API
  slug: campfiresms-com-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-enrollment-api-openapi.yml
- filename: campfiresms-com-health-api-openapi.yml
  format: yaml
  label: Campfire SMS Health API
  slug: campfiresms-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-health-api-openapi.yml
- filename: campfiresms-com-installations-api-openapi.yml
  format: yaml
  label: Campfire SMS Installations API
  slug: campfiresms-com-installations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-installations-api-openapi.yml
- filename: campfiresms-com-join-api-openapi.yml
  format: yaml
  label: Campfire SMS Join API
  slug: campfiresms-com-join-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-join-api-openapi.yml
- filename: campfiresms-com-login-api-openapi.yml
  format: yaml
  label: Campfire SMS Login API
  slug: campfiresms-com-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-login-api-openapi.yml
- filename: campfiresms-com-public-api-openapi.yml
  format: yaml
  label: Campfire SMS Public API
  slug: campfiresms-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-public-api-openapi.yml
- filename: campfiresms-com-setup-api-openapi.yml
  format: yaml
  label: Campfire SMS Setup API
  slug: campfiresms-com-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-setup-api-openapi.yml
- filename: campfiresms-com-webhooks-api-openapi.yml
  format: yaml
  label: Campfire SMS Webhooks API
  slug: campfiresms-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old and authorized to use the mobile number you enroll.
    value: '13'
  restricted_uses:
  - summary: Sexually explicit, hate speech, or carrier-prohibited content
    text: You also agree not to send, or have your agent send, sexually explicit content, hate speech, or other content that wireless carriers prohibit on business messaging.
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
name: Campfire SMS
provenance_date: '2026-11-09'
provider_name: Campfire SMS
provider_slug: campfiresms-com
slug: campfiresms-com-eligibility
source_date: '2026-11-09'
source_filename: campfiresms-com-eligibility.yml
source_heading: Eligibility
source_page: https://campfiresms.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Campfire SMS\naid: campfiresms-com\nurl: https://campfiresms.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sexually explicit, hate speech, or carrier-prohibited content\n  text: You also agree not to send, or have your agent send, sexually explicit content, hate speech, or other content\n    that wireless carriers prohibit on business messaging.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old and authorized\
  \ to use the mobile number you enroll.\n"
source_yaml_url: https://artifacts.apis.io/campfiresms-com/eligibility/campfiresms-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Campfire SMS's own page on 2026-11-09.
synthetic: false
tags:
- SMS
- Artificial Intelligence
- Automation
- Messaging
- Integration
---
