## git workflow tests

Testing various pitfalls with a new git branching strategy

the normal flow:

0. branch a release off of master
1. branch feature off master
2. feature dev
3. code review
4. rebase+merge onto staging
5. stuff on staging passes UAT
6. rebase+merge feature onto release
7. rebase+merge release onto master
8. rebase staging onto master
9. repeat

## scenarios

### happy path

### release a feature while one is on staging, no conflicts

### release a feature while one is on staging, conflicts
