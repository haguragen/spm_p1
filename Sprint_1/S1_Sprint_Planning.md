# Sprint1 Planning for "Urban Tree Explorer"

## Sprint Goal
Develop a visual map based on the plant dataset and have the "filter" and "mark location" function.

## Selected User Story
### User Story 1: View Tree Map

As a PhD student, I want to view tree distribution on an interactive map so that I can find suitable outdoor spots for gatherings.

### Acceptance Criteria:
- Users could see an interactive map.
- The map could display tree distribution.
- The map should support zoom and pan.

### Estimation using Fibonacci Sequence
| Factor              | Consideration |
|---------------------|--------------|
| Complexity         | Severe - Need to build an interactive interface. |
| Uncertainty        | Low - There are tools to build an interactive map. |
| Dependencies      | Severe - Whole project would been built on Tableau(or tools like this). |
| Risk              | Low - Low security risk and no other risks. |
| Estimated Story Points | **13** |

### Sprint Backlog Tasks
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Design the style of the map | Anqi ZHOU | 6 |
| Use dataset to build the visualization | Xingchen Du | 6 |
| Complete zoom and pan function | Junwu Shen | 2 |
| Test the map | Siyu GU | 2 |

### User Story 2: 2 Factor authentication

As a new user, I want to register and log in securely, so that I need a more safe way to login.

### Acceptance Criteria:
- Users need to use a TOTP code to login.
- Users could set up TOTP code when they sing up.

### Estimation using Fibonacci Sequence
| Factor              | Consideration |
|---------------------|--------------|
| Complexity         | Moderate - Need to have access to TOTP applications. |
| Uncertainty        | Low - There are so many ways to deploy 2 Factory Authentication. |
| Dependencies      | Moderate - Depends on TOTP application. |
| Risk              | High - Login security. |
| Estimated Story Points | **8** |

### Sprint Backlog Tasks
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Design 2 Factor Authentication schema(probably TOTP) | Anqi ZHOU | 6 |
| Implement TOTP login pattern(or other) | Xingchen Du | 6 |
| Link front-end interface of login and interface of authentication | Junwu Shen | 2 |
| Write documents to teach user how to user our 2 Factor Authentication pattern | Zehong Tan | 2 |
| Write unit tests for authentication | Siyu GU | 2 |


