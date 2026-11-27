---
api_specs:
- filename: ovh-cloud-cloud-api-openapi.yml
  format: yaml
  label: OVH Cloud API
  slug: ovh-cloud-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ovh-cloud/openapi/ovh-cloud-cloud-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE AN INDIVIDUAL ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk applications
    text: (H) in any application or situation where failure of the OVHcloud Services could lead to the death or serious bodily injury of any person
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: For purposes of fraud prevention, OVHcloud may require Customer to provide documentation verifying their identity and payment information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OVH Cloud
provenance_date: '2026-11-10'
provider_name: OVH Cloud
provider_slug: ovh-cloud
slug: ovh-cloud-eligibility
source_date: '2026-11-10'
source_filename: ovh-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://us.ovhcloud.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OVH Cloud\naid: ovh-cloud\nurl: https://us.ovhcloud.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: IF YOU ARE AN INDIVIDUAL ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY\nrestricted_uses:\n- summary: High-risk applications\n  text: (H) in any application or situation where failure of the OVHcloud Services could lead to the death or serious\n    bodily injury of any person\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: For purposes\
  \ of fraud prevention, OVHcloud may require Customer to provide documentation verifying their\n    identity and payment information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ovh-cloud/eligibility/ovh-cloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from OVH Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- Compute
- Servers
- Hosting
---
