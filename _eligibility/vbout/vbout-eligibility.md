---
api_specs:
- filename: vbout-account-api-openapi.yml
  format: yaml
  label: VBOUT Account API
  slug: vbout-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-account-api-openapi.yml
- filename: vbout-application-api-openapi.yml
  format: yaml
  label: VBOUT Application API
  slug: vbout-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-application-api-openapi.yml
- filename: vbout-automation-api-openapi.yml
  format: yaml
  label: VBOUT Automation API
  slug: vbout-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-automation-api-openapi.yml
- filename: vbout-contact-api-openapi.yml
  format: yaml
  label: VBOUT Contact API
  slug: vbout-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-contact-api-openapi.yml
- filename: vbout-email-marketing-api-openapi.yml
  format: yaml
  label: VBOUT Email Marketing API
  slug: vbout-email-marketing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-email-marketing-api-openapi.yml
- filename: vbout-goals-api-openapi.yml
  format: yaml
  label: VBOUT Goals API
  slug: vbout-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-goals-api-openapi.yml
- filename: vbout-help-api-openapi.yml
  format: yaml
  label: VBOUT Help API
  slug: vbout-help-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-help-api-openapi.yml
- filename: vbout-pipeline-api-openapi.yml
  format: yaml
  label: VBOUT Pipeline API
  slug: vbout-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-pipeline-api-openapi.yml
- filename: vbout-popups-api-openapi.yml
  format: yaml
  label: VBOUT Popups API
  slug: vbout-popups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-popups-api-openapi.yml
- filename: vbout-settings-api-openapi.yml
  format: yaml
  label: VBOUT Settings API
  slug: vbout-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-settings-api-openapi.yml
- filename: vbout-social-media-api-openapi.yml
  format: yaml
  label: VBOUT Social Media API
  slug: vbout-social-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-social-media-api-openapi.yml
- filename: vbout-users-workflow-api-openapi.yml
  format: yaml
  label: VBOUT Users & Workflow API
  slug: vbout-users-workflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-users-workflow-api-openapi.yml
- filename: vbout-ai-chatbot-api-openapi.yml
  format: yaml
  label: VBOUT AI Chatbot API
  slug: vbout-ai-chatbot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vbout/openapi/vbout-ai-chatbot-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: You must be 13 years or older to use this Service.
    value: '13'
  restricted_uses:
  - summary: Spam and prohibited industries
    text: 'You must not send content if you match any of the following industries: (a) Multi-level marketing or affiliate marketing, (b) Work from home and make money online type of promotions, (c) Cryptocurrency (ex: ICOs or trading), (d) Pharmaceutical products, (e) Certain fundraising campaigns, (f) Gambling services or products, (g) Political groups or affiliations that promote hate and violence, (h) Pornographic content or membership sites, (i) Dating sites, (j) Complex financial services offering.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VBOUT
provenance_date: '2026-11-10'
provider_name: VBOUT
provider_slug: vbout
slug: vbout-eligibility
source_date: '2026-11-10'
source_filename: vbout-eligibility.yml
source_heading: Eligibility
source_page: https://www.vbout.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VBOUT\naid: vbout\nurl: https://www.vbout.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Spam and prohibited industries\n  text: 'You must not send content if you match any of the following industries: (a) Multi-level marketing or affiliate\n    marketing, (b) Work from home and make money online type of promotions, (c) Cryptocurrency\
  \ (ex: ICOs or trading),\n    (d) Pharmaceutical products, (e) Certain fundraising campaigns, (f) Gambling services or products, (g) Political\n    groups or affiliations that promote hate and violence, (h) Pornographic content or membership sites, (i) Dating\n    sites, (j) Complex financial services offering.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your name, a valid email address, and any other information requested in order to complete\n    the signup process.\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/vbout/eligibility/vbout-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from VBOUT's own page on 2026-11-10.
synthetic: false
tags:
- Marketing Automation
- Email Marketing
- Social Media
- Lead Management
- Landing Pages
- Chatbots
- Contacts
- Campaigns
- Software-as-a-Service
---
