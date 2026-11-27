---
api_specs:
- filename: mixmax-contact-groups-api-openapi.yml
  format: yaml
  label: Mixmax Contact Groups API
  slug: mixmax-contact-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixmax/openapi/mixmax-contact-groups-api-openapi.yml
- filename: mixmax-contacts-api-openapi.yml
  format: yaml
  label: Mixmax Contacts API
  slug: mixmax-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixmax/openapi/mixmax-contacts-api-openapi.yml
- filename: mixmax-file-requests-api-openapi.yml
  format: yaml
  label: Mixmax File Requests API
  slug: mixmax-file-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixmax/openapi/mixmax-file-requests-api-openapi.yml
- filename: mixmax-meetings-api-openapi.yml
  format: yaml
  label: Mixmax Meetings API
  slug: mixmax-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixmax/openapi/mixmax-meetings-api-openapi.yml
- filename: mixmax-sequences-api-openapi.yml
  format: yaml
  label: Mixmax Sequences API
  slug: mixmax-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixmax/openapi/mixmax-sequences-api-openapi.yml
- filename: mixmax-snippet-tags-api-openapi.yml
  format: yaml
  label: Mixmax Snippet Tags API
  slug: mixmax-snippet-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixmax/openapi/mixmax-snippet-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16; if you are a child under 16, please do not attempt to register for the Services
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Is harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: Mixmax
provenance_date: '2026-11-10'
provider_name: Mixmax
provider_slug: mixmax
slug: mixmax-eligibility
source_date: '2026-11-10'
source_filename: mixmax-eligibility.yml
source_heading: Eligibility
source_page: https://www.mixmax.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mixmax\naid: mixmax\nurl: https://www.mixmax.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Is harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16; if you\n    are a child under 16, please do not attempt to register for the Services\n"
source_yaml_url: https://artifacts.apis.io/mixmax/eligibility/mixmax-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Mixmax's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- MCP
- Agents
- Webhook
- OAuth
- Sales Engagement
- Email
- Sales
- CRM
- Productivity
- Meetings
- Sequences
- Authentication
---
