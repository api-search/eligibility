---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that neither Customer nor any User or Customer App End User is located in any such country or on any such list. Export restrictions reference U.S. embargoed countries, but no country list is named.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical or hazardous use
    text: Customer agrees not to make any such use of any Licensed Materials and Customer Apps.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Customer may only distribute Customer Apps to Customer App End Users subject to a EULA approved in writing in advance for each such Customer App by Onymos.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Onymos
provenance_date: '2026-11-10'
provider_name: Onymos
provider_slug: onymos
slug: onymos-eligibility
source_date: '2026-11-10'
source_filename: onymos-eligibility.yml
source_heading: Eligibility
source_page: https://onymos.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onymos\naid: onymos\nurl: https://onymos.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that neither Customer nor any User or Customer App End User is located\n    in any such country or on any such list. Export restrictions reference U.S. embargoed countries, but no country\n    list is named.\nentity_types: []\nrestricted_uses:\n- summary: Safety-critical or hazardous use\n  text: Customer agrees not to make any such use of any Licensed Materials and Customer Apps.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: Customer may only distribute Customer Apps to Customer App End Users subject to a EULA approved in writing\n    in advance for each such Customer App by Onymos.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onymos/eligibility/onymos-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Onymos's own page on 2026-11-10.
synthetic: false
tags:
- Features as a Service
- SDK
- Application Development
- Mobile
- Document Processing
- Intelligent Document Processing
- OCR
- Healthcare
- Life Sciences
- Authentication
- Chat
- Push Notifications
- Geolocation
- Payments
- IoT
- No-Data Architecture
- Components
---
