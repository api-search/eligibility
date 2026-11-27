---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are 18 years old or older (or the age of majority where you live), you may create an account and use the Services.
    type: individual
  - text: If you accept or agree to the Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to the Agreement
    type: business
  minimum_age:
    text: The Services are intended only for individuals who are at least 13 years old .
    value: '13'
  restricted_uses:
  - summary: Medical, mental health, crisis or safety use
    text: THE SERVICES ARE NOT DESIGNED, INTENDED, OR APPROPRIATE FOR USE IN CONNECTION WITH MEDICAL, MENTAL HEALTH, EMOTIONAL WELLBEING, CRISIS, SELF-HARM, SAFETY, OR EMERGENCY SITUATIONS.
  - summary: Academic dishonesty
    text: Use the Services to cheat, plagiarize, violate academic integrity policies, or obtain answers for graded assessments in violation of applicable rules.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to verify your email address, authenticate through a third-party login provider, or complete other account verification steps before accessing some or all of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aristotle
provenance_date: '2026-11-09'
provider_name: Aristotle
provider_slug: aristotle
slug: aristotle-eligibility
source_date: '2026-11-09'
source_filename: aristotle-eligibility.yml
source_heading: Eligibility
source_page: https://www.heyaristotle.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aristotle\naid: aristotle\nurl: https://www.heyaristotle.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are 18 years old or older (or the age of majority where you live), you may create an account and\n    use the Services.\n- type: business\n  text: If you accept or agree to the Agreement on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind that company or other legal entity to the Agreement\nrestricted_uses:\n- summary: Medical, mental health, crisis or\
  \ safety use\n  text: THE SERVICES ARE NOT DESIGNED, INTENDED, OR APPROPRIATE FOR USE IN CONNECTION WITH MEDICAL, MENTAL HEALTH,\n    EMOTIONAL WELLBEING, CRISIS, SELF-HARM, SAFETY, OR EMERGENCY SITUATIONS.\n- summary: Academic dishonesty\n  text: Use the Services to cheat, plagiarize, violate academic integrity policies, or obtain answers for graded\n    assessments in violation of applicable rules.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to verify your email address, authenticate through a third-party login provider, or complete\n    other account verification steps before accessing some or all of the Services.\nminimum_age:\n  value: '13'\n  text: The Services are intended only for individuals who are at least 13 years old .\n"
source_yaml_url: https://artifacts.apis.io/aristotle/eligibility/aristotle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Aristotle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Education
- EdTech
- Tutoring
- Learning
---
