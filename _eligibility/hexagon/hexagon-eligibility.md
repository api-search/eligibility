---
api_specs:
- filename: developerportal
  format: yaml
  label: Hexagon Nexus API
  slug: nexus-api
  spec_type: OpenAPI
  url: https://nexus.hexagon.com/developerportal
- filename: hexagon-eam-ion-api-openapi.yml
  format: yaml
  label: HxGN EAM REST API
  slug: hxgn-eam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hexagon/openapi/hexagon-eam-ion-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Territory means the country in which the Customer is incorporated and registered, unless otherwise defined in the Agreement.
  entity_types:
  - text: The HxDR services offered under these Terms of Use are intended for commercial use by business customers only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical reliance
    text: rely solely on HxDR Content or services available on HxDR for any plans, technical drawings, models, feasibility studies or other construction or business decisions and activities where the use or failure of HxDR, including any HxDR Content, could lead to death, personal injury, or environmental damage.
  - summary: Export control
    text: The Customer agrees in particular not to export or re-export, directly or indirectly, HxDR Content, software or technical data that are intended to be used for any purposes prohibited by the restrictions under the applicable laws
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
name: Hexagon
provenance_date: '2026-11-09'
provider_name: Hexagon
provider_slug: hexagon
slug: hexagon-eligibility
source_date: '2026-11-09'
source_filename: hexagon-eligibility.yml
source_heading: Eligibility
source_page: https://geocloud.hexagon.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hexagon\naid: hexagon\nurl: https://geocloud.hexagon.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Territory means the country in which the Customer is incorporated and registered, unless otherwise defined\n    in the Agreement.\nentity_types:\n- type: business\n  text: The HxDR services offered under these Terms of Use are intended for commercial use by business customers\n    only.\nrestricted_uses:\n- summary: Safety-critical reliance\n  text: rely solely on HxDR Content or services available on HxDR for any plans, technical drawings,\
  \ models, feasibility\n    studies or other construction or business decisions and activities where the use or failure of HxDR, including\n    any HxDR Content, could lead to death, personal injury, or environmental damage.\n- summary: Export control\n  text: The Customer agrees in particular not to export or re-export, directly or indirectly, HxDR Content, software\n    or technical data that are intended to be used for any purposes prohibited by the restrictions under the applicable\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hexagon/eligibility/hexagon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Hexagon's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Metrology
- Quality Inspection
- Digital Factory
- Production Monitoring
- Industrial IoT
- Smart Manufacturing
- Geospatial
---
