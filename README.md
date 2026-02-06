# operational-risk-radar

## Data Requirements

This diagnostic uses a single item-level sales dataset with the following required fields:
- date
- item
- revenue
- quantity
- contribution_margin

Accepted formats: CSV or XLSX (single sheet)

The system is designed to work with imperfect operational data. All outputs are framed as early risk signals, not definitive conclusions.

## Diagnostic Outputs

This diagnostic produces three client-facing outputs:

1. Snapshot Risk Brief  
   A short written summary highlighting early margin and cost-leakage risks, framed to support informed decision-making.

2. Signal Summary Table  
   A simplified evidence table showing where margin erosion signals are forming across key items.

3. Decision Framing Notes  
   Context on how to interpret the findings, including limitations and appropriate use cases.
