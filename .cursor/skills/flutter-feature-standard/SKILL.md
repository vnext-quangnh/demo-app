# Skill: flutter-feature-standard

## Purpose

Implement new Flutter feature following internal architecture.

## Constraints

- Use standard Riverpod (no codegen)
- Do NOT use FutureProvider for complex features
- Use StateNotifier
- State must be immutable
- Follow feature-based structure:
  - presentation
  - application
  - domain
  - infrastructure
- Wrap all errors in AppFailure
- No API calls inside UI layer
- No StatefulWidget
- Pagination must use state machine pattern
- Dependency injection via constructor

## Output Format

1. Folder structure
2. Domain entities
3. UseCase
4. Repository interface
5. State class
6. Notifier
7. UI example
