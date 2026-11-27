---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: the User has attained the age to legally accept these Terms and Conditions as per the Applicable Law
    value: null
  restricted_uses:
  - summary: Services for oneself only
    text: the User can access or avail the Services only for oneself and not on behalf of any third party, unless specifically approved by the Cogoport Group
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: the Cogoport Group does not validate, verify or otherwise authenticate, certify, confirm or endorse the Users or the Information provided
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cogoport
provenance_date: '2026-11-09'
provider_name: Cogoport
provider_slug: cogoport
slug: cogoport-eligibility
source_date: '2026-11-09'
source_filename: cogoport-eligibility.yml
source_heading: Eligibility
source_page: https://www.cogoport.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cogoport\naid: cogoport\nurl: https://www.cogoport.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Services for oneself only\n  text: the User can access or avail the Services only for oneself and not on behalf of any third party, unless\n    specifically approved by the Cogoport Group\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: the Cogoport Group does not validate, verify or otherwise authenticate, certify, confirm or endorse the\n    Users or the Information provided\n\
  minimum_age:\n  value: null\n  text: the User has attained the age to legally accept these Terms and Conditions as per the Applicable Law\n"
source_yaml_url: https://artifacts.apis.io/cogoport/eligibility/cogoport-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Cogoport's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Logistics
- Freight
- Supply Chain
- Shipping
- Trade Finance
- Customs
---
