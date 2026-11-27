---
api_specs:
- filename: enzo-health-workflow-runs-api-openapi.yml
  format: yaml
  label: Enzo Health Workflow Runs API
  slug: enzo-health-workflow-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enzo-health/openapi/enzo-health-workflow-runs-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your personal use
    type: individual
  - text: If you are accessing the platform on behalf of your employer, you represent that you have authority to bind your employer to these Terms of Use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: you warrant that you will not use the Platform for any purpose that is unlawful or prohibited by these Terms of Use.
  - summary: Export restrictions
    text: you will not export or import any Platform content to any country to which export or import is restricted under United States law
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
name: Enzo Health
provenance_date: '2026-11-09'
provider_name: Enzo Health
provider_slug: enzo-health
slug: enzo-health-eligibility
source_date: '2026-11-09'
source_filename: enzo-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.enzo.health/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enzo Health\naid: enzo-health\nurl: https://www.enzo.health/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: solely for your personal use\n- type: business\n  text: If you are accessing the platform on behalf of your employer, you represent that you have authority to bind\n    your employer to these Terms of Use.\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: you warrant that you will not use the Platform for any purpose that is unlawful or prohibited by these Terms\n    of Use.\n- summary: Export\
  \ restrictions\n  text: you will not export or import any Platform content to any country to which export or import is restricted\n    under United States law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enzo-health/eligibility/enzo-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Enzo Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Care
- Electronic Health Records
- Healthcare
- Software-as-a-Service
---
