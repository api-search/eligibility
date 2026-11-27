---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Scripbox complies with all regulations and compliances as per Indian law. If you are accessing our Services from any jurisdiction outside India, the onus of compliance with the local laws lies on you.
  entity_types:
  - text: If you are entering into this Agreement on behalf of a legal entity you represent that you have the authority to bind such entity to these terms and conditions
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Service restrictions by residence, nationality, age, wealth
    text: Some of the Services, provided by us or our Service Partners, may have restrictions on use depending on criteria such as, but not limited to, your place of residence, nationality, age, wealth, source of income/wealth etc.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Scripbox will establish your identity on its online Services by means of a phone number or email and will authenticate it by either a password selected by you, or a one time password (OTP)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scripbox
provenance_date: '2026-11-10'
provider_name: Scripbox
provider_slug: scripbox
slug: scripbox-eligibility
source_date: '2026-11-10'
source_filename: scripbox-eligibility.yml
source_heading: Eligibility
source_page: https://scripbox.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scripbox\naid: scripbox\nurl: https://scripbox.com/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Scripbox complies with all regulations and compliances as per Indian law. If you are accessing our Services\n    from any jurisdiction outside India, the onus of compliance with the local laws lies on you.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a legal entity you represent that you have the authority\n    to bind such entity to these terms and conditions\nrestricted_uses:\n- summary: Service restrictions\
  \ by residence, nationality, age, wealth\n  text: Some of the Services, provided by us or our Service Partners, may have restrictions on use depending on\n    criteria such as, but not limited to, your place of residence, nationality, age, wealth, source of income/wealth\n    etc.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Scripbox will establish your identity on its online Services by means of a phone number or email and will\n    authenticate it by either a password selected by you, or a one time password (OTP)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scripbox/eligibility/scripbox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Scripbox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Financial Services
- Wealth Management
- Mutual Funds
- Investing
- Fintech
- India
---
