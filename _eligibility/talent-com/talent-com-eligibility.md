---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Talent.com entity varies by user location: Canada, United States, France, United Kingdom, Switzerland or elsewhere in the world. Arbitration applies to Job Seekers resident in the United States.'
  entity_types:
  - text: If you are an individual looking for employment or employment information, whether you are a registered user or not (“Job Seeker”)
    type: individual
  - text: If you are an individual or a legal person looking for Job Seekers or looking to make employment opportunities and information available to Job Seekers, on your behalf as an employer or on behalf of others, including but not limited to, as an agency (“Employers”)
    type: business
  minimum_age:
    text: You may agree to these Terms of Service only if you have reached the age of eighteen (18) years old or the legal age in your jurisdiction to form binding contracts under applicable law.
    value: '18'
  restricted_uses:
  - summary: Job Ads must be for real employment
    text: aims at collecting candidates' profiles without the intent of filling a real and current job opening
  - summary: Employers may not charge applicants
    text: requires applicants to pay to apply, pay for training, pay for training materials
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Talent.com may, under its sole discretion, require Employer User Content and/or Employers to be verified to prevent fraud or abuse of our Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Talent.com
provenance_date: '2026-11-10'
provider_name: Talent.com
provider_slug: talent-com
slug: talent-com-eligibility
source_date: '2026-11-10'
source_filename: talent-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.talent.com:443/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talent.com\naid: talent-com\nurl: https://www.talent.com:443/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Talent.com entity varies by user location: Canada, United States, France, United Kingdom, Switzerland or\n    elsewhere in the world. Arbitration applies to Job Seekers resident in the United States.'\nentity_types:\n- type: individual\n  text: If you are an individual looking for employment or employment information, whether you are a registered\n    user or not (“Job Seeker”)\n- type: business\n  text: If you are an individual or a legal\
  \ person looking for Job Seekers or looking to make employment opportunities\n    and information available to Job Seekers, on your behalf as an employer or on behalf of others, including but\n    not limited to, as an agency (“Employers”)\nrestricted_uses:\n- summary: Job Ads must be for real employment\n  text: aims at collecting candidates' profiles without the intent of filling a real and current job opening\n- summary: Employers may not charge applicants\n  text: requires applicants to pay to apply, pay for training, pay for training materials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Talent.com may, under its sole discretion, require Employer User Content and/or Employers to be verified\n    to prevent fraud or abuse of our Services\nminimum_age:\n  value: '18'\n  text: You may agree to these Terms of Service only if you have reached the age of eighteen (18) years old or the\n    legal age in your jurisdiction to form binding contracts under applicable\
  \ law.\n"
source_yaml_url: https://artifacts.apis.io/talent-com/eligibility/talent-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Talent.com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job Search
- Recruiting
- Employment
- Technology
---
