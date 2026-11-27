---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a platform where roofing professionals (“Service Providers” or “you”) can obtain tools to assist in providing roofing measurements, estimating and workflow automation tools.
    type: other
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    value: legal age
  restricted_uses:
  - summary: Commercializing Services as separate business
    text: Commercializes or leverages Roofr Services as a separate business;
  - summary: Spam or auto-responders
    text: Runs Maillist, Listserv, any form of auto-responder or “spam” on the Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Roofr may screen Service Providers and/or Customers, but all users should exercise caution and common sense to protect personal safety and property when interacting with other users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Roofr
provenance_date: '2026-11-10'
provider_name: Roofr
provider_slug: roofr
slug: roofr-eligibility
source_date: '2026-11-10'
source_filename: roofr-eligibility.yml
source_heading: Eligibility
source_page: https://roofr.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roofr\naid: roofr\nurl: https://roofr.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: a platform where roofing professionals (“Service Providers” or “you”) can obtain tools to assist in providing\n    roofing measurements, estimating and workflow automation tools.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Commercializing\
  \ Services as separate business\n  text: Commercializes or leverages Roofr Services as a separate business;\n- summary: Spam or auto-responders\n  text: Runs Maillist, Listserv, any form of auto-responder or “spam” on the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Roofr may screen Service Providers and/or Customers, but all users should exercise caution and common sense\n    to protect personal safety and property when interacting with other users.\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/roofr/eligibility/roofr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Roofr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Roofing
- Construction
- CRM
- Proposals
- Payments
- Field Service Management
- Contractor Software
---
