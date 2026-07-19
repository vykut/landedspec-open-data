# LandedSpec open construction-import data

Reusable buyer-side registers for comparing construction-material import quotes without inventing supplier, freight, customs, tax, or compliance outcomes.

This repository is an owned distribution of selected datasets already published by [LandedSpec](https://landedspec.com/). The linked LandedSpec HTML page is the authoritative landing page for each dataset, including its explanation, sources, professional-confirmation boundaries, and current version.

## Datasets

| Dataset | Use | Authoritative landing page | Download |
| --- | --- | --- | --- |
| Aluminium profile tooling and finish acceptance register | Join the controlled drawing and tool or die to the actual finishing plant, pretreatment/coating system, production batch, packing revision, and repeat-order release. | [China aluminium profile pretreatment for Germany](https://landedspec.com/import/powder-coated-aluminium-profiles-to-germany/) | [CSV](datasets/aluminium-profile-tooling-finish-acceptance-register.csv) |
| Supplier document requirements list template | Build a 27-line supplier document requirements list/SDRL with milestones, formats, reviews, resubmissions, and final-dossier controls. | [Supplier document requirements before deposit](https://landedspec.com/blog/supplier-documents-before-deposit/) | [CSV](datasets/supplier-document-requirements-list-template.csv) |
| FOB, CIF, and DAP construction quote comparison | Reconcile quote inclusions, physical handoffs, risk transfer, import responsibilities, destination charges, and buyer evidence across Incoterms® scopes. | [FOB vs CIF vs DAP for construction materials](https://landedspec.com/blog/compare-fob-cif-dap-construction-materials/) | [CSV](datasets/fob-cif-dap-construction-quote-comparison.csv) |

`manifest.json` records each file's SHA-256 digest, byte size, row count, direct LandedSpec distribution, and HTML canonical.

## Use and limits

- Treat blank, `buyer_to_confirm`, and unresolved fields as unresolved—not as zero or approval.
- Confirm the exact product, supplier, route, contract, customs, tax, compliance, insurance, and acceptance facts with the responsible professionals.
- The files do not recommend a supplier or origin, assign a customs code or duty, quote a freight rate, approve a shipment, or replace the official Incoterms® rules.
- `Incoterms` is a registered trademark of the International Chamber of Commerce. LandedSpec is not affiliated with or endorsed by ICC or the source institutions named in the files.

## Reuse and citation

Unless a dataset states otherwise, LandedSpec-authored selection, calculations, labels, and explanatory notes are available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribute LandedSpec, link to the authoritative landing page, cite the named source dataset and date, and identify LandedSpec-added calculations or labels.

Underlying source data remains subject to its provider's rights and terms. See [LandedSpec dataset reuse and source terms](https://landedspec.com/methodology/#dataset-reuse) and [LICENSE.md](LICENSE.md).

For software and research tooling, `CITATION.cff` provides a machine-readable collection citation. For an individual dataset, cite the title and authoritative landing page listed above.

## Corrections

Open a GitHub issue with the dataset filename, row or field, current source, and proposed correction. Do not include supplier quotes, prices, personal data, contracts, invoices, or other confidential commercial information. You can also use the [LandedSpec corrections route](https://landedspec.com/methodology/#corrections).
