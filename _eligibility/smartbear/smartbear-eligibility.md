---
api_specs:
- filename: smartbear-domains-api-openapi.yml
  format: yaml
  label: SmartBear Domains API
  slug: smartbear-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartbear/openapi/smartbear-domains-api-openapi.yml
- filename: smartbear-integrations-api-openapi.yml
  format: yaml
  label: SmartBear Integrations API
  slug: smartbear-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartbear/openapi/smartbear-integrations-api-openapi.yml
- filename: smartbear-organizations-api-openapi.yml
  format: yaml
  label: SmartBear Organizations API
  slug: smartbear-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartbear/openapi/smartbear-organizations-api-openapi.yml
- filename: smartbear-projects-api-openapi.yml
  format: yaml
  label: SmartBear Projects API
  slug: smartbear-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartbear/openapi/smartbear-projects-api-openapi.yml
- filename: smartbear-apis-api-openapi.yml
  format: yaml
  label: SmartBear APIs API
  slug: smartbear-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartbear/openapi/smartbear-apis-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Governing law depends on whether Customer is located in the U.S. or Canada; Export Control clause references Embargoed Countries and Designated Nationals without listing them.
  entity_types:
  - text: If the individual accepting this Agreement does so on behalf of a company or other entity, that individual represents and warrants that they have the legal authority to bind such entity to this Agreement.
    type: business
  - text: If Customer is a U.S. federal government department or agency or contracting on behalf of such department or agency, the Solutions were developed at private expense and are "Commercial Items"
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted data uploads
    text: Customer and its Users may only upload non-production, non-personal, non-sensitive data (e.g., synthetic or dummy data) when using the Solutions.
  - summary: Export controls
    text: the Solutions and SmartBear Technology (and the components thereof) shall not be exported, or re-exported in, to, or by any Embargoed Countries or Designated Nationals in violation of such export controls.
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
name: SmartBear
provenance_date: '2026-11-10'
provider_name: SmartBear
provider_slug: smartbear
slug: smartbear-eligibility
source_date: '2026-11-10'
source_filename: smartbear-eligibility.yml
source_heading: Eligibility
source_page: https://smartbear.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmartBear\naid: smartbear\nurl: https://smartbear.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Governing law depends on whether Customer is located in the U.S. or Canada; Export Control clause references\n    Embargoed Countries and Designated Nationals without listing them.\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement does so on behalf of a company or other entity, that individual\n    represents and warrants that they have the legal authority to bind such entity to this Agreement.\n- type: government\n  text: If Customer\
  \ is a U.S. federal government department or agency or contracting on behalf of such department\n    or agency, the Solutions were developed at private expense and are \"Commercial Items\"\nrestricted_uses:\n- summary: Restricted data uploads\n  text: Customer and its Users may only upload non-production, non-personal, non-sensitive data (e.g., synthetic\n    or dummy data) when using the Solutions.\n- summary: Export controls\n  text: the Solutions and SmartBear Technology (and the components thereof) shall not be exported, or re-exported\n    in, to, or by any Embargoed Countries or Designated Nationals in violation of such export controls.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smartbear/eligibility/smartbear-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from SmartBear's own page on 2026-11-10.
synthetic: false
tags:
- API Design
- API Documentation
- API Testing
- Contract Testing
- Developer Tools
- Governance
- Monitoring
- Platform
- Testing
---
