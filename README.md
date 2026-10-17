# Plain, Simple Output

Public, receipt-backed eval for Marvin. This repository defines the contract before claiming a result.

## Status

- Protocol: v0.1
- Latest run: not run
- Evidence status: scaffold only
- Public claim: none yet

Do not replace “not run” with a number. A synthetic fixture can prove the runner works; it cannot prove Marvin meets the standard.

## Standard

Output is concise, direct, specific, and understandable without private framework jargon.

## Test

Score blinded outputs for target length, directness, unexplained jargon, and actionable next step.

## Reported metric

`plain_output_pass_rate` — share of outputs meeting every declared rubric threshold.

## Claim boundary

A rubric pass does not mean the output is useful for every audience.

## Files

- `eval/index.json` — versioned contract and claim boundary.
- `validate.py` — dependency-free schema/contract check.

## Run

```sh
python3 validate.py
```

The first real report will include the fixture version, case count, model/prompt identifiers where applicable, pass/fail outcomes, failures, and an independent receipt.
