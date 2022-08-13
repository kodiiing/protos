# Protocol Buffer Contracts

This repository provides proto files as a contract for each services in Kodiiing.
Include this repository as a git submodule for each of the repository that are using
one or more proto files from this repository.

## Capabilities

This readme contains the capability of each services in detail.

### Auth

File: auth.proto

User can login via OAuth2 providers (Github and Gitlab)

### User

File: user.proto

- Onboarding. To find out what interest the user and what are their targets.

### Task

File: task.proto

- User can see available tasks
- User can start and submit a task
- User can take post-test assessment about their own performance
- User can give feedback about the task
- User can get their next task recommendation
- User can see their finished tasks and answers
- User can see their task's reviews
- User can comments to their task's reviews

### Code review

File: codereview.proto

- User can apply as a code reviewer
- Reviewer can see a list of tasks that can be reviewed
- Reviewer can give a fresh review to a finished task
- Reviewer can give follow up comments/feedbacks based on user's comment

### Hack

File: hack.proto

- User (or reviewer) can start a hack post
- User (or reviewer) can upvote a hack post
- User (or reviewer) can comment on a hack post