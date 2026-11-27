---
api_specs:
- filename: loops-api-key-api-openapi.yml
  format: yaml
  label: Loops API key API
  slug: loops-api-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-api-key-api-openapi.yml
- filename: loops-audience-segments-api-openapi.yml
  format: yaml
  label: Loops Audience segments API
  slug: loops-audience-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-audience-segments-api-openapi.yml
- filename: loops-campaign-groups-api-openapi.yml
  format: yaml
  label: Loops Campaign groups API
  slug: loops-campaign-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-campaign-groups-api-openapi.yml
- filename: loops-campaigns-api-openapi.yml
  format: yaml
  label: Loops Campaigns API
  slug: loops-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-campaigns-api-openapi.yml
- filename: loops-components-api-openapi.yml
  format: yaml
  label: Loops Components API
  slug: loops-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-components-api-openapi.yml
- filename: loops-configuration-api-openapi.yml
  format: yaml
  label: Loops Configuration API
  slug: loops-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-configuration-api-openapi.yml
- filename: loops-contact-properties-api-openapi.yml
  format: yaml
  label: Loops Contact properties API
  slug: loops-contact-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-contact-properties-api-openapi.yml
- filename: loops-contacts-api-openapi.yml
  format: yaml
  label: Loops Contacts API
  slug: loops-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-contacts-api-openapi.yml
- filename: loops-email-messages-api-openapi.yml
  format: yaml
  label: Loops Email messages API
  slug: loops-email-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-email-messages-api-openapi.yml
- filename: loops-event-patterns-api-openapi.yml
  format: yaml
  label: Loops Event patterns API
  slug: loops-event-patterns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-event-patterns-api-openapi.yml
- filename: loops-events-api-openapi.yml
  format: yaml
  label: Loops Events API
  slug: loops-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-events-api-openapi.yml
- filename: loops-mailing-lists-api-openapi.yml
  format: yaml
  label: Loops Mailing lists API
  slug: loops-mailing-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-mailing-lists-api-openapi.yml
- filename: loops-themes-api-openapi.yml
  format: yaml
  label: Loops Themes API
  slug: loops-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-themes-api-openapi.yml
- filename: loops-transactional-emails-api-openapi.yml
  format: yaml
  label: Loops Transactional emails API
  slug: loops-transactional-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-transactional-emails-api-openapi.yml
- filename: loops-transactional-groups-api-openapi.yml
  format: yaml
  label: Loops Transactional groups API
  slug: loops-transactional-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-transactional-groups-api-openapi.yml
- filename: loops-uploads-api-openapi.yml
  format: yaml
  label: Loops Uploads API
  slug: loops-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-uploads-api-openapi.yml
- filename: loops-workflow-nodes-api-openapi.yml
  format: yaml
  label: Loops Workflow nodes API
  slug: loops-workflow-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-workflow-nodes-api-openapi.yml
- filename: loops-workflows-api-openapi.yml
  format: yaml
  label: Loops Workflows API
  slug: loops-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-workflows-api-openapi.yml
- filename: loops-webhooks-asyncapi.yml
  format: yaml
  label: Loops Webhooks
  slug: loops-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/loops/asyncapi/loops-webhooks-asyncapi.yml
- filename: loops-webhooks-api-openapi.yml
  format: yaml
  label: Loops Webhooks API
  slug: loops-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: 'Please report any suspected abuse to our support team. Use of our Services for any dealings... with the following jurisdictions: Cuba, Iran, North Korea, Syria, Russian Federation and the Crimea, Donetsk and Luhansk regions, is prohibited.'
  minimum_age:
    text: You must be 18 years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Restricted industries require approval
    text: 'you agree that you will not engage in the following activities without first receiving prior written approval from the Company: Use our Services to provide or offer to provide certain (i) financial products and services'
  - summary: Crypto, NFTs, pharmaceuticals, tobacco, astrology, loans, legal services
    text: Use our Service to offer or sell crypto, NFT’s, or other related goods or services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Loops
provenance_date: '2026-11-09'
provider_name: Loops
provider_slug: loops
slug: loops-eligibility
source_date: '2026-11-09'
source_filename: loops-eligibility.yml
source_heading: Eligibility
source_page: https://loops.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loops\naid: loops\nurl: https://loops.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: 'Please report any suspected abuse to our support team. Use of our Services for any dealings... with the\n    following jurisdictions: Cuba, Iran, North Korea, Syria, Russian Federation and the Crimea, Donetsk and Luhansk\n    regions, is prohibited.'\nentity_types: []\nrestricted_uses:\n- summary: Restricted industries require approval\n  text: 'you agree that you will not engage in the following activities without first receiving prior written approval\n \
  \   from the Company: Use our Services to provide or offer to provide certain (i) financial products and services'\n- summary: Crypto, NFTs, pharmaceuticals, tobacco, astrology, loans, legal services\n  text: Use our Service to offer or sell crypto, NFT’s, or other related goods or services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/loops/eligibility/loops-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Loops's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Email API
- Marketing Automation
- Transactional Email
- Lifecycle Email
- Webhook
- Software-as-a-Service
- Communications
- Developer Tools
- MCP
- Agents
- Campaigns
---
