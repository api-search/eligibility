---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export Control: the Service may not be exported or re-exported into any United States embargoed countries'
  entity_types:
  - text: To use the Service you must be, and represent and warrant that you are, of legal age (18 years of age or older or otherwise of legal age in your jurisdiction)
    type: individual
  - text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: 18 years of age or older or otherwise of legal age in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use of the Service for any illegal purpose, or any other purpose not expressly permitted in these Terms, is strictly prohibited.
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
name: Nexamp
provenance_date: '2026-11-10'
provider_name: Nexamp
provider_slug: nexamp
slug: nexamp-eligibility
source_date: '2026-11-10'
source_filename: nexamp-eligibility.yml
source_heading: Eligibility
source_page: https://www.nexamp.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nexamp\naid: nexamp\nurl: https://www.nexamp.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export Control: the Service may not be exported or re-exported into any United States embargoed countries'\nentity_types:\n- type: individual\n  text: To use the Service you must be, and represent and warrant that you are, of legal age (18 years of age or\n    older or otherwise of legal age in your jurisdiction)\n- type: business\n  text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to\
  \ agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use of the Service for any illegal purpose, or any other purpose not expressly permitted in these Terms,\n    is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 18 years of age or older or otherwise of legal age in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/nexamp/eligibility/nexamp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nexamp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Solar
- Clean Energy
- Community Solar
- Renewable Energy
- Energy Storage
- Sustainability
- Utilities
---
