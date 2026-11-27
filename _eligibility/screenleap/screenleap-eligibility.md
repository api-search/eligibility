---
api_specs:
- filename: screenleap-screen-shares-api-openapi.yml
  format: yaml
  label: Screenleap Screen Shares API
  slug: screenleap-screen-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenleap/openapi/screenleap-screen-shares-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms and using the Services on behalf of a company, organization, government, or other legal entity, you represent and warrant that you are authorized to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted-person use
    text: You may use the Services only if you can form a binding contract with Screenleap and are not a person barred from receiving services under the laws of the United States or other applicable jurisdiction.
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
name: Screenleap
provenance_date: '2026-11-10'
provider_name: Screenleap
provider_slug: screenleap
slug: screenleap-eligibility
source_date: '2026-11-10'
source_filename: screenleap-eligibility.yml
source_heading: Eligibility
source_page: https://www.screenleap.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Screenleap\naid: screenleap\nurl: https://www.screenleap.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms and using the Services on behalf of a company, organization, government,\n    or other legal entity, you represent and warrant that you are authorized to do so.\nrestricted_uses:\n- summary: Restricted-person use\n  text: You may use the Services only if you can form a binding contract with Screenleap and are not a person barred\n    from receiving services under the laws of the United States\
  \ or other applicable jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/screenleap/eligibility/screenleap-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Screenleap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screen Sharing
- Video Conferencing
- Screen Recording
- Collaboration
- Real-Time Communication
- WebRTC
- Embeddable
- Developer API
---
