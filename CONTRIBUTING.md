# Contributing to CAMPUSCARE

CAMPUSCARE is designed as an online coding-event starter project.

## Getting Started

1. Fork or clone the repository.
2. Create a virtual environment.
3. Install dependencies from `requirements.txt`.
4. Run migrations.
5. Start the Django development server.
6. Read the open Issues before choosing a task.

## Development Guidelines

Keep changes focused on the selected Issue.

Use clear Python and Django code that another student can understand.

Do not commit:
- virtual environments
- passwords or secret keys
- personal student information
- generated cache files

## Before Submitting

Run:

```bash
python manage.py check
python manage.py test
```

Then verify the complaint submission flow manually.

## Competition Note

The existing prototype is intentionally incomplete. Participants should use the Issues as starting points and are encouraged to improve the implementation without breaking the existing complaint submission flow.
