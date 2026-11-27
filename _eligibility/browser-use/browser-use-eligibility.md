---
api_specs:
- filename: browser-use-browsers-api-openapi.yml
  format: yaml
  label: Browser Use Browsers API
  slug: browser-use-browsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-browsers-api-openapi.yml
- filename: browser-use-profiles-api-openapi.yml
  format: yaml
  label: Browser Use Profiles API
  slug: browser-use-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-profiles-api-openapi.yml
- filename: browser-use-runs-api-openapi.yml
  format: yaml
  label: Browser Use Runs API
  slug: browser-use-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-runs-api-openapi.yml
- filename: browser-use-sessions-api-openapi.yml
  format: yaml
  label: Browser Use Sessions API
  slug: browser-use-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-sessions-api-openapi.yml
- filename: browser-use-workspaces-api-openapi.yml
  format: yaml
  label: Browser Use Workspaces API
  slug: browser-use-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-workspaces-api-openapi.yml
- filename: browser-use-extensions-api-openapi.yml
  format: yaml
  label: Browser Use Extensions API
  slug: browser-use-extensions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-extensions-api-openapi.yml
- filename: browser-use-integrations-api-openapi.yml
  format: yaml
  label: Browser Use Integrations API
  slug: browser-use-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-integrations-api-openapi.yml
- filename: browser-use-wallets-api-openapi.yml
  format: yaml
  label: Browser Use Wallets API
  slug: browser-use-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-wallets-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual, our Privacy Policy will apply to you
    type: individual
  - text: If you are entering into these Terms of Service on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to these Terms of Service
    type: business
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Competitors barred
    text: No employee, independent contractor, agent, or affiliate of any company that offers a platform competitive with the Service is permitted to view, access, or use any portion of the Service without express written permission from Browser Use.
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
name: Browser Use
provenance_date: '2026-11-09'
provider_name: Browser Use
provider_slug: browser-use
slug: browser-use-eligibility
source_date: '2026-11-09'
source_filename: browser-use-eligibility.yml
source_heading: Eligibility
source_page: https://browser-use.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Browser Use\naid: browser-use\nurl: https://browser-use.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual, our Privacy Policy will apply to you\n- type: business\n  text: If you are entering into these Terms of Service on behalf of a company, business or other legal entity,\n    you represent that you have the authority to bind such entity and its affiliates to these Terms of Service\nrestricted_uses:\n- summary: Competitors barred\n  text: No employee, independent contractor, agent,\
  \ or affiliate of any company that offers a platform competitive\n    with the Service is permitted to view, access, or use any portion of the Service without express written permission\n    from Browser Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/browser-use/eligibility/browser-use-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Browser Use's own page on 2026-11-09.
synthetic: false
tags:
- AI Automation
- Browser Automation
- Web Agents
- Web Scraping
- Agent Infrastructure
- MCP
- Cloud Browser
- A2A
---
