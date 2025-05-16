# CEITSA Odoo v17 - Internal Development Fork

This repository is an **internal fork** of [Vauxoo/ceitsa](https://github.com/Vauxoo/ceitsa) used exclusively for:

- Internal development and controlled testing.
- Reproducing and troubleshooting issues.
- Validating improvements or fixes before proposing changes upstream.
- Safe experimentation without affecting the production repository.

## ⚠️ Important Notice

> This fork **is not** the official production repository.  
> Do not treat this repository as the source of truth for production deployments.  
> All official releases and updates should come from the upstream repository.

## Usage Scope

- Local or staging environment testing.
- Internal debugging and validation.
- Preparing Pull Requests to the upstream repository.

## Branching Guidelines

- Use descriptive branch names following this pattern:

feature/<short-description>
fix/<short-description>
test/<short-description>

Example: `feature/payment-validation`, `fix/report-layout`, `test/debug-email-sending`

## Contribution Workflow

1. Fork updates from upstream regularly to keep this fork aligned.
2. Work on isolated branches.
3. Test thoroughly in local or staging environments.
4. Open Pull Requests to the upstream repository only after internal validation.

## License

This repository inherits the license of the upstream [Vauxoo/ceitsa](https://github.com/Vauxoo/ceitsa) repository.

---

