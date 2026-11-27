---
api_specs:
- filename: flock-safety-alerts-api-openapi.yml
  format: yaml
  label: Flock Safety Alerts API
  slug: flock-safety-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-alerts-api-openapi.yml
- filename: flock-safety-cad-events-api-openapi.yml
  format: yaml
  label: Flock Safety CAD Events API
  slug: flock-safety-cad-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-cad-events-api-openapi.yml
- filename: flock-safety-custom-hotlists-api-openapi.yml
  format: yaml
  label: Flock Safety Custom Hotlists API
  slug: flock-safety-custom-hotlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-custom-hotlists-api-openapi.yml
- filename: flock-safety-devices-api-openapi.yml
  format: yaml
  label: Flock Safety Devices API
  slug: flock-safety-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-devices-api-openapi.yml
- filename: flock-safety-lpr-hotlist-alert-subscriptions-api-openapi.yml
  format: yaml
  label: Flock Safety LPR Hotlist Alert Subscriptions API
  slug: flock-safety-lpr-hotlist-alert-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-lpr-hotlist-alert-subscriptions-api-openapi.yml
- filename: flock-safety-plate-reads-api-openapi.yml
  format: yaml
  label: Flock Safety Plate Reads API
  slug: flock-safety-plate-reads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-plate-reads-api-openapi.yml
- filename: flock-safety-tracked-subject-types-api-openapi.yml
  format: yaml
  label: Flock Safety Tracked Subject Types API
  slug: flock-safety-tracked-subject-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-tracked-subject-types-api-openapi.yml
- filename: flock-safety-tracked-subjects-api-openapi.yml
  format: yaml
  label: Flock Safety Tracked Subjects API
  slug: flock-safety-tracked-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-tracked-subjects-api-openapi.yml
- filename: flock-safety-vehicle-images-api-openapi.yml
  format: yaml
  label: Flock Safety Vehicle Images API
  slug: flock-safety-vehicle-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-vehicle-images-api-openapi.yml
- filename: flock-safety-oauth2-api-openapi.yml
  format: yaml
  label: Flock Safety O Auth2 API
  slug: flock-safety-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flock-safety/openapi/flock-safety-oauth2-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Customer shall access the Flock Services through the Web Interface only ... (c) from and within the United States.
  entity_types:
  - text: All obligations of the Customer under the Agreement which require the expenditure of public funds are conditioned on the availability of said funds appropriated for that purpose.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use in violation of law or to harass or stalk
    text: use Flock Property or any part or aspect thereof in violation of Applicable Law or to mislead, harass, stalk, or otherwise impose upon or violate the rights of any person
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
name: Flock Safety
provenance_date: '2026-11-09'
provider_name: Flock Safety
provider_slug: flock-safety
slug: flock-safety-eligibility
source_date: '2026-11-09'
source_filename: flock-safety-eligibility.yml
source_heading: Eligibility
source_page: https://www.flocksafety.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flock Safety\naid: flock-safety\nurl: https://www.flocksafety.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Customer shall access the Flock Services through the Web Interface only ... (c) from and within the United\n    States.\nentity_types:\n- type: government\n  text: All obligations of the Customer under the Agreement which require the expenditure of public funds are conditioned\n    on the availability of said funds appropriated for that purpose.\nrestricted_uses:\n- summary: No use in violation of law or to harass or stalk\n  text: use\
  \ Flock Property or any part or aspect thereof in violation of Applicable Law or to mislead, harass, stalk,\n    or otherwise impose upon or violate the rights of any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flock-safety/eligibility/flock-safety-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Flock Safety's own page on 2026-11-09.
synthetic: false
tags:
- Company
- American Dynamism
- Public Safety
- Law Enforcement
- License Plate Recognition
- LPR
- Physical Security
- Surveillance
- Computer Vision
- Webhook
- Geolocation
- CAD
---
