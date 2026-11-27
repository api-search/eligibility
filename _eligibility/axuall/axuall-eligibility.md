---
api_specs:
- filename: axuall-actor-api-openapi.yml
  format: yaml
  label: Axuall Actor API
  slug: axuall-actor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-actor-api-openapi.yml
- filename: axuall-address-deduplications-api-openapi.yml
  format: yaml
  label: Axuall Address Deduplications API
  slug: axuall-address-deduplications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-address-deduplications-api-openapi.yml
- filename: axuall-agent-api-openapi.yml
  format: yaml
  label: Axuall Agent API
  slug: axuall-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-agent-api-openapi.yml
- filename: axuall-authentication-api-openapi.yml
  format: yaml
  label: Axuall Authentication API
  slug: axuall-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-authentication-api-openapi.yml
- filename: axuall-case-log-artifact-api-openapi.yml
  format: yaml
  label: Axuall Case Log Artifact API
  slug: axuall-case-log-artifact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-case-log-artifact-api-openapi.yml
- filename: axuall-documents-api-openapi.yml
  format: yaml
  label: Axuall Documents API
  slug: axuall-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-documents-api-openapi.yml
- filename: axuall-email-api-openapi.yml
  format: yaml
  label: Axuall Email API
  slug: axuall-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-email-api-openapi.yml
- filename: axuall-facilities-api-openapi.yml
  format: yaml
  label: Axuall Facilities API
  slug: axuall-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-facilities-api-openapi.yml
- filename: axuall-fsmb-artifact-api-openapi.yml
  format: yaml
  label: Axuall FSMB Artifact API
  slug: axuall-fsmb-artifact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-fsmb-artifact-api-openapi.yml
- filename: axuall-invite-api-openapi.yml
  format: yaml
  label: Axuall Invite API
  slug: axuall-invite-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-invite-api-openapi.yml
- filename: axuall-monitoring-reports-api-openapi.yml
  format: yaml
  label: Axuall Monitoring reports API
  slug: axuall-monitoring-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-monitoring-reports-api-openapi.yml
- filename: axuall-provider-preview-api-openapi.yml
  format: yaml
  label: Axuall Provider Preview API
  slug: axuall-provider-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-provider-preview-api-openapi.yml
- filename: axuall-providers-api-openapi.yml
  format: yaml
  label: Axuall Providers API
  slug: axuall-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-providers-api-openapi.yml
- filename: axuall-recipes-api-openapi.yml
  format: yaml
  label: Axuall Recipes API
  slug: axuall-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-recipes-api-openapi.yml
- filename: axuall-tasks-api-openapi.yml
  format: yaml
  label: Axuall Tasks API
  slug: axuall-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axuall/openapi/axuall-tasks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended to be used by adults (18 years of age or older) to request and submit credentialing information
    type: individual
  minimum_age:
    text: The Site is intended to be used by adults (18 years of age or older)
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may use the Site only for its lawfully intended purpose and as provided in these Terms of Use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Axuall Services you must register for and maintain an active user account in accordance with these Terms of Use.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Axuall
provenance_date: '2026-11-09'
provider_name: Axuall
provider_slug: axuall
slug: axuall-eligibility
source_date: '2026-11-09'
source_filename: axuall-eligibility.yml
source_heading: Eligibility
source_page: https://axuall.com/utility/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Axuall\naid: axuall\nurl: https://axuall.com/utility/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended to be used by adults (18 years of age or older) to request and submit credentialing\n    information\nrestricted_uses:\n- summary: Lawful use only\n  text: You may use the Site only for its lawfully intended purpose and as provided in these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Axuall Services you must register for and maintain an active\
  \ user account in accordance with\n    these Terms of Use.\nminimum_age:\n  value: '18'\n  text: The Site is intended to be used by adults (18 years of age or older)\n"
source_yaml_url: https://artifacts.apis.io/axuall/eligibility/axuall-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Axuall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Data
- Credentialing
- Artificial Intelligence
---
