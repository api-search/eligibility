---
api_specs:
- filename: namely-comments-api-openapi.yml
  format: yaml
  label: Namely Comments API
  slug: namely-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-comments-api-openapi.yml
- filename: namely-company-info-api-openapi.yml
  format: yaml
  label: Namely Company Info API
  slug: namely-company-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-company-info-api-openapi.yml
- filename: namely-company-resources-api-openapi.yml
  format: yaml
  label: Namely Company Resources API
  slug: namely-company-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-company-resources-api-openapi.yml
- filename: namely-countries-api-openapi.yml
  format: yaml
  label: Namely Countries API
  slug: namely-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-countries-api-openapi.yml
- filename: namely-events-api-openapi.yml
  format: yaml
  label: Namely Events API
  slug: namely-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-events-api-openapi.yml
- filename: namely-groups-api-openapi.yml
  format: yaml
  label: Namely Groups API
  slug: namely-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-groups-api-openapi.yml
- filename: namely-groups-teams-api-openapi.yml
  format: yaml
  label: Namely Groups & Teams API
  slug: namely-groups-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-groups-teams-api-openapi.yml
- filename: namely-home-feed-api-openapi.yml
  format: yaml
  label: Namely Home Feed API
  slug: namely-home-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-home-feed-api-openapi.yml
- filename: namely-job-tier-api-openapi.yml
  format: yaml
  label: Namely Job Tier API
  slug: namely-job-tier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-job-tier-api-openapi.yml
- filename: namely-job-title-api-openapi.yml
  format: yaml
  label: Namely Job Title API
  slug: namely-job-title-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-job-title-api-openapi.yml
- filename: namely-jobs-info-api-openapi.yml
  format: yaml
  label: Namely Jobs Info API
  slug: namely-jobs-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-jobs-info-api-openapi.yml
- filename: namely-likes-api-openapi.yml
  format: yaml
  label: Namely Likes API
  slug: namely-likes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-likes-api-openapi.yml
- filename: namely-namely-system-info-api-openapi.yml
  format: yaml
  label: Namely System Info API
  slug: namely-namely-system-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-namely-system-info-api-openapi.yml
- filename: namely-notifications-api-openapi.yml
  format: yaml
  label: Namely Notifications API
  slug: namely-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-notifications-api-openapi.yml
- filename: namely-profile-fields-api-openapi.yml
  format: yaml
  label: Namely Profile Fields API
  slug: namely-profile-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-profile-fields-api-openapi.yml
- filename: namely-profile-fields-sections-api-openapi.yml
  format: yaml
  label: Namely Profile Fields Sections API
  slug: namely-profile-fields-sections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-profile-fields-sections-api-openapi.yml
- filename: namely-profiles-api-openapi.yml
  format: yaml
  label: Namely Profiles API
  slug: namely-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-profiles-api-openapi.yml
- filename: namely-reports-api-openapi.yml
  format: yaml
  label: Namely Reports API
  slug: namely-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-reports-api-openapi.yml
- filename: namely-teams-api-openapi.yml
  format: yaml
  label: Namely Teams API
  slug: namely-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namely/openapi/namely-teams-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of Content
    text: You shall not sell, license, rent, or otherwise use or exploit any Content for commercial use
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
name: Namely
provenance_date: '2026-11-10'
provider_name: Namely
provider_slug: namely
slug: namely-eligibility
source_date: '2026-11-10'
source_filename: namely-eligibility.yml
source_heading: Eligibility
source_page: https://namely.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Namely\naid: namely\nurl: https://namely.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use of Content\n  text: You shall not sell, license, rent, or otherwise use or exploit any Content for commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/namely/eligibility/namely-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Namely's own page on 2026-11-10.
synthetic: false
tags:
- Human Resources
- HCM
- Payroll
- Employee Data
- Onboarding
- Benefits
- Applicant Tracking
- Performance Management
- SCIM
- SSO
- Identity Provisioning
- Workforce Management
- Identity Federation
- Employee Benefits
---
