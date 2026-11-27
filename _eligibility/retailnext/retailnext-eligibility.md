---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal, non-commercial use of this web site
    type: individual
  - text: Reports are for your internal business use only
    type: business
  - text: RetailNext provides the software downloaded from this web site to U.S. Government users with "RESTRICTED RIGHTS."
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use of site
    text: solely on your computer and for your personal, non-commercial use of this web site.
  - summary: Internal business use of Reports
    text: Reports are for your internal business use only
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
name: RetailNext
provenance_date: '2026-11-10'
provider_name: RetailNext
provider_slug: retailnext
slug: retailnext-eligibility
source_date: '2026-11-10'
source_filename: retailnext-eligibility.yml
source_heading: Eligibility
source_page: https://retailnext.net/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RetailNext\naid: retailnext\nurl: https://retailnext.net/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal, non-commercial use of this web site\n- type: business\n  text: Reports are for your internal business use only\n- type: government\n  text: RetailNext provides the software downloaded from this web site to U.S. Government users with \"RESTRICTED\n    RIGHTS.\"\nrestricted_uses:\n- summary: Non-commercial personal use of site\n  text: solely on your computer and for your personal, non-commercial\
  \ use of this web site.\n- summary: Internal business use of Reports\n  text: Reports are for your internal business use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/retailnext/eligibility/retailnext-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from RetailNext's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Retail Analytics
- In-Store Analytics
- Shopper Analytics
- Foot Traffic
- Loss Prevention
- Computer Vision
- Physical Retail
---
