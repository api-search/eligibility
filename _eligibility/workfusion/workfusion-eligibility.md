---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Disclosing information about the Services or WorkFusion software to anyone located, organized, or resident in a country that is the target of countrywide sanctions is restricted, naming Cuba, Iran, North Korea, Syria and the Crimea region of Ukraine.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk use
    text: You may not use the Services in any circumstance or fashion where a failure of the Services could result in death or physical injury.
  - summary: Regulated health or financial data
    text: You may not use or, or allow others to use the Services, to store or process sensitive or otherwise regulated health or financial information
  - summary: Sanctioned or illicit parties
    text: 'in a way that would allow access to the Services.by any person or entity involved with or suspected of involvement with: illegal gambling; terrorism; narcotics trafficking; arms trafficking'
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
name: WorkFusion
provenance_date: '2026-11-10'
provider_name: WorkFusion
provider_slug: workfusion
slug: workfusion-eligibility
source_date: '2026-11-10'
source_filename: workfusion-eligibility.yml
source_heading: Eligibility
source_page: https://www.workfusion.com/aup/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WorkFusion\naid: workfusion\nurl: https://www.workfusion.com/aup/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Disclosing information about the Services or WorkFusion software to anyone located, organized, or resident\n    in a country that is the target of countrywide sanctions is restricted, naming Cuba, Iran, North Korea, Syria\n    and the Crimea region of Ukraine.\nentity_types: []\nrestricted_uses:\n- summary: High-risk use\n  text: You may not use the Services in any circumstance or fashion where a failure of the Services could result\n    in death or physical injury.\n\
  - summary: Regulated health or financial data\n  text: You may not use or, or allow others to use the Services, to store or process sensitive or otherwise regulated\n    health or financial information\n- summary: Sanctioned or illicit parties\n  text: 'in a way that would allow access to the Services.by any person or entity involved with or suspected of\n    involvement with: illegal gambling; terrorism; narcotics trafficking; arms trafficking'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workfusion/eligibility/workfusion-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 4 quoted statements, read from WorkFusion's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- Financial Crime Compliance
- AML
- Sanctions Screening
- KYC
- Transaction Monitoring
- Adverse Media Monitoring
- Intelligent Document Processing
- RPA
- Banking
---
