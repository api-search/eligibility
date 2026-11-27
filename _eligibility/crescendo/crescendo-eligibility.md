---
api_specs:
- filename: crescendo-mcp-api-openapi.yml
  format: yaml
  label: Crescendo MCP API
  slug: crescendo-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-mcp-api-openapi.yml
- filename: crescendo-provisioning-api-openapi.yml
  format: yaml
  label: Crescendo Provisioning API
  slug: crescendo-provisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-provisioning-api-openapi.yml
- filename: crescendo-reporting-api-openapi.yml
  format: yaml
  label: Crescendo Reporting API
  slug: crescendo-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-reporting-api-openapi.yml
- filename: crescendo-service-api-openapi.yml
  format: yaml
  label: Crescendo Service API
  slug: crescendo-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-service-api-openapi.yml
- filename: crescendo-voc-api-openapi.yml
  format: yaml
  label: Crescendo VOC API
  slug: crescendo-voc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-voc-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company makes no claims concerning whether the content on this website may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: By accessing or using the site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Automated scraping or bot access
    text: 'use any automated system, software, or process, including but not limited to software or automated agents or scripts, to:'
  - summary: Interfering with servers or networks
    text: interfere with, disrupt, or create an undue burden on servers or networks connected to the Site
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
name: Crescendo
provenance_date: '2026-11-09'
provider_name: Crescendo
provider_slug: crescendo
slug: crescendo-eligibility
source_date: '2026-11-09'
source_filename: crescendo-eligibility.yml
source_heading: Eligibility
source_page: https://www.crescendo.ai/policies/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crescendo\naid: crescendo\nurl: https://www.crescendo.ai/policies/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company makes no claims concerning whether the content on this website may be downloaded, viewed, or\n    be appropriate for use outside of the United States.\nentity_types:\n- type: business\n  text: By accessing or using the site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Automated scraping or bot access\n  text: 'use any automated system, software, or process, including\
  \ but not limited to software or automated agents\n    or scripts, to:'\n- summary: Interfering with servers or networks\n  text: interfere with, disrupt, or create an undue burden on servers or networks connected to the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/crescendo/eligibility/crescendo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Crescendo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Customer Service
- Artificial Intelligence
- AI Agents
- Contact Center
- Conversational AI
- Voice of Customer
- MCP
- Platform
- Automation
---
