### A written Convention
    Maintain a written brancing workflow will help as follow for your team
    1. Git allows out to create branches - but it doesn't tell you how to use it
    2. Need written best practices how work is ideally structured in your team- to avoid mistakes and collissions
    3. It highly depends on our team / team size on our project, and how you handle releases.
    4. It helps to onboard new team members (This is how we work here)


### Long Running branches
    Branches that are exist the complete lifetime of the project, often they mirror "stages" in your dev lifecycle. no direct commits for this branch.
### Short-lived branches
    for new features, bu fixes, refactoring, experiments
    will be deleted after integration (merge/rebase) 
    typically depend on long running branch

## Exapmle brancing stratagies
    1. Github flow
        very simple, very lean: only one long running branch ("main") + feature branches.
    2. GitFlow
        more structure, more rules.
        may be multiple long running branches: "main" + "develop"
        short-lived: feature, releases, hotfix



                                              release   
                      feature---feature      /       \
                     /                  \   /         \                  
              develop----------------------------------\---------------------------develop---------------
            /                                           \                                  
        main------------------------------------------------------------------------------main-----------