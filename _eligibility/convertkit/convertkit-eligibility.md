---
api_specs:
- filename: convertkit-accounts-api-openapi.yml
  format: yaml
  label: Kit Accounts API
  slug: convertkit-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-accounts-api-openapi.yml
- filename: convertkit-broadcasts-api-openapi.yml
  format: yaml
  label: Kit Broadcasts API
  slug: convertkit-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-broadcasts-api-openapi.yml
- filename: convertkit-custom-fields-api-openapi.yml
  format: yaml
  label: Kit Custom Fields API
  slug: convertkit-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-custom-fields-api-openapi.yml
- filename: convertkit-email-templates-api-openapi.yml
  format: yaml
  label: Kit Email Templates API
  slug: convertkit-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-email-templates-api-openapi.yml
- filename: convertkit-forms-api-openapi.yml
  format: yaml
  label: Kit Forms API
  slug: convertkit-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-forms-api-openapi.yml
- filename: convertkit-posts-api-openapi.yml
  format: yaml
  label: Kit Posts API
  slug: convertkit-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-posts-api-openapi.yml
- filename: convertkit-purchases-api-openapi.yml
  format: yaml
  label: Kit Purchases API
  slug: convertkit-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-purchases-api-openapi.yml
- filename: convertkit-segments-api-openapi.yml
  format: yaml
  label: Kit Segments API
  slug: convertkit-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-segments-api-openapi.yml
- filename: convertkit-sequence-emails-api-openapi.yml
  format: yaml
  label: Kit Sequence Emails API
  slug: convertkit-sequence-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-sequence-emails-api-openapi.yml
- filename: convertkit-sequences-api-openapi.yml
  format: yaml
  label: Kit Sequences API
  slug: convertkit-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-sequences-api-openapi.yml
- filename: convertkit-snippets-api-openapi.yml
  format: yaml
  label: Kit Snippets API
  slug: convertkit-snippets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-snippets-api-openapi.yml
- filename: convertkit-subscribers-api-openapi.yml
  format: yaml
  label: Kit Subscribers API
  slug: convertkit-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-subscribers-api-openapi.yml
- filename: convertkit-tags-api-openapi.yml
  format: yaml
  label: Kit Tags API
  slug: convertkit-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-tags-api-openapi.yml
- filename: convertkit-webhooks-api-openapi.yml
  format: yaml
  label: Kit Webhooks API
  slug: convertkit-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-webhooks-api-openapi.yml
- filename: convertkit-account-api-openapi.yml
  format: yaml
  label: Kit Account API
  slug: convertkit-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertkit/openapi/convertkit-account-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Kit provides the Services solely from the United States.
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Unauthorized or illegal use
    text: Use our Services for any illegal or unauthorized purpose, or engage in, encourage or promote any activity that violates these Terms.
  - summary: Spam and bulk communications
    text: Send, distribute or post spam, unsolicited or bulk commercial electronic communications, chain letters, or pyramid schemes;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Kit will review the information you submit while signing up for a Commerce Account. You authorize Kit to request information verifying your identity at any time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kit
provenance_date: '2026-11-09'
provider_name: Kit
provider_slug: convertkit
slug: convertkit-eligibility
source_date: '2026-11-09'
source_filename: convertkit-eligibility.yml
source_heading: Eligibility
source_page: https://kit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kit\naid: convertkit\nurl: https://kit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Kit provides the Services solely from the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\nrestricted_uses:\n- summary: Unauthorized or illegal use\n  text: Use our Services for any illegal or unauthorized purpose, or engage in, encourage or promote any activity\n    that violates these Terms.\n- summary: Spam and bulk communications\n  text: Send, distribute or post spam, unsolicited or bulk\
  \ commercial electronic communications, chain letters,\n    or pyramid schemes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Kit will review the information you submit while signing up for a Commerce Account. You authorize Kit to\n    request information verifying your identity at any time\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/convertkit/eligibility/convertkit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Kit's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Creator Economy
- Subscribers
- Automation
- Newsletters
- Sequences
- Forms
- Broadcast
- Webhook
- MCP
- Agents
- Authentication
- Marketing Automation
- Landing Pages
- Segmentation
- Email Campaigns
- Software-as-a-Service
- Commerce
- A2A
- Email
---
