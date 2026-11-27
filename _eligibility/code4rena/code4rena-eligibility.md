---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may use the Services only if you are not a Prohibited Person and are not barred from using the Services under applicable law. Prohibited Person means any person or entity subject to sanctions or trade restrictions under applicable laws or located in an embargoed jurisdiction.
  entity_types:
  - text: If you are 18 or older (or the age of majority where you reside), you represent and warrant that you have the legal capacity to enter into these Terms.
    type: individual
  - text: If you accept these Terms on behalf of an entity, you represent and warrant that you have authority to bind that entity and that “you” refers to such entity.
    type: business
  minimum_age:
    text: If you are under the age of majority but at least 13 years old (a “Minor”), you may use the Services and participate in Audits and Private Audits only if your parent or legal guardian (A) has reviewed and accepted these Terms on your behalf
    value: '13'
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: We may require identity verification, KYB/KYC, and tax information (for example, IRS Forms W-8/W-9) from you or, where you are a Minor, from your parent or legal guardian before permitting participation or payment of any Award.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Code4rena
provenance_date: '2026-11-09'
provider_name: Code4rena
provider_slug: code4rena
slug: code4rena-eligibility
source_date: '2026-11-09'
source_filename: code4rena-eligibility.yml
source_heading: Eligibility
source_page: https://docs.code4rena.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Code4rena\naid: code4rena\nurl: https://docs.code4rena.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may use the Services only if you are not a Prohibited Person and are not barred from using the Services\n    under applicable law. Prohibited Person means any person or entity subject to sanctions or trade restrictions\n    under applicable laws or located in an embargoed jurisdiction.\nentity_types:\n- type: individual\n  text: If you are 18 or older (or the age of majority where you reside), you represent and warrant that you have\n    the legal\
  \ capacity to enter into these Terms.\n- type: business\n  text: If you accept these Terms on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity and that “you” refers to such entity.\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: We may require identity verification, KYB/KYC, and tax information (for example, IRS Forms W-8/W-9) from\n    you or, where you are a Minor, from your parent or legal guardian before permitting participation or payment\n    of any Award.\nminimum_age:\n  value: '13'\n  text: If you are under the age of majority but at least 13 years old (a “Minor”), you may use the Services and\n    participate in Audits and Private Audits only if your parent or legal guardian (A) has reviewed and accepted\n    these Terms on your behalf\n"
source_yaml_url: https://artifacts.apis.io/code4rena/eligibility/code4rena-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Code4rena's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Smart Contracts
- Web3
- DeFi
- Auditing
- Bug Bounty
- Blockchain
---
