---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Because international information is provided on our Site, not all products or programs mentioned will be available in your country.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or criminal activity
    text: Engage in or promote any illegal or criminal activity such as child pornography, gambling, or piracy.
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
name: Cisco ACI
provenance_date: '2026-11-09'
provider_name: Cisco ACI
provider_slug: cisco-aci
slug: cisco-aci-eligibility
source_date: '2026-11-09'
source_filename: cisco-aci-eligibility.yml
source_heading: Eligibility
source_page: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cisco ACI\naid: cisco-aci\nurl: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Because international information is provided on our Site, not all products or programs mentioned will be\n    available in your country.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or criminal activity\n  text: Engage in or promote any illegal or criminal activity such as child pornography, gambling, or piracy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/cisco-aci/eligibility/cisco-aci-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Cisco ACI's own page on 2026-11-09.
synthetic: false
tags:
- SDN
- Data Center
- Networking
- Fabric
- Automation
- Enterprise
- Network Automation
- Infrastructure
- Controller
- REST API
---
