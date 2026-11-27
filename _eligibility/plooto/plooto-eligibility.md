---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: The Accounts Payable Offering enables Payors to transmit payments to Plooto via pre-authorized debit (“PAD”) in Canada and automated clearing house (“ACH”) in the United States
  entity_types:
  - text: YOU ARE USING THE PLOOTO PLATFORM FOR A BUSINESS PURPOSE AND ARE NOT ACTING FOR PERSONAL, FAMILY OR HOUSEHOLD PURPOSES
    type: business
  - text: The Plooto Platform is available for use by Users at bookkeeping and accounting firms
    type: other
  minimum_age:
    text: YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION
    value: age of majority
  restricted_uses:
  - summary: Personal, family or household use
    text: YOU ARE USING THE PLOOTO PLATFORM FOR A BUSINESS PURPOSE AND ARE NOT ACTING FOR PERSONAL, FAMILY OR HOUSEHOLD PURPOSES
  - summary: Payments to sanctioned parties
    text: Users in the United States are prohibited from attempting to directly or indirectly to send payments to any sanctioned country, person, group or entity under U.S. law.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to activate any Plooto Account, Plooto will need to perform certain background verifications for the purposes of verifying your or your business’s identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Plooto
provenance_date: '2026-11-10'
provider_name: Plooto
provider_slug: plooto
slug: plooto-eligibility
source_date: '2026-11-10'
source_filename: plooto-eligibility.yml
source_heading: Eligibility
source_page: https://www.plooto.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plooto\naid: plooto\nurl: https://www.plooto.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: The Accounts Payable Offering enables Payors to transmit payments to Plooto via pre-authorized debit (“PAD”)\n    in Canada and automated clearing house (“ACH”) in the United States\nentity_types:\n- type: business\n  text: YOU ARE USING THE PLOOTO PLATFORM FOR A BUSINESS PURPOSE AND ARE NOT ACTING FOR PERSONAL, FAMILY OR HOUSEHOLD\n    PURPOSES\n- type: other\n  text: The Plooto Platform is available for use by Users at bookkeeping\
  \ and accounting firms\nrestricted_uses:\n- summary: Personal, family or household use\n  text: YOU ARE USING THE PLOOTO PLATFORM FOR A BUSINESS PURPOSE AND ARE NOT ACTING FOR PERSONAL, FAMILY OR HOUSEHOLD\n    PURPOSES\n- summary: Payments to sanctioned parties\n  text: Users in the United States are prohibited from attempting to directly or indirectly to send payments to\n    any sanctioned country, person, group or entity under U.S. law.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to activate any Plooto Account, Plooto will need to perform certain background verifications for\n    the purposes of verifying your or your business’s identity\nminimum_age:\n  value: age of majority\n  text: YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/plooto/eligibility/plooto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Plooto's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Canada
- Accounts Payable
- Accounts Receivable
- AP Automation
- AR Automation
- Bill Pay
- Money Transfer
- EFT
- ACH
- Cross-Border
- Small Business
---
