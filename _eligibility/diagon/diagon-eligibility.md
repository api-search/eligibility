---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only available to users at least 18 years of age.
    type: individual
  - text: If registering or using the Site on behalf of a company, you represent and warrant that you are the Company's authorized representative with authority to bind it to these Terms.
    type: business
  minimum_age:
    text: The Site is only available to users at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export controls
    text: Not subject to economic sanctions and export controls (OFAC, BIS, UN, EU, UK OFSI, ECJU)
  - summary: Criminal or money-laundering links
    text: Funds are not connected with criminal activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users agree to provide all information and assistance reasonably requested to comply with Anti-Money Laundering processes and laws.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Diagon
provenance_date: '2026-11-09'
provider_name: Diagon
provider_slug: diagon
slug: diagon-eligibility
source_date: '2026-11-09'
source_filename: diagon-eligibility.yml
source_heading: Eligibility
source_page: https://diagon.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diagon\naid: diagon\nurl: https://diagon.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only available to users at least 18 years of age.\n- type: business\n  text: If registering or using the Site on behalf of a company, you represent and warrant that you are the Company's\n    authorized representative with authority to bind it to these Terms.\nrestricted_uses:\n- summary: Sanctions and export controls\n  text: Not subject to economic sanctions and export controls (OFAC, BIS, UN, EU, UK OFSI, ECJU)\n- summary:\
  \ Criminal or money-laundering links\n  text: Funds are not connected with criminal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users agree to provide all information and assistance reasonably requested to comply with Anti-Money Laundering\n    processes and laws.\nminimum_age:\n  value: '18'\n  text: The Site is only available to users at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/diagon/eligibility/diagon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Diagon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- Industrial Equipment
- Procurement
- Marketplace
- Supply Chain
- Equipment Sourcing
- Artificial Intelligence
---
