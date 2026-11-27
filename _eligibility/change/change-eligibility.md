---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Nonprofit organizations (“NPOs”) that are tax-exempt under applicable law may register for an account on our platform by providing proof of tax-exempt status
    type: nonprofit
  - text: If you are accepting these Terms and policies and using our services on behalf of a company, organization, government, or other legal entity, you represent and warrant that you are authorized to do so.
    type: business
  minimum_age:
    text: Our platform is for people who are at least 16 years of age except in the United States where you may use our platform if you are at least 13 years of age or older.
    value: '16'
  restricted_uses:
  - summary: Use of signer data limited
    text: You may only use signer information to contact signers about your work, and you may not sell, share, or use that data for any other purpose.
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: Once verified, Verified NPOs who start petitions may access the signer list for their own petitions
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Change.org
provenance_date: '2026-11-09'
provider_name: Change.org
provider_slug: change
slug: change-eligibility
source_date: '2026-11-09'
source_filename: change-eligibility.yml
source_heading: Eligibility
source_page: https://www.change.org/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Change.org\naid: change\nurl: https://www.change.org/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: Nonprofit organizations (“NPOs”) that are tax-exempt under applicable law may register for an account on\n    our platform by providing proof of tax-exempt status\n- type: business\n  text: If you are accepting these Terms and policies and using our services on behalf of a company, organization,\n    government, or other legal entity, you represent and warrant that you are authorized to do so.\nrestricted_uses:\n\
  - summary: Use of signer data limited\n  text: You may only use signer information to contact signers about your work, and you may not sell, share, or\n    use that data for any other purpose.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: Once verified, Verified NPOs who start petitions may access the signer list for their own petitions\nminimum_age:\n  value: '16'\n  text: Our platform is for people who are at least 16 years of age except in the United States where you may use\n    our platform if you are at least 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/change/eligibility/change-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Change.org's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Petitions
- Advocacy
- Social Impact
- Civic Engagement
- Social Change
---
