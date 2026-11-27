---
api_specs:
- filename: whoop-activity-id-mapping-api-openapi.yml
  format: yaml
  label: WHOOP Activity ID Mapping API
  slug: whoop-activity-id-mapping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-activity-id-mapping-api-openapi.yml
- filename: whoop-cycle-api-openapi.yml
  format: yaml
  label: WHOOP Cycle API
  slug: whoop-cycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-cycle-api-openapi.yml
- filename: whoop-partner-api-openapi.yml
  format: yaml
  label: WHOOP Partner API
  slug: whoop-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-partner-api-openapi.yml
- filename: whoop-recovery-api-openapi.yml
  format: yaml
  label: WHOOP Recovery API
  slug: whoop-recovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-recovery-api-openapi.yml
- filename: whoop-sleep-api-openapi.yml
  format: yaml
  label: WHOOP Sleep API
  slug: whoop-sleep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-sleep-api-openapi.yml
- filename: whoop-user-api-openapi.yml
  format: yaml
  label: WHOOP User API
  slug: whoop-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-user-api-openapi.yml
- filename: whoop-workout-api-openapi.yml
  format: yaml
  label: WHOOP Workout API
  slug: whoop-workout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoop/openapi/whoop-workout-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: WHOOP Advanced Labs and specific features of WHOOP Advanced Labs are not available in all regions, see the WHOOP website for the latest availability details.
  entity_types:
  - text: You represent and warrant that you are at least 13 years of age or the minimum age mandated by the law of your local jurisdiction
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age or the minimum age mandated by the law of your local jurisdiction
    value: '13'
  restricted_uses:
  - summary: Advanced Labs not for minors or pregnant members
    text: WHOOP Advanced Labs are not for use by members under 18 or pregnant members.
  - summary: No insurance reimbursement submissions
    text: you are prohibited from submitting any purchase of services or products from WHOOP, Quest Diagnostics, or SteadyMD for reimbursement by third-party payors.
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
name: WHOOP
provenance_date: '2026-11-10'
provider_name: WHOOP
provider_slug: whoop
slug: whoop-eligibility
source_date: '2026-11-10'
source_filename: whoop-eligibility.yml
source_heading: Eligibility
source_page: https://www.whoop.com/us/en/whoop-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WHOOP\naid: whoop\nurl: https://www.whoop.com/us/en/whoop-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: WHOOP Advanced Labs and specific features of WHOOP Advanced Labs are not available in all regions, see the\n    WHOOP website for the latest availability details.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 13 years of age or the minimum age mandated by the law of\n    your local jurisdiction\nrestricted_uses:\n- summary: Advanced Labs not for minors or pregnant members\n  text: WHOOP Advanced Labs\
  \ are not for use by members under 18 or pregnant members.\n- summary: No insurance reimbursement submissions\n  text: you are prohibited from submitting any purchase of services or products from WHOOP, Quest Diagnostics, or\n    SteadyMD for reimbursement by third-party payors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least 13 years of age or the minimum age mandated by the law of\n    your local jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/whoop/eligibility/whoop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from WHOOP's own page on 2026-11-10.
synthetic: false
tags:
- Fitness
- Wearables
- Health
- Recovery
- Sleep
- Workouts
- Strain
- Heart Rate
- Performance
- Wellness
---
