# Rust Code Review Guidelines

## Objective of the Guidelines

This guide aims to:

1. Provide a systematic and actionable checklist for Rust code reviews.
2. Supplement automated checks by tools such as compilers, rustfmt, and clippy.
3. Help reviewers identify key issues including:
   - Memory safety issues not detectable by the compiler.
   - Concurrency safety hazards.
   - Business logic defects.
   - Performance bottlenecks.
   - Maintainability issues.
   - Information security risks.

This guide is applicable to:

- Code reviewers: Provides comprehensive inspection dimensions and specific verification methods.
- Code submitters: Understands review concerns and performs preliminary self-checks on code quality.
- Project leaders: A reference for establishing team code review standards.

## Relationship with Other Guidelines

The difference between this guide and the "Rust Coding Guidelines":

- Aimed at code reviewers rather than developers.
- Focuses on issues that are difficult for compilers and static analysis tools to detect.
- Provides specific inspection methods and examples.
