---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using or accessing the Website on behalf of an organization, you accept these Terms on behalf of that organization.
    type: business
  minimum_age:
    text: LS Retail’s services and website are not intended for individuals under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Software download or use requires customer agreement
    text: You may not download or install the Software or utilize LS Retail’s services, unless you are a party to (or a user covered under) the applicable Customer Agreement.
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
name: LS Retail
provenance_date: '2026-11-09'
provider_name: LS Retail
provider_slug: ls-retail
slug: ls-retail-eligibility
source_date: '2026-11-09'
source_filename: ls-retail-eligibility.yml
source_heading: Eligibility
source_page: https://www.lsretail.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LS Retail\naid: ls-retail\nurl: https://www.lsretail.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using or accessing the Website on behalf of an organization, you accept these Terms on behalf\n    of that organization.\nrestricted_uses:\n- summary: Software download or use requires customer agreement\n  text: You may not download or install the Software or utilize LS Retail’s services, unless you are a party to\n    (or a user covered under) the applicable Customer Agreement.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: LS Retail’s services and website are not intended for individuals under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/ls-retail/eligibility/ls-retail-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from LS Retail's own page on 2026-11-09.
synthetic: false
tags:
- Retail
- Point-of-Sale
- Business Management
- Microsoft Dynamics
- Omnichannel
- Software
---
