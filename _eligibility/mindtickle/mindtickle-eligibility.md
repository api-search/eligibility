---
api_specs:
- filename: mindtickle-assethub-api-openapi.yml
  format: yaml
  label: Mindtickle Assethub API
  slug: mindtickle-assethub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindtickle/openapi/mindtickle-assethub-api-openapi.yml
- filename: mindtickle-public-api-openapi.yml
  format: yaml
  label: Mindtickle Public API
  slug: mindtickle-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindtickle/openapi/mindtickle-public-api-openapi.yml
- filename: mindtickle-reports-api-openapi.yml
  format: yaml
  label: Mindtickle Reports API
  slug: mindtickle-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindtickle/openapi/mindtickle-reports-api-openapi.yml
- filename: mindtickle-services-api-openapi.yml
  format: yaml
  label: Mindtickle Services API
  slug: mindtickle-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindtickle/openapi/mindtickle-services-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page names no served countries. It states that Controlled Subject Matter will not be exported to countries under a U.S. embargo, without naming them.
  entity_types:
  - text: IF CUSTOMER IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, CUSTOMER REPRESENTS TO HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No access by direct competitors
    text: CUSTOMER MAY NOT ACCESS THE SERVICES IF CUSTOMER IS MINDTICKLE’S DIRECT COMPETITOR, EXCEPT WITH MINDTICKLE’S PRIOR WRITTEN CONSENT.
  - summary: No benchmarking or monitoring access
    text: CUSTOMER MAY NOT ACCESS THE SERVICES FOR PURPOSES OF MONITORING THEIR AVAILABILITY, PERFORMANCE OR FUNCTIONALITY, OR FOR ANY OTHER BENCHMARKING OR COMPETITIVE PURPOSES.
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
name: Mindtickle
provenance_date: '2026-11-10'
provider_name: Mindtickle
provider_slug: mindtickle
slug: mindtickle-eligibility
source_date: '2026-11-10'
source_filename: mindtickle-eligibility.yml
source_heading: Eligibility
source_page: https://www.mindtickle.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mindtickle\naid: mindtickle\nurl: https://www.mindtickle.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page names no served countries. It states that Controlled Subject Matter will not be exported to countries\n    under a U.S. embargo, without naming them.\nentity_types:\n- type: business\n  text: IF CUSTOMER IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, CUSTOMER REPRESENTS\n    TO HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES\nrestricted_uses:\n- summary: No access by direct competitors\n  text: CUSTOMER\
  \ MAY NOT ACCESS THE SERVICES IF CUSTOMER IS MINDTICKLE’S DIRECT COMPETITOR, EXCEPT WITH MINDTICKLE’S\n    PRIOR WRITTEN CONSENT.\n- summary: No benchmarking or monitoring access\n  text: CUSTOMER MAY NOT ACCESS THE SERVICES FOR PURPOSES OF MONITORING THEIR AVAILABILITY, PERFORMANCE OR FUNCTIONALITY,\n    OR FOR ANY OTHER BENCHMARKING OR COMPETITIVE PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mindtickle/eligibility/mindtickle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Mindtickle's own page on 2026-11-10.
synthetic: false
tags:
- Sales Enablement
- Revenue Productivity
- Sales Readiness
- Coaching
- Conversation Intelligence
- LMS
- Content Management
- Call AI
- Revenue Intelligence
---
