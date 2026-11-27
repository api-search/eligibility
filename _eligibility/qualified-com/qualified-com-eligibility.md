---
api_specs:
- filename: qualified-com-bot-conversations-api-openapi.yml
  format: yaml
  label: Qualified Bot Conversations API
  slug: qualified-com-bot-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-bot-conversations-api-openapi.yml
- filename: qualified-com-bulk-api-openapi.yml
  format: yaml
  label: Qualified Bulk API
  slug: qualified-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-bulk-api-openapi.yml
- filename: qualified-com-cancel-meeting-api-openapi.yml
  format: yaml
  label: Qualified Cancel Meeting API
  slug: qualified-com-cancel-meeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-cancel-meeting-api-openapi.yml
- filename: qualified-com-companies-api-openapi.yml
  format: yaml
  label: Qualified Companies API
  slug: qualified-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-companies-api-openapi.yml
- filename: qualified-com-conversations-api-openapi.yml
  format: yaml
  label: Qualified Conversations API
  slug: qualified-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-conversations-api-openapi.yml
- filename: qualified-com-emails-api-openapi.yml
  format: yaml
  label: Qualified Emails API
  slug: qualified-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-emails-api-openapi.yml
- filename: qualified-com-gdpr-api-openapi.yml
  format: yaml
  label: Qualified GDPR API
  slug: qualified-com-gdpr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-gdpr-api-openapi.yml
- filename: qualified-com-leads-api-openapi.yml
  format: yaml
  label: Qualified Leads API
  slug: qualified-com-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-leads-api-openapi.yml
- filename: qualified-com-meetings-api-openapi.yml
  format: yaml
  label: Qualified Meetings API
  slug: qualified-com-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-meetings-api-openapi.yml
- filename: qualified-com-messages-api-openapi.yml
  format: yaml
  label: Qualified Messages API
  slug: qualified-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-messages-api-openapi.yml
- filename: qualified-com-rep-conversations-api-openapi.yml
  format: yaml
  label: Qualified Rep Conversations API
  slug: qualified-com-rep-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-rep-conversations-api-openapi.yml
- filename: qualified-com-sessions-api-openapi.yml
  format: yaml
  label: Qualified Sessions API
  slug: qualified-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualified-com/openapi/qualified-com-sessions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business use.
    type: business
  minimum_age:
    text: You must be eighteen (18) years or older to register for or use any parts of the Services.
    value: '18'
  restricted_uses:
  - summary: Spam and unlawful content
    text: use the Services to send SPAM or store or transmit content, data or images that are infringing, libelous, fraudulent, offensive, threatening, obscene
  - summary: Unsolicited marketing
    text: Customer will not engage in any unsolicited advertising, marketing, or other activities using the Services
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
name: Qualified
provenance_date: '2026-11-10'
provider_name: Qualified
provider_slug: qualified-com
slug: qualified-com-eligibility
source_date: '2026-11-10'
source_filename: qualified-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.qualified.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qualified\naid: qualified-com\nurl: https://www.qualified.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business use.\nrestricted_uses:\n- summary: Spam and unlawful content\n  text: use the Services to send SPAM or store or transmit content, data or images that are infringing, libelous,\n    fraudulent, offensive, threatening, obscene\n- summary: Unsolicited marketing\n  text: Customer will not engage in any unsolicited advertising, marketing, or other activities using the Services\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years or older to register for or use any parts of the Services.\n"
source_yaml_url: https://artifacts.apis.io/qualified-com/eligibility/qualified-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Qualified's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Conversational Marketing
- Sales
- Marketing
- Artificial Intelligence
- AI Agents
- Lead Generation
- Customer Engagement
- Salesforce
- Analytics
---
