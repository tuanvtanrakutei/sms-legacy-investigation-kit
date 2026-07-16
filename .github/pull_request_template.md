## Summary

Describe the problem and the smallest change that solves it.

## Contract impact

- [ ] No contract or output change
- [ ] Schema/manifest change
- [ ] Orchestration/role/wave change
- [ ] Access/build-context change
- [ ] Phase or derived-output change

## Validation

- [ ] `python -m compileall -q plugins/sms-kit/scripts plugins/sms-kit/tests`
- [ ] `python plugins/sms-kit/scripts/validate_structure.py --package plugins/sms-kit --repository-root .`
- [ ] `python -m pytest -q`
- [ ] PowerShell adapter parsed on Windows, if changed

## Safety and evidence

- [ ] Uses synthetic data only
- [ ] Contains no database, credential, DSN, customer, A01, or proprietary artifacts
- [ ] Clearly states untested live runtime paths
- [ ] Updates `CHANGELOG.md` when appropriate
