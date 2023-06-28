# FuturU

This will contain some standards that should be applied in the organisation

## Branch name
The branch name should contain ticket number and brief description. An example:
lx-1_replace_mock_with_list_courses_api

## Commit message
The commit message can contain these items below:
- Ticket number
- Type of change (config/fix/feature/refactor)
- Brief description of change
- Areas for regression testing (if applicable)
- Technical info (optional)

First line should contain the first three item, at minimum. Second line can contain the remaining two items, if relevant. An example:

[LX-2] [Feature] Replaced mocked list of courses with the API Request

Added API Request to list courses defined on ticket LX-1, authenticating via JWT signed by Cognito
Regression test Courses list page and home page

## Branch protection
- Add protection to new repositories to main branch, requiring a Pull Request with at least one approval

## Repository permissions
- Write permission to developer team
- Admin permission to sre-admins team
