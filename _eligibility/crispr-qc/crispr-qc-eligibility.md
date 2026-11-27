---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled, operated and administered by CQC from our offices within the USA. If you access the Service from a location outside the USA, you are responsible for compliance with all local laws.
  minimum_age:
    text: If you are under 18, you may use crisprqc.com only with permission of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: As a condition of your use of the Site, you warrant to CQC that you will not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: CRISPR QC
provenance_date: '2026-11-09'
provider_name: CRISPR QC
provider_slug: crispr-qc
slug: crispr-qc-eligibility
source_date: '2026-11-09'
source_filename: crispr-qc-eligibility.yml
source_heading: Eligibility
source_page: https://crisprqc.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CRISPR QC\naid: crispr-qc\nurl: https://crisprqc.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled, operated and administered by CQC from our offices within the USA. If you access\n    the Service from a location outside the USA, you are responsible for compliance with all local laws.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: As a condition of your use of the Site, you warrant to CQC that you will not use the Site for any purpose\n    that is unlawful or prohibited by these Terms.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may use crisprqc.com only with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/crispr-qc/eligibility/crispr-qc-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CRISPR QC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Gene Editing
- Analytics
- Platform
---
