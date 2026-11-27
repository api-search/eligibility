---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: all fees are quoted and billed in Canadian dollars in the case of Canadian Users (plus any and all applicable taxes, including without limitation HST, GST, and PST as applicable) and in U.S. Dollars in the case of United States Users
  entity_types:
  - text: you must be at least age of majority in your jurisdiction of residence and have the capacity to form a legally binding contract with VendorPM
    type: individual
  - text: If you are entering into these Terms on behalf of a company or other legal entity
    type: business
  minimum_age:
    text: you must be at least age of majority in your jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Direct competitors of VendorPM
    text: Access or use the Site or Service if you are a direct competitor of VendorPM, unless prior written consent is obtained from VendorPM.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: should we ask a user for proof of identification, and that identification is not submitted in the allotted time, we reserve the right, in our sole discretion, to cancel any transaction associated with that user
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VendorPM
provenance_date: '2026-11-10'
provider_name: VendorPM
provider_slug: vendorpm
slug: vendorpm-eligibility
source_date: '2026-11-10'
source_filename: vendorpm-eligibility.yml
source_heading: Eligibility
source_page: https://vendorpm.com/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VendorPM\naid: vendorpm\nurl: https://vendorpm.com/terms-of-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: all fees are quoted and billed in Canadian dollars in the case of Canadian Users (plus any and all applicable\n    taxes, including without limitation HST, GST, and PST as applicable) and in U.S. Dollars in the case of United\n    States Users\nentity_types:\n- type: individual\n  text: you must be at least age of majority in your jurisdiction of residence and have the capacity to form a legally\n    binding contract with VendorPM\n\
  - type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity\nrestricted_uses:\n- summary: Direct competitors of VendorPM\n  text: Access or use the Site or Service if you are a direct competitor of VendorPM, unless prior written consent\n    is obtained from VendorPM.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: should we ask a user for proof of identification, and that identification is not submitted in the allotted\n    time, we reserve the right, in our sole discretion, to cancel any transaction associated with that user\nminimum_age:\n  value: age of majority\n  text: you must be at least age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/vendorpm/eligibility/vendorpm-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from VendorPM's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- PropTech
- Procurement
- Real Estate
- Property Management
- Vendor Management
- Contract Management
- Compliance
---
