---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering with hobbyDB as a business entity, you represent that you have the authority to legally bind that entity.
    type: business
  minimum_age:
    text: You may not use the Site if you are under the age of 18 and do not have permission from your parent or legal guardian to do so
    value: '18'
  restricted_uses:
  - summary: Real weapons sale or trade
    text: Attempting to use the site to arrange or facilitate sale or trade of real weapons of any sort (including but not limited to replica handguns) is for now expressly forbidden
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we are unable to verify or authenticate any information you provide to us
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: hobbyDB
provenance_date: '2026-11-09'
provider_name: hobbyDB
provider_slug: hobbydb
slug: hobbydb-eligibility
source_date: '2026-11-09'
source_filename: hobbydb-eligibility.yml
source_heading: Eligibility
source_page: https://help.hobbydb.com/support/solutions/articles/36000264473-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hobbyDB\naid: hobbydb\nurl: https://help.hobbydb.com/support/solutions/articles/36000264473-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering with hobbyDB as a business entity, you represent that you have the authority to legally\n    bind that entity.\nrestricted_uses:\n- summary: Real weapons sale or trade\n  text: Attempting to use the site to arrange or facilitate sale or trade of real weapons of any sort (including\n    but not limited to replica handguns) is for now expressly forbidden\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: we are unable to verify or authenticate any information you provide to us\nminimum_age:\n  value: '18'\n  text: You may not use the Site if you are under the age of 18 and do not have permission from your parent or legal\n    guardian to do so\n"
source_yaml_url: https://artifacts.apis.io/hobbydb/eligibility/hobbydb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from hobbyDB's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collectibles
- Marketplace
- Database
- Collection
- E-Commerce
- Auctions
- Community
---
