# Review and fix code issues in one pass

Review and fix code issues in a single pass.

## Steps

1. **Analyze the diff** for potential logic, syntax, or style bugs.
2. **Run static analysis** (e.g. eslint, golangci-lint) and address findings.
3. **Check for regressions** against existing patterns in the repo.
4. **Apply safe fixes** without changing intended behavior.
5. **Re-review** the final code to ensure no new issues were introduced.

## Output

Show reasoning for each fix in inline comments (or in the response) so the change is traceable.
