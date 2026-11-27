---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not be located in an embargoed country or listed on any U.S. Government list of prohibited or restricted parties
  entity_types:
  - text: Individuals, groups, and entities may register to compete in a prize challenge or competition
    type: individual
  - text: businesses connect with independent technology experts and pre-formed expert teams
    type: business
  - text: or government buyer
    type: government
  minimum_age:
    text: you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Under-18 users barred from accounts and postings
    text: Create an account, post an RFP, post a Job, or apply to a Job if you are not over 18 years of age
  - summary: No collecting other users' personal information
    text: Collect any personal information about other users
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: CrowdPlat does not verify the identity, qualifications, or responses of any Candidate and is not liable for any misrepresentation or inaccuracy in Candidate submissions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crowdplat
provenance_date: '2026-11-09'
provider_name: Crowdplat
provider_slug: crowdplat
slug: crowdplat-eligibility
source_date: '2026-11-09'
source_filename: crowdplat-eligibility.yml
source_heading: Eligibility
source_page: https://www.crowdplat.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crowdplat\naid: crowdplat\nurl: https://www.crowdplat.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not be located in an embargoed country or listed on any U.S. Government list of prohibited or restricted\n    parties\nentity_types:\n- type: individual\n  text: Individuals, groups, and entities may register to compete in a prize challenge or competition\n- type: business\n  text: businesses connect with independent technology experts and pre-formed expert teams\n- type: government\n  text: or government buyer\nrestricted_uses:\n- summary: Under-18 users barred from\
  \ accounts and postings\n  text: Create an account, post an RFP, post a Job, or apply to a Job if you are not over 18 years of age\n- summary: No collecting other users' personal information\n  text: Collect any personal information about other users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: CrowdPlat does not verify the identity, qualifications, or responses of any Candidate and is not liable\n    for any misrepresentation or inaccuracy in Candidate submissions.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/crowdplat/eligibility/crowdplat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Crowdplat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crowdsourcing
- Recruiting
- Hiring
- Artificial Intelligence
- Talent Marketplace
- Software Development
- Consulting
---
