---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals who are eighteen (18) years of age or above, or such other age of majority as may be prescribed under applicable law, are permitted to independently create an account on the Platform and access the Services in their own name and capacity.
    type: individual
  minimum_age:
    text: Where the User is below eighteen (18) years of age, access to the Platform is strictly conditional upon the knowledge, supervision, and verifiable consent of a parent or lawful guardian.
    value: '18'
  restricted_uses:
  - summary: Solicitation or commercial exploitation
    text: Misuse of counselling services or institutional data for solicitation, spamming, or commercial exploitation;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company may implement one or more reasonable authentication mechanisms, including but not limited to one-time password (OTP) verification sent to the parent’s or guardian’s registered mobile number or email address, call-based verification, digital acknowledgements, or such other lawful technical measures as may be deemed appropriate.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Collegedekho
provenance_date: '2026-11-09'
provider_name: Collegedekho
provider_slug: collegedekho
slug: collegedekho-eligibility
source_date: '2026-11-09'
source_filename: collegedekho-eligibility.yml
source_heading: Eligibility
source_page: https://www.collegedekho.com/terms-and-conditions-refund-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collegedekho\naid: collegedekho\nurl: https://www.collegedekho.com/terms-and-conditions-refund-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals who are eighteen (18) years of age or above, or such other age of majority as may be prescribed\n    under applicable law, are permitted to independently create an account on the Platform and access the Services\n    in their own name and capacity.\nrestricted_uses:\n- summary: Solicitation or commercial exploitation\n  text: Misuse of counselling services or institutional\
  \ data for solicitation, spamming, or commercial exploitation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company may implement one or more reasonable authentication mechanisms, including but not limited to\n    one-time password (OTP) verification sent to the parent’s or guardian’s registered mobile number or email address,\n    call-based verification, digital acknowledgements, or such other lawful technical measures as may be deemed\n    appropriate.\nminimum_age:\n  value: '18'\n  text: Where the User is below eighteen (18) years of age, access to the Platform is strictly conditional upon\n    the knowledge, supervision, and verifiable consent of a parent or lawful guardian.\n"
source_yaml_url: https://artifacts.apis.io/collegedekho/eligibility/collegedekho-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Collegedekho's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Technology
- India
- CollegeSearch
---
