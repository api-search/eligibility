---
api_specs:
- filename: cloudtalk-agents-api-openapi.yml
  format: yaml
  label: CloudTalk Agents API
  slug: cloudtalk-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-agents-api-openapi.yml
- filename: cloudtalk-bulks-api-openapi.yml
  format: yaml
  label: CloudTalk Bulks API
  slug: cloudtalk-bulks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-bulks-api-openapi.yml
- filename: cloudtalk-calls-api-openapi.yml
  format: yaml
  label: CloudTalk Calls API
  slug: cloudtalk-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-calls-api-openapi.yml
- filename: cloudtalk-campaigns-api-openapi.yml
  format: yaml
  label: CloudTalk Campaigns API
  slug: cloudtalk-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-campaigns-api-openapi.yml
- filename: cloudtalk-contacts-api-openapi.yml
  format: yaml
  label: CloudTalk Contacts API
  slug: cloudtalk-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-contacts-api-openapi.yml
- filename: cloudtalk-conversation-intelligence-api-openapi.yml
  format: yaml
  label: CloudTalk Conversation Intelligence API
  slug: cloudtalk-conversation-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-conversation-intelligence-api-openapi.yml
- filename: cloudtalk-cuecard-api-openapi.yml
  format: yaml
  label: CloudTalk CueCard API
  slug: cloudtalk-cuecard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-cuecard-api-openapi.yml
- filename: cloudtalk-groups-api-openapi.yml
  format: yaml
  label: CloudTalk Groups API
  slug: cloudtalk-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-groups-api-openapi.yml
- filename: cloudtalk-numbers-api-openapi.yml
  format: yaml
  label: CloudTalk Numbers API
  slug: cloudtalk-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-numbers-api-openapi.yml
- filename: cloudtalk-sms-api-openapi.yml
  format: yaml
  label: CloudTalk Sms API
  slug: cloudtalk-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-sms-api-openapi.yml
- filename: cloudtalk-voiceagent-api-openapi.yml
  format: yaml
  label: CloudTalk VoiceAgent API
  slug: cloudtalk-voiceagent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-voiceagent-api-openapi.yml
- filename: cloudtalk-contact-tags-api-openapi.yml
  format: yaml
  label: CloudTalk Contact tags API
  slug: cloudtalk-contact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-contact-tags-api-openapi.yml
- filename: cloudtalk-dialer-api-openapi.yml
  format: yaml
  label: CloudTalk Dialer API
  slug: cloudtalk-dialer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-dialer-api-openapi.yml
- filename: cloudtalk-utilities-api-openapi.yml
  format: yaml
  label: CloudTalk Utilities API
  slug: cloudtalk-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-utilities-api-openapi.yml
- filename: cloudtalk-webhooks-api-openapi.yml
  format: yaml
  label: CloudTalk Webhooks API
  slug: cloudtalk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudtalk/openapi/cloudtalk-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customers with a billing address in the United States or Canada pay a Compliance and Administrative Cost Recovery Fee
  entity_types:
  - text: in the case of an individual accepting this Agreement on his or her own behalf, such individual
    type: individual
  - text: or in the case of an individual accepting this Agreement on behalf of a company or other legal entity, the company or other legal entity on behalf of which such individual is accepting this Agreement
    type: business
  minimum_age:
    text: its representative is at least eighteen (18) years of age or the applicable statutory age of majority to enter into a binding agreement
    value: '18'
  restricted_uses:
  - summary: AI usage restrictions
    text: for social scoring;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: CloudTalk may request from the Customer, its representatives and UBOs information and personal data to satisfactorily identify the Ultimate Beneficial Owner
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CloudTalk
provenance_date: '2026-11-09'
provider_name: CloudTalk
provider_slug: cloudtalk
slug: cloudtalk-eligibility
source_date: '2026-11-09'
source_filename: cloudtalk-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloudtalk.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudTalk\naid: cloudtalk\nurl: https://www.cloudtalk.io/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customers with a billing address in the United States or Canada pay a Compliance and Administrative Cost\n    Recovery Fee\nentity_types:\n- type: individual\n  text: in the case of an individual accepting this Agreement on his or her own behalf, such individual\n- type: business\n  text: or in the case of an individual accepting this Agreement on behalf of a company or other legal entity, the\n    company or other legal entity on behalf\
  \ of which such individual is accepting this Agreement\nrestricted_uses:\n- summary: AI usage restrictions\n  text: for social scoring;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: CloudTalk may request from the Customer, its representatives and UBOs information and personal data to satisfactorily\n    identify the Ultimate Beneficial Owner\nminimum_age:\n  value: '18'\n  text: its representative is at least eighteen (18) years of age or the applicable statutory age of majority to\n    enter into a binding agreement\n"
source_yaml_url: https://artifacts.apis.io/cloudtalk/eligibility/cloudtalk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CloudTalk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Communications
- Voice
- VoIP
- Call Center
- Contact Center
- CCaaS
- Telephony
- SMS
- Conversation Intelligence
---
