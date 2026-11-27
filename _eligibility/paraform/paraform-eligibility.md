---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you've received your parent's or guardian's permission to use the Services
    value: null
  restricted_uses:
  - summary: Children under 16
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age
  - summary: Employer use of Candidate Information
    text: No Employer may collect any information from or relating to Candidates (“Candidate Information”), via the Services, or otherwise, beyond what is necessary for the Candidate to apply for a job.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Every Employer onboarded to Paraform would have received a recruiting agreement that needs to be signed before using our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Paraform
provenance_date: '2026-11-10'
provider_name: Paraform
provider_slug: paraform
slug: paraform-eligibility
source_date: '2026-11-10'
source_filename: paraform-eligibility.yml
source_heading: Eligibility
source_page: https://www.paraform.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paraform\naid: paraform\nurl: https://www.paraform.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Children under 16\n  text: We do not knowingly collect or solicit personally\
  \ identifiable information from children under 16 years\n    of age\n- summary: Employer use of Candidate Information\n  text: No Employer may collect any information from or relating to Candidates (“Candidate Information”), via the\n    Services, or otherwise, beyond what is necessary for the Candidate to apply for a job.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Every Employer onboarded to Paraform would have received a recruiting agreement that needs to be signed\n    before using our Services.\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you've received your parent's or guardian's permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/paraform/eligibility/paraform-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Paraform's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recruiting
- Hiring
- Talent
- Marketplace
- Human Resources
- AI Agents
- ATS Integration
---
