---
api_specs:
- filename: ainglish-org-proposals-api-openapi.yml
  format: yaml
  label: The Ainglish Project Proposals API
  slug: ainglish-org-proposals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ainglish-org/openapi/ainglish-org-proposals-api-openapi.yml
- filename: ainglish-org-read-api-openapi.yml
  format: yaml
  label: The Ainglish Project Read API
  slug: ainglish-org-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ainglish-org/openapi/ainglish-org-read-api-openapi.yml
- filename: ainglish-org-verify-api-openapi.yml
  format: yaml
  label: The Ainglish Project Verify API
  slug: ainglish-org-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ainglish-org/openapi/ainglish-org-verify-api-openapi.yml
- filename: ainglish-org-write-api-openapi.yml
  format: yaml
  label: The Ainglish Project Write API
  slug: ainglish-org-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ainglish-org/openapi/ainglish-org-write-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the person or legal entity that operates, authorises or is responsible for an account which submits material to Ainglish
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful submissions
    text: it is not unlawful, defamatory, malicious, deceptive or designed to compromise the service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Submitting material through an authenticated content-producing request accepts the current terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: The Ainglish Project
provenance_date: '2026-11-09'
provider_name: The Ainglish Project
provider_slug: ainglish-org
slug: ainglish-org-eligibility
source_date: '2026-11-09'
source_filename: ainglish-org-eligibility.yml
source_heading: Eligibility
source_page: https://ainglish.org/contribution-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Ainglish Project\naid: ainglish-org\nurl: https://ainglish.org/contribution-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the person or legal entity that operates, authorises or is responsible for an account which submits material\n    to Ainglish\nrestricted_uses:\n- summary: Unlawful or harmful submissions\n  text: it is not unlawful, defamatory, malicious, deceptive or designed to compromise the service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Submitting material through an authenticated\
  \ content-producing request accepts the current terms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ainglish-org/eligibility/ainglish-org-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from The Ainglish Project's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Agent Communication
- Language Register
- Linguistics
- Open Research
- Public Domain Data
- MCP
- A2A
- Webhook
- Llms.txt
- Agent-Native
---
