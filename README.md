# Cobi Claude Marketplace

A curated collection of **verified, production-ready** Claude Code plugins from trusted sources. This marketplace focuses on quality over quantity, featuring only plugins that are guaranteed to work correctly.

## Installation

Add this marketplace to your Claude Code installation:

```bash
claude marketplace add https://github.com/cobibean/cobi-claude-marketplace.git
```

Then install individual plugins:

```bash
/plugin install superpowers@cobi-claude-marketplace
/plugin install code-review@cobi-claude-marketplace
```

## Available Plugins

### Superpowers by Jesse Vincent

- **superpowers** (v4.0.2) - Core skills library for Claude Code: TDD, debugging, collaboration patterns, and proven techniques
  - Author: Jesse Vincent
  - Source: [obra/superpowers](https://github.com/obra/superpowers)
  - **Highly Recommended** - Foundational skills library for professional development workflows

### Official Anthropic Plugins

#### Development Tools

- **agent-sdk-dev** (v1.0.0) - Claude Agent SDK Development Plugin
  - Author: Ashwin Bhat (Anthropic)

- **plugin-dev** (v0.1.0) - Comprehensive toolkit for developing Claude Code plugins with 7 specialized skills and guided workflow
  - Author: Daisy Hollman (Anthropic)

- **feature-dev** (v1.0.0) - Comprehensive feature development workflow with specialized agents for codebase exploration, architecture design, and quality review
  - Author: Sid Bidasaria (Anthropic)

- **frontend-design** (v1.0.0) - Frontend design skill for UI/UX implementation
  - Author: Prithvi Rajasekaran (Anthropic)

#### Code Quality & Review

- **code-review** (v1.0.0) - Automated code review for pull requests using multiple specialized agents with confidence-based scoring
  - Author: Boris Cherny (Anthropic)

- **pr-review-toolkit** (v1.0.0) - Comprehensive PR review agents specializing in comments, tests, error handling, type design, code quality, and code simplification
  - Author: Daisy (Anthropic)

#### Git Workflow

- **commit-commands** (v1.0.0) - Streamline your git workflow with simple commands for committing, pushing, and creating pull requests
  - Author: Anthropic

#### Output Styles & Learning

- **explanatory-output-style** (v1.0.0) - Adds educational insights about implementation choices and codebase patterns
  - Author: Dickson Tsai (Anthropic)

- **learning-output-style** (v1.0.0) - Interactive learning mode that requests meaningful code contributions at decision points
  - Author: Boris Cherny (Anthropic)

#### Utilities & Automation

- **hookify** (v0.1.0) - Easily create hooks to prevent unwanted behaviors by analyzing conversation patterns
  - Author: Daisy Hollman (Anthropic)

- **ralph-wiggum** (v1.0.0) - Continuous self-referential AI loops for interactive iterative development
  - Author: Daisy Hollman (Anthropic)

- **security-guidance** (v1.0.0) - Warn about potential security issues when editing files - targets command injection, XSS vulnerabilities, and dangerous coding patterns
  - Author: David Dworken (Anthropic)

- **claude-opus-4-5-migration** (v1.0.0) - Migrate your code and prompts from Sonnet 4.x and Opus 4.1 to Opus 4.5
  - Author: William Hu (Anthropic)

---

## Want More Plugins?

### Seth Hobson's Workflow Marketplace (67+ Plugins)

For access to Seth Hobson's extensive collection of 67 specialized workflow plugins, add his marketplace directly:

```bash
# Add Seth's marketplace
claude marketplace add https://github.com/wshobson/agents.git
```

**Then you can install any of his plugins:**

```bash
# Development & Debugging
/plugin install debugging-toolkit@claude-code-workflows
/plugin install backend-development@claude-code-workflows
/plugin install frontend-mobile-development@claude-code-workflows

# Blockchain & Web3
/plugin install blockchain-web3@claude-code-workflows

# AI & Machine Learning
/plugin install llm-application-dev@claude-code-workflows
/plugin install agent-orchestration@claude-code-workflows
/plugin install machine-learning-ops@claude-code-workflows

# Infrastructure & Operations
/plugin install kubernetes-operations@claude-code-workflows
/plugin install cloud-infrastructure@claude-code-workflows
/plugin install cicd-automation@claude-code-workflows

# Database & Performance
/plugin install database-design@claude-code-workflows
/plugin install database-cloud-optimization@claude-code-workflows
/plugin install application-performance@claude-code-workflows

# Security
/plugin install security-scanning@claude-code-workflows
/plugin install security-compliance@claude-code-workflows
/plugin install backend-api-security@claude-code-workflows

# Marketing & SEO
/plugin install seo-content-creation@claude-code-workflows
/plugin install content-marketing@claude-code-workflows

# Programming Languages
/plugin install python-development@claude-code-workflows
/plugin install javascript-typescript@claude-code-workflows
/plugin install systems-programming@claude-code-workflows

# And 50+ more specialized plugins...
```

See the full list at: [wshobson/agents](https://github.com/wshobson/agents)

---

## Plugin Summary

**Cobi's Curated Marketplace:**
- **Total Plugins:** 14 (all verified to work correctly)
- **Superpowers:** 1
- **Official Anthropic:** 13

**Why This Marketplace?**
- ✅ Every plugin is tested and verified to install correctly
- ✅ No broken plugin installations
- ✅ Curated selection of essential, high-quality tools
- ✅ Clear documentation and usage examples
- ✅ Regular updates to track upstream changes

## Contributing

To suggest a plugin for this curated marketplace:

1. Verify the plugin installs correctly from its source repository
2. Test that all commands, agents, and skills work as expected
3. Submit a pull request with:
   - Updated `marketplace.json` with the plugin entry
   - Updated README.md with plugin description
   - Brief explanation of why it should be included

**Quality Standards:**
- Plugin must be root-level in its repository OR use verified subdirectory structure from Anthropic repos
- Plugin must have clear documentation
- Plugin must be actively maintained
- Plugin source must be from a trusted developer/organization

## License

This marketplace repository is MIT licensed. Individual plugins maintain their own licenses (most are MIT).

## Sources

- [obra/superpowers](https://github.com/obra/superpowers) - Core skills library by Jesse Vincent
- [anthropics/claude-code](https://github.com/anthropics/claude-code) - Official Anthropic plugins
- [wshobson/agents](https://github.com/wshobson/agents) - Production workflow plugins by Seth Hobson (add separately)

## Version History

### v2.0.0 (Current)
- **Breaking Change:** Removed Seth Hobson's 67 plugins from direct marketplace references
- **Reason:** Plugin subdirectory extraction not supported by Claude Code installer
- **Solution:** Users should add Seth's marketplace directly (instructions above)
- Cleaned up marketplace.json to only include verified, working plugins
- Updated README with clear instructions for accessing additional plugins

### v1.0.0
- Initial marketplace release with 81 plugin references
- (Had installation issues - plugins installed as empty directories)
