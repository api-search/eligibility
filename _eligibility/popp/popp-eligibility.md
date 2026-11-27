---
api_specs:
- filename: popp-agents-api-openapi.yml
  format: yaml
  label: Popp Agents API
  slug: popp-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-agents-api-openapi.yml
- filename: popp-analysis-api-openapi.yml
  format: yaml
  label: Popp Analysis API
  slug: popp-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-analysis-api-openapi.yml
- filename: popp-ats-api-openapi.yml
  format: yaml
  label: Popp ATS API
  slug: popp-ats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-ats-api-openapi.yml
- filename: popp-campaigns-api-openapi.yml
  format: yaml
  label: Popp Campaigns API
  slug: popp-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-campaigns-api-openapi.yml
- filename: popp-candidate-lists-api-openapi.yml
  format: yaml
  label: Popp Candidate Lists API
  slug: popp-candidate-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-candidate-lists-api-openapi.yml
- filename: popp-candidates-api-openapi.yml
  format: yaml
  label: Popp Candidates API
  slug: popp-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-candidates-api-openapi.yml
- filename: popp-conversations-api-openapi.yml
  format: yaml
  label: Popp Conversations API
  slug: popp-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-conversations-api-openapi.yml
- filename: popp-custom-fields-beta-api-openapi.yml
  format: yaml
  label: Popp Custom Fields (Beta) API
  slug: popp-custom-fields-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-custom-fields-beta-api-openapi.yml
- filename: popp-document-credentials-api-openapi.yml
  format: yaml
  label: Popp Document Credentials API
  slug: popp-document-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-document-credentials-api-openapi.yml
- filename: popp-documents-api-openapi.yml
  format: yaml
  label: Popp Documents API
  slug: popp-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-documents-api-openapi.yml
- filename: popp-organization-configuration-api-openapi.yml
  format: yaml
  label: Popp Organization Configuration API
  slug: popp-organization-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-organization-configuration-api-openapi.yml
- filename: popp-organizations-api-openapi.yml
  format: yaml
  label: Popp Organizations API
  slug: popp-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-organizations-api-openapi.yml
- filename: popp-scheduling-api-openapi.yml
  format: yaml
  label: Popp Scheduling API
  slug: popp-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-scheduling-api-openapi.yml
- filename: popp-tags-api-openapi.yml
  format: yaml
  label: Popp Tags API
  slug: popp-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-tags-api-openapi.yml
- filename: popp-templates-api-openapi.yml
  format: yaml
  label: Popp Templates API
  slug: popp-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-templates-api-openapi.yml
- filename: popp-users-api-openapi.yml
  format: yaml
  label: Popp Users API
  slug: popp-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-users-api-openapi.yml
- filename: popp-webhooks-api-openapi.yml
  format: yaml
  label: Popp Webhooks API
  slug: popp-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-webhooks-api-openapi.yml
- filename: popp-workflows-api-openapi.yml
  format: yaml
  label: Popp Workflows API
  slug: popp-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popp/openapi/popp-workflows-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Popp specialises in business-to-business software solutions, providing recruiters and hiring teams with efficient talent acquisition processes through our website and other software and services.
    type: business
  - text: If you are accepting these Terms on behalf of an entity or agency, you represent and warrant that you have the authority to bind that entity or agency.
    type: individual
  minimum_age:
    text: To use Popp's Site or Services, you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Recording compliance
    text: You will use Popp's recording tools in compliance with all applicable local, national, and other laws, rules, and regulations, including those pertaining to privacy
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
name: Popp
provenance_date: '2026-11-10'
provider_name: Popp
provider_slug: popp
slug: popp-eligibility
source_date: '2026-11-10'
source_filename: popp-eligibility.yml
source_heading: Eligibility
source_page: https://joinpopp.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Popp\naid: popp\nurl: https://joinpopp.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Popp specialises in business-to-business software solutions, providing recruiters and hiring teams with\n    efficient talent acquisition processes through our website and other software and services.\n- type: individual\n  text: If you are accepting these Terms on behalf of an entity or agency, you represent and warrant that you have\n    the authority to bind that entity or agency.\nrestricted_uses:\n- summary: Recording compliance\n\
  \  text: You will use Popp's recording tools in compliance with all applicable local, national, and other laws, rules,\n    and regulations, including those pertaining to privacy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use Popp's Site or Services, you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/popp/eligibility/popp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Popp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recruiting
- Staffing
- Hiring
- Conversational AI
- Automation
- Scheduling
- Workflows
- Webhook
- MCP
- Agents
---
