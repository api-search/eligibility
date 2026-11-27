---
api_specs:
- filename: connskill-com-analytics-api-openapi.yml
  format: yaml
  label: CONNSKILL Analytics API
  slug: connskill-com-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-analytics-api-openapi.yml
- filename: connskill-com-conformance-api-openapi.yml
  format: yaml
  label: CONNSKILL Conformance API
  slug: connskill-com-conformance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-conformance-api-openapi.yml
- filename: connskill-com-directory-api-openapi.yml
  format: yaml
  label: CONNSKILL Directory API
  slug: connskill-com-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-directory-api-openapi.yml
- filename: connskill-com-discovery-api-openapi.yml
  format: yaml
  label: CONNSKILL Discovery API
  slug: connskill-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-discovery-api-openapi.yml
- filename: connskill-com-eu-llm-api-openapi.yml
  format: yaml
  label: CONNSKILL EU LLM API
  slug: connskill-com-eu-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-eu-llm-api-openapi.yml
- filename: connskill-com-health-api-openapi.yml
  format: yaml
  label: CONNSKILL Health API
  slug: connskill-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-health-api-openapi.yml
- filename: connskill-com-mail-api-openapi.yml
  format: yaml
  label: CONNSKILL Mail API
  slug: connskill-com-mail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-mail-api-openapi.yml
- filename: connskill-com-meta-api-openapi.yml
  format: yaml
  label: CONNSKILL Meta API
  slug: connskill-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-meta-api-openapi.yml
- filename: connskill-com-payments-api-openapi.yml
  format: yaml
  label: CONNSKILL Payments API
  slug: connskill-com-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-payments-api-openapi.yml
- filename: connskill-com-seo-api-openapi.yml
  format: yaml
  label: CONNSKILL SEO API
  slug: connskill-com-seo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-seo-api-openapi.yml
- filename: connskill-com-serp-api-openapi.yml
  format: yaml
  label: CONNSKILL SERP API
  slug: connskill-com-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-serp-api-openapi.yml
- filename: connskill-com-smm-api-openapi.yml
  format: yaml
  label: CONNSKILL SMM API
  slug: connskill-com-smm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-smm-api-openapi.yml
- filename: connskill-com-sms-api-openapi.yml
  format: yaml
  label: CONNSKILL SMS API
  slug: connskill-com-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-sms-api-openapi.yml
- filename: connskill-com-status-json-api-openapi.yml
  format: yaml
  label: CONNSKILL Status.json API
  slug: connskill-com-status-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-status-json-api-openapi.yml
- filename: connskill-com-support-api-openapi.yml
  format: yaml
  label: CONNSKILL Support API
  slug: connskill-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-support-api-openapi.yml
- filename: connskill-com-on-chain-api-openapi.yml
  format: yaml
  label: CONNSKILL On Chain API
  slug: connskill-com-on-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connskill-com/openapi/connskill-com-on-chain-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die AGB gelten ausschließlich gegenüber Unternehmern im Sinne des § 14 BGB, juristischen Personen des öffentlichen Rechts und öffentlich-rechtlichen Sondervermögen.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Der Zugang zur Plattform wird ausschließlich durch CONNSKILL eingerichtet und freigegeben.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CONNSKILL
provenance_date: '2026-11-09'
provider_name: CONNSKILL
provider_slug: connskill-com
slug: connskill-com-eligibility
source_date: '2026-11-09'
source_filename: connskill-com-eligibility.yml
source_heading: Eligibility
source_page: https://connskill.com/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CONNSKILL\naid: connskill-com\nurl: https://connskill.com/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Die AGB gelten ausschließlich gegenüber Unternehmern im Sinne des § 14 BGB, juristischen Personen des öffentlichen\n    Rechts und öffentlich-rechtlichen Sondervermögen.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Der Zugang zur Plattform wird ausschließlich durch CONNSKILL eingerichtet und freigegeben.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/connskill-com/eligibility/connskill-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from CONNSKILL's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- SERP
- Keyword Research
- x402
- Agentic Payments
- AI Agents
- MCP
- A2A
- SMS Verification
- Inference
- Social Media Marketing
- Web Analytics
- Blockchain Data
- Marketing Agency
- Germany
---
