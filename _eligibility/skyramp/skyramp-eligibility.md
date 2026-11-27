---
api_specs:
- filename: skyramp-openapi-generated.yml
  format: yaml
  label: Skyramp API
  slug: skyramp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skyramp/openapi/_ae-authored/skyramp-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    value: '13'
  restricted_uses:
  - summary: Software testing purpose only
    text: (i) for software testing (including but not limited to load and integration testing) during the software development process and lifecycle
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skyramp
provenance_date: '2026-11-10'
provider_name: Skyramp
provider_slug: skyramp
slug: skyramp-eligibility
source_date: '2026-11-10'
source_filename: skyramp-eligibility.yml
source_heading: Eligibility
source_page: https://docs.skyramp.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skyramp\naid: skyramp\nurl: https://docs.skyramp.dev/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Software testing purpose only\n  text: (i) for software testing (including but not limited to load and integration testing) during the software\n    development process and lifecycle\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n"
source_yaml_url: https://artifacts.apis.io/skyramp/eligibility/skyramp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Skyramp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Testing
- Developer Tools
- Automation
---
