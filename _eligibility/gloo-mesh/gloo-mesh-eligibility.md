---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is intended for business users who are at least 18 years old.
    type: business
  minimum_age:
    text: This Website is intended for business users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No automated or bot access
    text: (5) you will not access the Website through automated or non-human means, whether through a bot, script or otherwise
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
name: Gloo Mesh
provenance_date: '2026-11-09'
provider_name: Gloo Mesh
provider_slug: gloo-mesh
slug: gloo-mesh-eligibility
source_date: '2026-11-09'
source_filename: gloo-mesh-eligibility.yml
source_heading: Eligibility
source_page: https://legal.solo.io/#website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gloo Mesh\naid: gloo-mesh\nurl: https://legal.solo.io/#website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This Website is intended for business users who are at least 18 years old.\nrestricted_uses:\n- summary: No automated or bot access\n  text: (5) you will not access the Website through automated or non-human means, whether through a bot, script\n    or otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended for business\
  \ users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/gloo-mesh/eligibility/gloo-mesh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gloo Mesh's own page on 2026-11-09.
synthetic: false
tags:
- Istio
- Kubernetes
- Multi-Cluster
- Open Source
- Service Mesh
- Envoy
- Kubernetes CRDs
- Protobuf
- Policy Enforcement
- Observability
---
