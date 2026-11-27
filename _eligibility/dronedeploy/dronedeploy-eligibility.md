---
api_specs:
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Projects and Plans API
  slug: dronedeploy-projects-and-plans-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Maps and Exports API
  slug: dronedeploy-maps-and-exports-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Annotations and Issues API
  slug: dronedeploy-annotations-and-issues-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Uploads and Images API
  slug: dronedeploy-uploads-and-images-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Users and Organizations API
  slug: dronedeploy-users-and-organizations-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Reports API
  slug: dronedeploy-reports-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
- filename: dronedeploy.postman_collection.json
  format: json
  label: DroneDeploy Webhooks API
  slug: dronedeploy-webhooks-api
  spec_type: Postman
  url: https://artifacts.apis.io/dronedeploy/collections/dronedeploy.postman_collection.json
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer will not permit any User to access, use or export any of the foregoing in a U.S.-embargoed country or region (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)
  entity_types:
  - text: You represent that you are authorized to act on behalf of the owner of the account you are registering or using (such owner, “ Customer ” or “ you ”) and to bind them to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Military use
    text: use the Services for or in connection with any military purpose or harm or intimidation of any person or animal
  - summary: Illegal or hazardous use
    text: use or intend to use the Services for any harmful, illegal or hazardous purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DroneDeploy
provenance_date: '2026-11-09'
provider_name: DroneDeploy
provider_slug: dronedeploy
slug: dronedeploy-eligibility
source_date: '2026-11-09'
source_filename: dronedeploy-eligibility.yml
source_heading: Eligibility
source_page: https://www.dronedeploy.com/legal/master-services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DroneDeploy\naid: dronedeploy\nurl: https://www.dronedeploy.com/legal/master-services-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer will not permit any User to access, use or export any of the foregoing in a U.S.-embargoed country\n    or region (currently Cuba, Iran, North Korea, Sudan, Syria or Crimea)\nentity_types:\n- type: business\n  text: You represent that you are authorized to act on behalf of the owner of the account you are registering or\n    using (such owner, “ Customer ” or “ you ”) and to bind them to this\
  \ Agreement.\nrestricted_uses:\n- summary: Military use\n  text: use the Services for or in connection with any military purpose or harm or intimidation of any person or\n    animal\n- summary: Illegal or hazardous use\n  text: use or intend to use the Services for any harmful, illegal or hazardous purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dronedeploy/eligibility/dronedeploy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from DroneDeploy's own page on 2026-11-09.
synthetic: false
tags:
- Drone Mapping
- Reality Capture
- Aerial Analytics
- Geospatial
- GraphQL
- Photogrammetry
---
