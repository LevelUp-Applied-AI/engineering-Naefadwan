# Pull Request

## Description

Summarize what changed and why. Be specific — mention the files, functions, or modules affected and explain the problem this PR solves or the feature it adds. Give reviewers enough context so they don't need to dig through Slack or issues to understand the change.

**Example:** "Updated `parse_csv()` in `utils.py` to raise a `ValueError` on missing headers instead of silently returning `None`. This fixes a bug where downstream code crashed with an unhelpful `AttributeError`."

Fixes # (issue)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update

## How Has This Been Tested?

1. Activate the virtual environment: `source .venv/bin/activate` (Mac/Linux) or `source .venv/Scripts/activate` (Windows)
2. Install dependencies: `pip install -r requirements.txt`
3. Run the test suite: `pytest`
4. Confirm expected output — describe what success looks like (e.g., "All 24 tests pass, including the new `test_missing_header` case")

- [ ] Existing tests pass locally (`pytest` exits with no failures)
- [ ] New tests added that cover the changed behavior

## Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules