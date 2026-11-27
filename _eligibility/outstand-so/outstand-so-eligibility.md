---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to a U.S. Government embargo or designated as a "terrorist supporting" country
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, organization, or other legal entity, you represent and warrant that you have the authority to bind such entity to these Terms.
    type: business
  - text: allows developers and businesses to programmatically schedule, manage, and publish content across multiple social media platforms
    type: developer
  minimum_age:
    text: Be at least 18 years of age or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Post malicious, harmful, defamatory, obscene, or illegal content
  - summary: Harassment or hate speech
    text: Engage in harassment, hate speech, or incitement of violence
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: outstand-so
provenance_date: '2026-11-10'
provider_name: outstand-so
provider_slug: outstand-so
slug: outstand-so-eligibility
source_date: '2026-11-10'
source_filename: outstand-so-eligibility.yml
source_heading: Eligibility
source_page: https://www.outstand.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: outstand-so\naid: outstand-so\nurl: https://www.outstand.so/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to a U.S. Government embargo or designated as\n    a \"terrorist supporting\" country\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, organization, or other legal entity, you\n    represent and warrant that you have the authority to bind such entity to these Terms.\n- type: developer\n  text: allows developers and businesses to programmatically schedule,\
  \ manage, and publish content across multiple\n    social media platforms\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Post malicious, harmful, defamatory, obscene, or illegal content\n- summary: Harassment or hate speech\n  text: Engage in harassment, hate speech, or incitement of violence\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/outstand-so/eligibility/outstand-so-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from outstand-so's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- MCP
- Software-as-a-Service
---
