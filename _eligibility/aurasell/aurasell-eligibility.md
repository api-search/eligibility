---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual using the Site on behalf of an entity, you represent and warrant that you have the legal authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: The Site and the Site Materials are not directed to, or designed and intended, for use by children under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You shall not, without prior U.S. government authorization, export, re-export, or transfer the Sites, the Site Materials or any other Aurasell products, services or technology
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
name: Aurasell
provenance_date: '2026-11-09'
provider_name: Aurasell
provider_slug: aurasell
slug: aurasell-eligibility
source_date: '2026-11-09'
source_filename: aurasell-eligibility.yml
source_heading: Eligibility
source_page: https://www.aurasell.ai/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aurasell\naid: aurasell\nurl: https://www.aurasell.ai/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an individual using the Site on behalf of an entity, you represent and warrant that you have\n    the legal authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Export restrictions\n  text: You shall not, without prior U.S. government authorization, export, re-export, or transfer the Sites, the\n    Site Materials or any other Aurasell products, services or technology\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and the Site Materials are not directed to, or designed and intended, for use by children under\n    the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/aurasell/eligibility/aurasell-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aurasell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- CRM
- Platform
---
