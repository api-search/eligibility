---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Basic use of the Platform is offered free of charge to teachers and other educators.
    type: individual
  - text: Schools or Districts or State Education Agencies (“Schools”) may purchase a license or subscription to use the Platform for its educator community
    type: other
  - text: Technology Providers may create accounts on the site to access and use the Platform to obtain data and reports relating to the Educational Tools of the Technology Provider.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No self-review by technology providers
    text: Technology Providers are not permitted to review their own products, or review the products of other Technology Providers.
  - summary: No paid reviews
    text: you agree that any Reviews you provide will be true, honest and based on your own professional experience and judgment and that you will not provide Reviews for payment or other compensation.
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
name: LearnPlatform
provenance_date: '2026-11-09'
provider_name: LearnPlatform
provider_slug: learnplatform
slug: learnplatform-eligibility
source_date: '2026-11-09'
source_filename: learnplatform-eligibility.yml
source_heading: Eligibility
source_page: https://www.instructure.com/policies/learnplatform-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LearnPlatform\naid: learnplatform\nurl: https://www.instructure.com/policies/learnplatform-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Basic use of the Platform is offered free of charge to teachers and other educators.\n- type: other\n  text: Schools or Districts or State Education Agencies (“Schools”) may purchase a license or subscription to use\n    the Platform for its educator community\n- type: business\n  text: Technology Providers may create accounts on the site to access and use the Platform to obtain\
  \ data and reports\n    relating to the Educational Tools of the Technology Provider.\nrestricted_uses:\n- summary: No self-review by technology providers\n  text: Technology Providers are not permitted to review their own products, or review the products of other Technology\n    Providers.\n- summary: No paid reviews\n  text: you agree that any Reviews you provide will be true, honest and based on your own professional experience\n    and judgment and that you will not provide Reviews for payment or other compensation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/learnplatform/eligibility/learnplatform-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from LearnPlatform's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- Learning
- Analytics
- Student Data Privacy
- Evidence
- Instructure
---
