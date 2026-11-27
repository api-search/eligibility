---
api_specs:
- filename: beancount-io-ledger-api-openapi.yml
  format: yaml
  label: Beancount.io Ledger API
  slug: beancount-io-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beancount-io/openapi/beancount-io-ledger-api-openapi.yml
- filename: beancount-io-mcp-api-openapi.yml
  format: yaml
  label: Beancount.io MCP API
  slug: beancount-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beancount-io/openapi/beancount-io-mcp-api-openapi.yml
- filename: beancount-io-graph-ql-api-openapi.yml
  format: yaml
  label: Beancount.io Graph QL API
  slug: beancount-io-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beancount-io/openapi/beancount-io-graph-ql-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years of age, then please do not use the Services.
    type: individual
  - text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT IS DOING SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE REQUISITE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: The Services are not provided for persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Illegal or rights-violating use
    text: 'you will not and will not attempt to: (i) violate any laws, third party rights or our other policies'
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
name: Beancount.io
provenance_date: '2026-11-09'
provider_name: Beancount.io
provider_slug: beancount-io
slug: beancount-io-eligibility
source_date: '2026-11-09'
source_filename: beancount-io-eligibility.yml
source_heading: Eligibility
source_page: https://beancount.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beancount.io\naid: beancount-io\nurl: https://beancount.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, then please do not use the Services.\n- type: business\n  text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT IS DOING SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY,\n    SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE REQUISITE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Illegal or rights-violating use\n  text: 'you will not and will not attempt to: (i) violate\
  \ any laws, third party rights or our other policies'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not provided for persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/beancount-io/eligibility/beancount-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beancount.io's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Finance
- Software-as-a-Service
- Open Source
- Collaboration
---
