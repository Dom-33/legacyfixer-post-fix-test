# LegacyFixer post-fix test gate

Controlled repository for validating LegacyFixer behavior when post-fix tests fail.

Expected behavior:

- pip-audit can fix the vulnerable Python dependency
- npm ci succeeds
- npm test fails intentionally
- LegacyFixer must skip PR creation because post-fix tests fail
