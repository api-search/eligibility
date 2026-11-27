---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'any individual or entity who accesses or uses: Our public websites'
    type: individual
  - text: If you are using the Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  - text: Use of Paratus by the U.S. Government or any other public-sector entity is subject to the terms of the applicable government contract and any mandatory statutory or regulatory requirements.
    type: government
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: No sensitive data on public site or unapproved environments
    text: For our public website and for any Paratus-hosted environment that has not been clearly identified to you by the mission owner or contracting authority as authorized to handle CUI or other controlled information, you must not submit classified information, CUI, PHI, Social Security numbers, or other mission-critical or sensitive operational data.
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
name: Paratus
provenance_date: '2026-11-10'
provider_name: Paratus
provider_slug: paratus
slug: paratus-eligibility
source_date: '2026-11-10'
source_filename: paratus-eligibility.yml
source_heading: Eligibility
source_page: https://www.getparatus.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paratus\naid: paratus\nurl: https://www.getparatus.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'any individual or entity who accesses or uses: Our public websites'\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms\n- type: government\n  text: Use of Paratus by the U.S. Government or any other public-sector entity is subject to the terms of the applicable\n    government contract\
  \ and any mandatory statutory or regulatory requirements.\nrestricted_uses:\n- summary: No sensitive data on public site or unapproved environments\n  text: For our public website and for any Paratus-hosted environment that has not been clearly identified to you\n    by the mission owner or contracting authority as authorized to handle CUI or other controlled information, you\n    must not submit classified information, CUI, PHI, Social Security numbers, or other mission-critical or sensitive\n    operational data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/paratus/eligibility/paratus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Paratus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Military
- Knowledge Management
- Security
---
