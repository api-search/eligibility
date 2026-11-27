---
api_specs:
- filename: gospotcheck-asyncjobs-api-openapi.yml
  format: yaml
  label: GoSpotCheck AsyncJobs API
  slug: gospotcheck-asyncjobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-asyncjobs-api-openapi.yml
- filename: gospotcheck-catalogs-api-openapi.yml
  format: yaml
  label: GoSpotCheck Catalogs API
  slug: gospotcheck-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-catalogs-api-openapi.yml
- filename: gospotcheck-customviews-api-openapi.yml
  format: yaml
  label: GoSpotCheck CustomViews API
  slug: gospotcheck-customviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-customviews-api-openapi.yml
- filename: gospotcheck-missionresponses-api-openapi.yml
  format: yaml
  label: GoSpotCheck MissionResponses API
  slug: gospotcheck-missionresponses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-missionresponses-api-openapi.yml
- filename: gospotcheck-missions-api-openapi.yml
  format: yaml
  label: GoSpotCheck Missions API
  slug: gospotcheck-missions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-missions-api-openapi.yml
- filename: gospotcheck-placegroups-api-openapi.yml
  format: yaml
  label: GoSpotCheck PlaceGroups API
  slug: gospotcheck-placegroups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-placegroups-api-openapi.yml
- filename: gospotcheck-places-api-openapi.yml
  format: yaml
  label: GoSpotCheck Places API
  slug: gospotcheck-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-places-api-openapi.yml
- filename: gospotcheck-taskresponses-api-openapi.yml
  format: yaml
  label: GoSpotCheck TaskResponses API
  slug: gospotcheck-taskresponses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-taskresponses-api-openapi.yml
- filename: gospotcheck-tasks-api-openapi.yml
  format: yaml
  label: GoSpotCheck Tasks API
  slug: gospotcheck-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-tasks-api-openapi.yml
- filename: gospotcheck-teams-api-openapi.yml
  format: yaml
  label: GoSpotCheck Teams API
  slug: gospotcheck-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-teams-api-openapi.yml
- filename: gospotcheck-userplaceassignments-api-openapi.yml
  format: yaml
  label: GoSpotCheck UserPlaceAssignments API
  slug: gospotcheck-userplaceassignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-userplaceassignments-api-openapi.yml
- filename: gospotcheck-users-api-openapi.yml
  format: yaml
  label: GoSpotCheck Users API
  slug: gospotcheck-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-users-api-openapi.yml
- filename: gospotcheck-catalog-items-api-openapi.yml
  format: yaml
  label: GoSpotCheck Catalog Items API
  slug: gospotcheck-catalog-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gospotcheck/openapi/gospotcheck-catalog-items-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: corporate entities (each a “Principal”) can enlist individual users that have downloaded the App
    type: business
  - text: You represent and warrant that you (a) are above the legal age of majority in your jurisdiction of residence
    type: individual
  minimum_age:
    text: are above the legal age of majority in your jurisdiction of residence
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: 'You shall not upload to, transmit through, or display via the Service any content that: (i) is unlawful, fraudulent, threatening, abusive, libelous, defamatory, obscene or otherwise objectionable'
  - summary: No account sharing
    text: YOU MAY NEVER USE ANOTHER PERSON’S MEMBER ACCOUNT WITHOUT PERMISSION.
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
name: GoSpotCheck
provenance_date: '2026-11-09'
provider_name: GoSpotCheck
provider_slug: gospotcheck
slug: gospotcheck-eligibility
source_date: '2026-11-09'
source_filename: gospotcheck-eligibility.yml
source_heading: Eligibility
source_page: https://www.gospotcheck.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoSpotCheck\naid: gospotcheck\nurl: https://www.gospotcheck.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: corporate entities (each a “Principal”) can enlist individual users that have downloaded the App\n- type: individual\n  text: You represent and warrant that you (a) are above the legal age of majority in your jurisdiction of residence\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: 'You shall not upload to, transmit through, or display via the Service any content that: (i) is unlawful,\n    fraudulent,\
  \ threatening, abusive, libelous, defamatory, obscene or otherwise objectionable'\n- summary: No account sharing\n  text: YOU MAY NEVER USE ANOTHER PERSON’S MEMBER ACCOUNT WITHOUT PERMISSION.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: are above the legal age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/gospotcheck/eligibility/gospotcheck-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from GoSpotCheck's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail Execution
- Field Service Management
- Data Collection
- Surveys
- Merchandising
- Consumer Packaged Goods
- Mobile
---
