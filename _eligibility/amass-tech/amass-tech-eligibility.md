---
api_specs:
- filename: amass-tech-cores-biomedcore-api-openapi.yml
  format: yaml
  label: Amass Cores/biomedcore API
  slug: amass-tech-cores-biomedcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-biomedcore-api-openapi.yml
- filename: amass-tech-cores-drugcore-api-openapi.yml
  format: yaml
  label: Amass Cores/drugcore API
  slug: amass-tech-cores-drugcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-drugcore-api-openapi.yml
- filename: amass-tech-cores-genecore-api-openapi.yml
  format: yaml
  label: Amass Cores/genecore API
  slug: amass-tech-cores-genecore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-genecore-api-openapi.yml
- filename: amass-tech-cores-patentcore-api-openapi.yml
  format: yaml
  label: Amass Cores/patentcore API
  slug: amass-tech-cores-patentcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-patentcore-api-openapi.yml
- filename: amass-tech-cores-regulatorycore-api-openapi.yml
  format: yaml
  label: Amass Cores/regulatorycore API
  slug: amass-tech-cores-regulatorycore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-regulatorycore-api-openapi.yml
- filename: amass-tech-cores-trialcore-api-openapi.yml
  format: yaml
  label: Amass Cores/trialcore API
  slug: amass-tech-cores-trialcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-trialcore-api-openapi.yml
- filename: amass-tech-credits-api-openapi.yml
  format: yaml
  label: Amass Credits API
  slug: amass-tech-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-credits-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use the Services.
    type: individual
  - text: If you accept these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind that entity, in which case "Customer" means that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: Sensitive data
    text: By default, the Services are not intended to require the processing of special categories of personal data under GDPR
  - summary: Not professional advice
    text: The Services are designed to assist with research, analysis and knowledge management, but do not constitute medical, clinical, regulatory, legal or other professional advice.
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
name: Amass
provenance_date: '2026-11-09'
provider_name: Amass
provider_slug: amass-tech
slug: amass-tech-eligibility
source_date: '2026-11-09'
source_filename: amass-tech-eligibility.yml
source_heading: Eligibility
source_page: https://amass.tech/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amass\naid: amass-tech\nurl: https://amass.tech/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Services.\n- type: business\n  text: If you accept these Terms on behalf of a company or other legal entity, you represent that you have the\n    authority to bind that entity, in which case \"Customer\" means that entity.\nrestricted_uses:\n- summary: Sensitive data\n  text: By default, the Services are not intended to require the\
  \ processing of special categories of personal data\n    under GDPR\n- summary: Not professional advice\n  text: The Services are designed to assist with research, analysis and knowledge management, but do not constitute\n    medical, clinical, regulatory, legal or other professional advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/amass-tech/eligibility/amass-tech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Amass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Data Intelligence
- MCP
---
