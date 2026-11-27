---
api_specs:
- filename: paedae-applications-api-openapi.yml
  format: yaml
  label: Paedae Applications API
  slug: paedae-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paedae/openapi/paedae-applications-api-openapi.yml
- filename: paedae-beacon-configurations-api-openapi.yml
  format: yaml
  label: Paedae Beacon Configurations API
  slug: paedae-beacon-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paedae/openapi/paedae-beacon-configurations-api-openapi.yml
- filename: paedae-beacons-api-openapi.yml
  format: yaml
  label: Paedae Beacons API
  slug: paedae-beacons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paedae/openapi/paedae-beacons-api-openapi.yml
- filename: paedae-communications-api-openapi.yml
  format: yaml
  label: Paedae Communications API
  slug: paedae-communications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paedae/openapi/paedae-communications-api-openapi.yml
- filename: paedae-places-api-openapi.yml
  format: yaml
  label: Paedae Places API
  slug: paedae-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paedae/openapi/paedae-places-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if the Site is being used on behalf of an organization such as your employer, you have the authority to bind such organization to the TOU
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: YOU MUST COMPLY WITH ALL DOMESTIC AND INTERNATIONAL EXPORT LAWS AND REGULATIONS THAT APPLY TO THE SOFTWARE OR OTHER MATERIALS YOU OBTAIN FROM OUR SITE.
  - summary: Weapons end uses
    text: You further agree that no Products received from Gimbal will be directly or indirectly employed in missile technology, sensitive nuclear, or chemical biological weapons end uses or in any manner transferred to any party for any such end use.
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
name: Paedae
provenance_date: '2026-11-10'
provider_name: Paedae
provider_slug: paedae
slug: paedae-eligibility
source_date: '2026-11-10'
source_filename: paedae-eligibility.yml
source_heading: Eligibility
source_page: https://infillion.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paedae\naid: paedae\nurl: https://infillion.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if the Site is being used on behalf of an organization such as your employer, you have the authority to\n    bind such organization to the TOU\nrestricted_uses:\n- summary: Export restrictions\n  text: YOU MUST COMPLY WITH ALL DOMESTIC AND INTERNATIONAL EXPORT LAWS AND REGULATIONS THAT APPLY TO THE SOFTWARE\n    OR OTHER MATERIALS YOU OBTAIN FROM OUR SITE.\n- summary: Weapons end uses\n  text: You further agree that no Products\
  \ received from Gimbal will be directly or indirectly employed in missile\n    technology, sensitive nuclear, or chemical biological weapons end uses or in any manner transferred to any party\n    for any such end use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paedae/eligibility/paedae-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Paedae's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Proximity
- Location
- Beacons
- Geofencing
- Mobile SDK
- Advertising
- Marketing
---
