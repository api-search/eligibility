---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - KP
    - IR
    - SY
    - CU
    served: []
    text: You represent that you are not (a) located in, organized in, or resident of a jurisdiction subject to comprehensive sanctions or embargoes, including without limitation North Korea, Iran, Syria, Cuba, or the Crimea/Donetsk/Luhansk regions
  entity_types:
  - text: You represent that you are at least the age of majority in your jurisdiction and have legal capacity to enter into this agreement.
    type: individual
  - text: If you are entering into these Terms on behalf of an organization or entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You represent that you are at least the age of majority in your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: SLP program limited to accredited users
    text: SLP participation is limited to accredited, KYC-verified users and is subject to all applicable securities, AML/CTF, and sanctions requirements.
  - summary: No unregistered securities or derivatives trading
    text: no unregistered or unqualified trading of securities or derivatives is permitted on the Platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- KP
- IR
- SY
- CU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BlocPal
provenance_date: '2026-11-09'
provider_name: BlocPal
provider_slug: blocpal
slug: blocpal-eligibility
source_date: '2026-11-09'
source_filename: blocpal-eligibility.yml
source_heading: Eligibility
source_page: https://www.blocpal.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlocPal\naid: blocpal\nurl: https://www.blocpal.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - KP\n  - IR\n  - SY\n  - CU\n  text: You represent that you are not (a) located in, organized in, or resident of a jurisdiction subject to comprehensive\n    sanctions or embargoes, including without limitation North Korea, Iran, Syria, Cuba, or the Crimea/Donetsk/Luhansk\n    regions\nentity_types:\n- type: individual\n  text: You represent that you are at least the age of majority in your jurisdiction and have legal capacity to\n    enter into this agreement.\n- type: business\n\
  \  text: If you are entering into these Terms on behalf of an organization or entity, you represent that you have\n    authority to bind that entity.\nrestricted_uses:\n- summary: SLP program limited to accredited users\n  text: SLP participation is limited to accredited, KYC-verified users and is subject to all applicable securities,\n    AML/CTF, and sanctions requirements.\n- summary: No unregistered securities or derivatives trading\n  text: no unregistered or unqualified trading of securities or derivatives is permitted on the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You represent that you are at least the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/blocpal/eligibility/blocpal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from BlocPal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Digital Banking
- Wealth Management
- Blockchain
---
