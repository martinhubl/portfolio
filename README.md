# Martin Hübl — Developer Portfolio

I build web applications and automation with an emphasis on clear backend behavior, practical testing, and secure delivery. The projects below are selected from verified work and described without exposing confidential implementation or internal data.

## Skills

- PHP, SQL/PDO, MVC-style web applications, and JSON APIs
- HTML, CSS, and JavaScript integration
- Python and Bash automation
- Git and GitHub workflows
- Automated CLI, API contract, regression, and security testing
- Authentication, authorization, CSRF protection, input validation, and fail-closed design

## Selected Projects

### KRIMIGAME

A turn-based multiplayer deduction web game built around a custom PHP MVC backend. The application includes room and player flows, server-side game state, movement validation, turn handling, clues, win conditions, JSON endpoints, and administration features.

- Technologies: PHP, SQL/PDO, HTML, CSS, JavaScript, JSON APIs
- Engineering work: domain services, routing policies, authentication and session controls, CSRF protection, API validation, and database-backed game logic
- Verification: a recorded release audit reports 61 of 61 CLI end-to-end and API contract checks passing, including authorization, routing, game-engine, and HTTP error-path coverage
- Public overview: https://github.com/martinhubl/krimigame

### Safe Portfolio Publication Pipeline

A Python orchestration layer that turns verified project evidence into deterministic public previews while keeping publication disabled by default. It applies project and field allowlists, provenance checks, secret and privacy gates, explicit approval, destination validation, idempotency, post-push verification, and rollback semantics.

- Technologies: Python, Bash, JSON, Git, GitHub CLI/API integration
- Engineering work: deny-by-default policy, deterministic hashing and diffs, isolated adapter testing, bounded approvals, verification receipts, and recoverable publication planning
- Verification: 61 focused cases passed twice, 16 owner regression gates passed, and the final health and certification gates passed
- Safety boundary: no public destination is enabled automatically and no non-public implementation is included in generated content

## Engineering Practices

- Deterministic previews and reviewable diffs before side effects
- Automated focused, regression, security, and release checks
- Hash-bound approvals and evidence-backed results
- Fail-closed handling of secrets, private metadata, and incomplete provenance
- Idempotent operations, rollback planning, and post-operation verification
- Git-based change history with explicit scope control

## Contact / Availability

GitHub: [@martinhubl](https://github.com/martinhubl)
