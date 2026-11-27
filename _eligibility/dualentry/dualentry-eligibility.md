---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: if you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
    value: '13'
  restricted_uses:
  - summary: No professional advice reliance
    text: NO PART OF THE SERVICES SHOULD BE CONSTRUED AS PROFESSIONAL ADVICE OF ANY KIND (INCLUDING FINANCIAL PLANNING, BUSINESS, EMPLOYMENT, INVESTMENT, ACCOUNTING, TAX, AND/OR LEGAL ADVICE).
  - summary: No account sharing
    text: You will not share your DualEntry User ID, account or password with anyone
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
name: DualEntry
provenance_date: '2026-11-09'
provider_name: DualEntry
provider_slug: dualentry
slug: dualentry-eligibility
source_date: '2026-11-09'
source_filename: dualentry-eligibility.yml
source_heading: Eligibility
source_page: https://www.dualentry.com/legal/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DualEntry\naid: dualentry\nurl: https://www.dualentry.com/legal/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: if you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: No professional advice reliance\n  text: NO PART OF THE SERVICES\
  \ SHOULD BE CONSTRUED AS PROFESSIONAL ADVICE OF ANY KIND (INCLUDING FINANCIAL PLANNING,\n    BUSINESS, EMPLOYMENT, INVESTMENT, ACCOUNTING, TAX, AND/OR LEGAL ADVICE).\n- summary: No account sharing\n  text: You will not share your DualEntry User ID, account or password with anyone\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/dualentry/eligibility/dualentry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from DualEntry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Accounting
- ERP
- Finance
- Financial Operations
- Bookkeeping
- Revenue Recognition
- Fintech
---
