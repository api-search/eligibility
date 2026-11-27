---
api_specs:
- filename: docsbot-ai-docsbot-chat-api-api-openapi.yml
  format: yaml
  label: docsbot-ai DocsBot Chat API
  slug: docsbot-ai-docsbot-chat-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsbot-ai/openapi/docsbot-ai-docsbot-chat-api-api-openapi.yml
- filename: docsbot-ai-libraries-api-openapi.yml
  format: yaml
  label: docsbot-ai Libraries API
  slug: docsbot-ai-libraries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsbot-ai/openapi/docsbot-ai-libraries-api-openapi.yml
- filename: docsbot-ai-teams-api-openapi.yml
  format: yaml
  label: docsbot-ai Teams API
  slug: docsbot-ai-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsbot-ai/openapi/docsbot-ai-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Access to and use of our Services is only for those over the age of 13 (or 16 in the European Union).
    value: '13'
  restricted_uses:
  - summary: Fully automated decisions
    text: For fully automated decision making that adversely impacts an individual’s legal rights or otherwise creates or modifies a binding, enforceable obligation;
  - summary: Medical advice
    text: To provide medical advice and medical results interpretation;
  - summary: Law enforcement, immigration or asylum use
    text: To generate or disseminate information for the purpose to be used for administration of justice, law enforcement, immigration or asylum processes
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
name: docsbot-ai
provenance_date: '2026-11-09'
provider_name: docsbot-ai
provider_slug: docsbot-ai
slug: docsbot-ai-eligibility
source_date: '2026-11-09'
source_filename: docsbot-ai-eligibility.yml
source_heading: Eligibility
source_page: https://docsbot.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: docsbot-ai\naid: docsbot-ai\nurl: https://docsbot.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fully automated decisions\n  text: For fully automated decision making that adversely impacts an individual’s legal rights or otherwise creates\n    or modifies a binding, enforceable obligation;\n- summary: Medical advice\n  text: To provide medical advice and medical results interpretation;\n- summary: Law enforcement, immigration or asylum use\n  text: To generate or disseminate information for the purpose\
  \ to be used for administration of justice, law enforcement,\n    immigration or asylum processes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Access to and use of our Services is only for those over the age of 13 (or 16 in the European Union).\n"
source_yaml_url: https://artifacts.apis.io/docsbot-ai/eligibility/docsbot-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from docsbot-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Chatbots
- Automation
- Customer Service
---
