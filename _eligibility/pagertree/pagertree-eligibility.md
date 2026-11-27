---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is entering into this Agreement on behalf of a company, or other legal entity (“Entity”), Customer represents that Customer has the authority to bind such Entity
    type: business
  - text: If Customer is the U.S. Government or any agency or department thereof (“Government”), Government agrees that the Service and the documentation are licensed hereunder (a) only as a commercial item
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Customer shall access and use the Service only in accordance with this Agreement and all applicable laws and regulations
  - summary: US export controls
    text: The Service is subject to United States export controls. The Service may not be downloaded or otherwise exported or re-exported in violation of United States export laws.
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
name: PagerTree
provenance_date: '2026-11-10'
provider_name: PagerTree
provider_slug: pagertree
slug: pagertree-eligibility
source_date: '2026-11-10'
source_filename: pagertree-eligibility.yml
source_heading: Eligibility
source_page: https://pagertree.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PagerTree\naid: pagertree\nurl: https://pagertree.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If Customer is entering into this Agreement on behalf of a company, or other legal entity (“Entity”), Customer\n    represents that Customer has the authority to bind such Entity\n- type: government\n  text: If Customer is the U.S. Government or any agency or department thereof (“Government”), Government agrees\n    that the Service and the documentation are licensed hereunder (a) only as a commercial item\nrestricted_uses:\n\
  - summary: Lawful use only\n  text: Customer shall access and use the Service only in accordance with this Agreement and all applicable laws\n    and regulations\n- summary: US export controls\n  text: The Service is subject to United States export controls. The Service may not be downloaded or otherwise\n    exported or re-exported in violation of United States export laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pagertree/eligibility/pagertree-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from PagerTree's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
