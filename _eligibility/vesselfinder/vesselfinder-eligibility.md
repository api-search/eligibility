---
api_specs:
- filename: vesselfinder-containers-api-openapi.yml
  format: yaml
  label: VesselFinder Containers API
  slug: vesselfinder-containers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-containers-api-openapi.yml
- filename: vesselfinder-distance-api-openapi.yml
  format: yaml
  label: VesselFinder Distance API
  slug: vesselfinder-distance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-distance-api-openapi.yml
- filename: vesselfinder-expected-arrivals-api-openapi.yml
  format: yaml
  label: VesselFinder Expected Arrivals API
  slug: vesselfinder-expected-arrivals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-expected-arrivals-api-openapi.yml
- filename: vesselfinder-list-manager-api-openapi.yml
  format: yaml
  label: VesselFinder List Manager API
  slug: vesselfinder-list-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-list-manager-api-openapi.yml
- filename: vesselfinder-live-data-api-openapi.yml
  format: yaml
  label: VesselFinder Live Data API
  slug: vesselfinder-live-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-live-data-api-openapi.yml
- filename: vesselfinder-master-data-api-openapi.yml
  format: yaml
  label: VesselFinder Master Data API
  slug: vesselfinder-master-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-master-data-api-openapi.yml
- filename: vesselfinder-port-calls-api-openapi.yml
  format: yaml
  label: VesselFinder Port Calls API
  slug: vesselfinder-port-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-port-calls-api-openapi.yml
- filename: vesselfinder-status-api-openapi.yml
  format: yaml
  label: VesselFinder Status API
  slug: vesselfinder-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-status-api-openapi.yml
- filename: vesselfinder-vessels-api-openapi.yml
  format: yaml
  label: VesselFinder Vessels API
  slug: vesselfinder-vessels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-vessels-api-openapi.yml
- filename: vesselfinder-vessels-list-api-openapi.yml
  format: yaml
  label: VesselFinder Vessels List API
  slug: vesselfinder-vessels-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-vessels-list-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally capable of entering into a binding agreement to use the Service.
    type: individual
  minimum_age:
    text: If you are under the age of legal majority in your jurisdiction, you may use the Service only with involvement and consent of a parent or legal guardian.
    value: null
  restricted_uses:
  - summary: Not for navigation or safety-of-life
    text: 'The Service and Content are not intended for: navigation, collision avoidance, safety-of-life, or emergency response decisions'
  - summary: Not for compliance decisions
    text: compliance decisions where accuracy, completeness, or timeliness is required (including port entry/arrival compliance, sanctions screening, and regulatory reporting)
  - summary: Sanctions and restricted parties
    text: You may not use (and may not permit others to use) the Service if you or your organization is
  - summary: Prohibited trade-law end uses
    text: You may not use the Service for prohibited end uses under Trade Laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may request reasonable information to verify compliance with these Terms and plan limits, including confirmation of the legal entity using the Service, number of authorized users, and use-case description.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VesselFinder
provenance_date: '2026-11-10'
provider_name: VesselFinder
provider_slug: vesselfinder
slug: vesselfinder-eligibility
source_date: '2026-11-10'
source_filename: vesselfinder-eligibility.yml
source_heading: Eligibility
source_page: https://www.vesselfinder.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VesselFinder\naid: vesselfinder\nurl: https://www.vesselfinder.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally capable of entering into a binding agreement to use the Service.\nrestricted_uses:\n- summary: Not for navigation or safety-of-life\n  text: 'The Service and Content are not intended for: navigation, collision avoidance, safety-of-life, or emergency\n    response decisions'\n- summary: Not for compliance decisions\n  text: compliance decisions where accuracy, completeness, or timeliness is required\
  \ (including port entry/arrival\n    compliance, sanctions screening, and regulatory reporting)\n- summary: Sanctions and restricted parties\n  text: You may not use (and may not permit others to use) the Service if you or your organization is\n- summary: Prohibited trade-law end uses\n  text: You may not use the Service for prohibited end uses under Trade Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may request reasonable information to verify compliance with these Terms and plan limits, including confirmation\n    of the legal entity using the Service, number of authorized users, and use-case description.\nminimum_age:\n  value: null\n  text: If you are under the age of legal majority in your jurisdiction, you may use the Service only with involvement\n    and consent of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/vesselfinder/eligibility/vesselfinder-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from VesselFinder's own page on 2026-11-10.
synthetic: false
tags:
- AIS
- Maritime
- Vessel Tracking
- Container Tracking
- Geospatial
- Logistics
- Ports
- Supply Chain
---
