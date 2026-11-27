---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: be at least the age of majority in your jurisdiction of residence (or have consent from a parent/guardian)
    type: individual
  - text: If you are agreeing to these Terms on behalf of a company or other organization, you represent and warrant to FutureFit AI that you have the authority to bind such organization
    type: business
  minimum_age:
    text: be at least the age of majority in your jurisdiction of residence (or have consent from a parent/guardian)
    value: age of majority
  restricted_uses:
  - summary: Single-user accounts
    text: Accounts are for single users only and may not be shared by more than one individual.
  - summary: Prohibited content and conduct
    text: (e) interfere with or disrupt the Site, Services or servers or networks connected to the Site
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
name: FutureFit AI
provenance_date: '2026-11-09'
provider_name: FutureFit AI
provider_slug: futurefit-ai
slug: futurefit-ai-eligibility
source_date: '2026-11-09'
source_filename: futurefit-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.futurefit.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FutureFit AI\naid: futurefit-ai\nurl: https://www.futurefit.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: be at least the age of majority in your jurisdiction of residence (or have consent from a parent/guardian)\n- type: business\n  text: If you are agreeing to these Terms on behalf of a company or other organization, you represent and warrant\n    to FutureFit AI that you have the authority to bind such organization\nrestricted_uses:\n- summary: Single-user accounts\n  text: Accounts are for single users only\
  \ and may not be shared by more than one individual.\n- summary: Prohibited content and conduct\n  text: (e) interfere with or disrupt the Site, Services or servers or networks connected to the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: be at least the age of majority in your jurisdiction of residence (or have consent from a parent/guardian)\n"
source_yaml_url: https://artifacts.apis.io/futurefit-ai/eligibility/futurefit-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from FutureFit AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workforce
- Artificial Intelligence
- Career Navigation
- Talent
- Human Resources
- Economic Development
- Enterprise
---
