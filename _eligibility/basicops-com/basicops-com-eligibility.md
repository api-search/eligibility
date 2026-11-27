---
api_specs:
- filename: basicops-com-openapi-generated.yml
  format: yaml
  label: BasicOps API
  slug: basicops-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basicops-com/openapi/_ae-authored/basicops-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled, operated and administered by BasicOps from our offices within the USA. Use of the Services is unauthorized in any jurisdiction that does not give effect to all provisions of these Terms.
  entity_types:
  - text: BasicOps only offers company accounts on behalf of business entities and does not offer personal accounts on behalf of individuals.
    type: business
  minimum_age:
    text: Our Services are not directed for persons under 13. We do not knowingly collect or solicit personally identifiable information from children under the age of thirteen.
    value: '13'
  restricted_uses:
  - summary: Unlawful use
    text: you warrant to BasicOps that you will not use the Services for any purpose that is unlawful or prohibited by these Terms.
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
name: BasicOps
provenance_date: '2026-11-09'
provider_name: BasicOps
provider_slug: basicops-com
slug: basicops-com-eligibility
source_date: '2026-11-09'
source_filename: basicops-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.basicops.com/terms-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BasicOps\naid: basicops-com\nurl: https://www.basicops.com/terms-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled, operated and administered by BasicOps from our offices within the USA. Use\n    of the Services is unauthorized in any jurisdiction that does not give effect to all provisions of these Terms.\nentity_types:\n- type: business\n  text: BasicOps only offers company accounts on behalf of business entities and does not offer personal accounts\n    on behalf of individuals.\nrestricted_uses:\n- summary: Unlawful use\n  text: you warrant to\
  \ BasicOps that you will not use the Services for any purpose that is unlawful or prohibited\n    by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Services are not directed for persons under 13. We do not knowingly collect or solicit personally identifiable\n    information from children under the age of thirteen.\n"
source_yaml_url: https://artifacts.apis.io/basicops-com/eligibility/basicops-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BasicOps's own page on 2026-11-09.
synthetic: false
tags:
- Collaboration
- Project Management
- AI Agents
- Productivity
- Software-as-a-Service
---
