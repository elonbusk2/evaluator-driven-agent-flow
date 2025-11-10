# Contributing to EDAF

Thank you for your interest in contributing to EDAF (Evaluator-Driven Agent Flow)!

## 📋 Contribution Guidelines

### Reporting Issues

- Use GitHub Issues to report bugs or suggest features
- Provide clear reproduction steps for bugs
- Include relevant environment details (OS, Claude Code version, language/framework)
- Search existing issues before creating new ones

### Suggesting Features

- Open an issue with the "enhancement" label
- Describe the use case and expected behavior
- Explain how it fits with EDAF's self-adapting philosophy

### Pull Requests

1. **Fork the repository** and create a feature branch from `main`
2. **Follow existing style:**
   - No exaggerated claims or unsupported percentages
   - Keep documentation clear and concise
   - Use technical accuracy over marketing language
3. **Test your changes:**
   - Verify with a real project
   - Ensure evaluators/workers function correctly
4. **Document your changes:**
   - Update relevant README sections
   - Add examples if introducing new features
5. **Submit PR** with clear description of changes

### What We Accept

✅ **Bug fixes** - Fix existing functionality issues
✅ **Documentation improvements** - Clarify or expand existing docs
✅ **New language/framework support** - Add detection patterns with examples
✅ **Test coverage improvements** - Add validation for edge cases
✅ **Evaluator enhancements** - Improve detection accuracy or scoring logic

### What We Don't Accept

❌ **Breaking changes** without prior discussion
❌ **Unsupported performance claims** (e.g., "95% success rate" without data)
❌ **Template-based approaches** (EDAF is self-adapting, not template-based)
❌ **Marketing language** (e.g., "revolutionary", "game-changing")
❌ **Changes that increase maintenance burden** (e.g., language-specific templates)

## 🔍 Code Review Process

1. **Submit PR** with clear description
2. **Maintainer reviews** (may take 1-7 days)
3. **Address feedback** if requested
4. **Maintainer merges** approved PRs

All PRs require maintainer approval before merging.

## 🎯 Adding New Language/Framework Support

To add support for a new language or framework:

1. **Update detection logic** in relevant evaluator/worker
2. **Add detection patterns** (package files, file extensions, etc.)
3. **Test with real project** in that language/framework
4. **Submit PR** with:
   - Example project structure
   - Detection pattern additions
   - Test results showing it works

**Example:**
```markdown
## Adding Kotlin Support

Modified files:
- `.claude/evaluators/code-quality-evaluator-v1-self-adapting.md`
  - Added `build.gradle.kts` detection
  - Added `ktlint` as linter option

Tested with:
- Sample Kotlin project (link to repo)
- Linter detection: ✅ Works
- Scoring: ✅ Accurate
```

## 📝 Documentation Style Guide

- Use clear, technical language
- Avoid subjective claims without evidence
- Use "Recommended" instead of "Ideal" or "Perfect"
- Use "Minimal" instead of "0 hours/year"
- Use specific thresholds instead of vague percentages

**Good:**
- "Recommended test ratio: 70% unit, 20% integration, 10% e2e"
- "Maintenance: Minimal"
- "Automatically detects language from package files"

**Bad:**
- "Perfect test ratio: 70/20/10"
- "Maintenance: 0 hours/year"
- "95% success rate in language detection"

## 🤝 Community

- Be respectful and constructive
- Focus on technical merit
- Provide evidence for claims
- Keep discussions professional

## ❓ Questions?

Open an issue for discussion before starting large contributions. We're happy to provide guidance!

---

**Thank you for helping make EDAF better!** 🚀
