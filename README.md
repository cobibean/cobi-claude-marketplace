# Cobi Claude Marketplace

A curated collection of production-ready Claude Code plugins from the community. This marketplace aggregates 81 plugins from three premier sources to enhance your Claude Code experience.

## Installation

To use this marketplace, point your Claude Code installation to this repository:

```bash
cc --marketplace https://github.com/your-org/cobi-claude-marketplace
```

Or install individual plugins:

```bash
/plugin install <plugin-name>
```

## Plugin Collections

### Official Anthropic Plugins (13 plugins)

Official plugins from the Claude Code team at Anthropic.

#### Development Tools

- **agent-sdk-dev** (v1.0.0) - Claude Agent SDK Development Plugin
  - Author: Ashwin Bhat
  - Source: anthropics/claude-code

- **plugin-dev** (v0.1.0) - Comprehensive toolkit for developing Claude Code plugins with 7 specialized skills and guided workflow
  - Author: Daisy Hollman
  - Source: anthropics/claude-code

- **feature-dev** (v1.0.0) - Comprehensive feature development workflow with specialized agents for codebase exploration, architecture design, and quality review
  - Author: Sid Bidasaria
  - Source: anthropics/claude-code

- **frontend-design** (v1.0.0) - Frontend design skill for UI/UX implementation
  - Authors: Prithvi Rajasekaran, Alexander Bricken
  - Source: anthropics/claude-code

#### Code Quality & Review

- **code-review** (v1.0.0) - Automated code review for pull requests using multiple specialized agents with confidence-based scoring
  - Author: Boris Cherny
  - Source: anthropics/claude-code

- **pr-review-toolkit** (v1.0.0) - Comprehensive PR review agents specializing in comments, tests, error handling, type design, code quality, and code simplification
  - Author: Daisy
  - Source: anthropics/claude-code

#### Git Workflow

- **commit-commands** (v1.0.0) - Streamline your git workflow with simple commands for committing, pushing, and creating pull requests
  - Author: Anthropic
  - Source: anthropics/claude-code

#### Output Styles & Learning

- **explanatory-output-style** (v1.0.0) - Adds educational insights about implementation choices and codebase patterns (mimics the deprecated Explanatory output style)
  - Author: Dickson Tsai
  - Source: anthropics/claude-code

- **learning-output-style** (v1.0.0) - Interactive learning mode that requests meaningful code contributions at decision points (mimics the unshipped Learning output style)
  - Author: Boris Cherny
  - Source: anthropics/claude-code

#### Utilities & Automation

- **hookify** (v0.1.0) - Easily create hooks to prevent unwanted behaviors by analyzing conversation patterns
  - Author: Daisy Hollman
  - Source: anthropics/claude-code

- **ralph-wiggum** (v1.0.0) - Continuous self-referential AI loops for interactive iterative development
  - Author: Daisy Hollman
  - Source: anthropics/claude-code

- **security-guidance** (v1.0.0) - Warn about potential security issues when editing files - targets command injection, XSS vulnerabilities, and dangerous coding patterns
  - Author: David Dworken
  - Source: anthropics/claude-code

- **claude-opus-4-5-migration** (v1.0.0) - Migrate your code and prompts from Sonnet 4.x and Opus 4.1 to Opus 4.5
  - Author: William Hu
  - Source: anthropics/claude-code

---

### Superpowers by Jesse Vincent

- **superpowers** (v4.0.2) - Core skills library for Claude Code: TDD, debugging, collaboration patterns, and proven techniques
  - Author: Jesse Vincent
  - Source: obra/superpowers

A foundational skills library emphasizing test-driven development, debugging methodologies, team coordination, and industry best practices.

---

### Claude Code Workflows by Seth Hobson (67 plugins)

Production-ready workflow orchestration with 67 focused plugins, 99 specialized agents, and 107 skills - optimized for granular installation and minimal token usage.

#### Documentation (3 plugins)

- **code-documentation** (v1.2.0) - Doc generation, code explanation, tutorials
- **documentation-generation** (v1.2.1) - OpenAPI specs, Mermaid diagrams, tutorials
- **c4-architecture** (v1.0.0) - C4 documentation with code analysis

#### Development (6 plugins)

- **debugging-toolkit** (v1.2.0) - Interactive debugging, DX optimization
- **backend-development** (v1.2.4) - API design, GraphQL, Temporal, TDD
- **frontend-mobile-development** (v1.2.1) - UI/mobile implementation across platforms
- **multi-platform-apps** (v1.2.1) - Cross-platform coordination
- **developer-essentials** (v1.0.1) - Git, SQL, testing, auth, monorepo

#### Workflows (4 plugins)

- **git-pr-workflows** (v1.2.1) - Git automation, pull requests, onboarding
- **full-stack-orchestration** (v1.2.1) - End-to-end feature orchestration
- **tdd-workflows** (v1.2.1) - Red-green-refactor methodology

#### Testing (2 plugins)

- **unit-testing** (v1.2.0) - Python/JavaScript test automation
- **performance-testing-review** (v1.2.0) - Performance analysis, test coverage

#### Code Quality (2 plugins)

- **code-review-ai** (v1.2.0) - Architectural review, quality analysis
- **comprehensive-review** (v1.2.1) - Multi-perspective code analysis

#### Utilities (3 plugins)

- **code-refactoring** (v1.2.0) - Cleanup, refactoring, technical debt
- **dependency-management** (v1.2.0) - Auditing, version management, security
- **error-debugging** (v1.2.0) - Error analysis, trace debugging
- **team-collaboration** (v1.2.0) - Workflows, standups, issue management

#### AI & Machine Learning (4 plugins)

- **llm-application-dev** (v1.2.2) - Prompt engineering, LLM optimization
- **agent-orchestration** (v1.2.0) - Multi-agent systems, context management
- **context-management** (v1.2.0) - Persistence, restoration, conversations
- **machine-learning-ops** (v1.2.1) - ML pipelines, hyperparameter tuning

#### Data Engineering (3 plugins)

- **data-engineering** (v1.2.2) - ETL pipelines, data warehouse design
- **data-validation-suite** (v1.2.0) - Schema validation, data quality monitoring

#### Operations (5 plugins)

- **incident-response** (v1.2.2) - Production incidents, triage workflows
- **error-diagnostics** (v1.2.0) - Root cause analysis, smart debugging
- **distributed-debugging** (v1.2.0) - Tracing across microservices
- **observability-monitoring** (v1.2.1) - Metrics, logging, tracing, SLOs

#### Infrastructure (5 plugins)

- **deployment-strategies** (v1.2.0) - Deployment patterns, rollback automation
- **deployment-validation** (v1.2.0) - Pre-deployment checks, validation
- **kubernetes-operations** (v1.2.1) - K8s manifests, GitOps, auto-scaling
- **cloud-infrastructure** (v1.2.2) - AWS/Azure/GCP, Terraform, multi-cloud
- **cicd-automation** (v1.2.1) - GitHub Actions, GitLab CI, pipelines

#### Performance (3 plugins)

- **application-performance** (v1.2.1) - Profiling, optimization, observability
- **database-cloud-optimization** (v1.2.0) - Query optimization, cost reduction

#### Modernization (2 plugins)

- **framework-migration** (v1.2.2) - Framework updates, architectural transformation
- **codebase-cleanup** (v1.2.0) - Technical debt reduction, refactoring

#### Database (2 plugins)

- **database-design** (v1.2.0) - Architecture, schema design, SQL optimization
- **database-migrations** (v1.2.0) - Migration automation, observability

#### Security (5 plugins)

- **security-scanning** (v1.2.3) - SAST, vulnerability scanning, OWASP
- **security-compliance** (v1.2.0) - SOC2, HIPAA, GDPR validation
- **backend-api-security** (v1.2.0) - API hardening, auth, authorization
- **frontend-mobile-security** (v1.2.0) - XSS prevention, CSRF protection, CSP

#### API Development (2 plugins)

- **api-scaffolding** (v1.2.1) - REST/GraphQL scaffolding, generation
- **api-testing-observability** (v1.2.0) - API testing, mocking, OpenAPI docs

#### Marketing & SEO (4 plugins)

- **seo-content-creation** (v1.2.0) - Content writing, planning, auditing
- **seo-technical-optimization** (v1.2.0) - Meta tags, keywords, featured snippets
- **seo-analysis-monitoring** (v1.2.0) - Content freshness, cannibalization detection
- **content-marketing** (v1.2.0) - Strategy, research, synthesis

#### Business (3 plugins)

- **business-analytics** (v1.2.1) - Metrics analysis, KPI tracking, reporting
- **hr-legal-compliance** (v1.2.1) - HR policies, legal templates, contracts
- **customer-sales-automation** (v1.2.0) - Support workflows, sales pipelines, CRM

#### Specialized Domains (5 plugins)

- **blockchain-web3** (v1.2.1) - Smart contracts, DeFi, NFT platforms
- **quantitative-trading** (v1.2.1) - Algorithmic trading, risk management
- **payment-processing** (v1.2.1) - Stripe/PayPal integration, billing
- **game-development** (v1.2.1) - Unity, C#, Minecraft plugin development
- **accessibility-compliance** (v1.2.1) - WCAG auditing, screen reader testing

#### Programming Languages (9 plugins)

- **python-development** (v1.2.1) - Django, FastAPI, async patterns
- **javascript-typescript** (v1.2.1) - ES6+, Node.js, React
- **systems-programming** (v1.2.1) - Rust, Go, C, C++
- **jvm-languages** (v1.2.0) - Java, Scala, C#
- **web-scripting** (v1.2.0) - PHP, Ruby, Rails
- **functional-programming** (v1.2.0) - Elixir, OTP, Phoenix
- **julia-development** (v1.0.0) - Julia 1.10+, scientific computing
- **arm-cortex-microcontrollers** (v1.2.0) - Firmware, Teensy, STM32, nRF52
- **shell-scripting** (v1.2.1) - Bash, POSIX, defensive programming

## Total Plugin Count

- **Official Anthropic Plugins**: 13
- **Superpowers**: 1
- **Claude Code Workflows**: 67
- **Total**: 81 plugins

## Contributing

To add your plugin to this marketplace, please submit a pull request with:

1. Updated `marketplace.json` with your plugin entry
2. Updated README.md with plugin description
3. Proper GitHub source reference in the correct format

## License

This marketplace repository is MIT licensed. Individual plugins maintain their own licenses (most are MIT).

## Sources

- [anthropics/claude-code](https://github.com/anthropics/claude-code) - Official Anthropic plugins
- [obra/superpowers](https://github.com/obra/superpowers) - Core skills library by Jesse Vincent
- [wshobson/agents](https://github.com/wshobson/agents) - Production workflow plugins by Seth Hobson
