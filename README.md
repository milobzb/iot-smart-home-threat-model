IoT Smart Home Threat Modeling – Artifact Repository

This repository contains the full project artifacts for the final report “IoT Threat Modeling for Smart Home Devices.”
The materials here support the methodology, STRIDE analysis, evaluation metrics, and figures described in the report.

Repository Contents
1. LaTeX Source (/latex/)

Includes:

main.tex – complete LaTeX source for the final report

references.bib (if applicable)

Auxiliary files used for compilation (figures, tables, etc.)

2. Final PDF (Final_Report.pdf)

A compiled version of the full 6-page report following the required structure:

Abstract

Introduction & Problem Statement

Related Work

Methodology

Evaluation & Results

Discussion & Challenges

Concluding Remarks

References

3. Pipeline Figure (pipeline.pdf)

A standalone copy of the methodology pipeline diagram used in Section 3 of the report.
This figure illustrates the threat modeling workflow including asset enumeration, STRIDE mapping, and mitigation analysis.

4. STRIDE Matrices (/matrices/)

Structured threat modeling tables used to:

Document assets, flows, and trust boundaries

Assign STRIDE categories

Record risk ratings

Map recommended mitigations

Identify responsible parties (User / Vendor / ISP)

These matrices are provided in editable CSV/Excel form for reuse.

Project Description

This project applies the STRIDE threat modeling framework to a realistic smart home environment consisting of:

A consumer router

A hub or mobile app

A camera

A smart lock

Cloud service components

The analysis identifies threats, rates risk, and assigns mitigations across all STRIDE categories.
Evaluation metrics include:

STRIDE Coverage

Prioritization Quality

Mitigation Completeness

The repository provides all artifacts needed to reproduce or extend the threat model.
