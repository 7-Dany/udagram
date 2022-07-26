# CircleCi

To create a pipeline we first create a folder called .circleci in the root directory

Then create a new file called config.yml

In config.yml we specify many thing

1. CircleCi Version
    - version: 2.1

2. Orbs, here we specify all recipes that needed to run our app
    - node:circleci/node@5.0.2

3. jobs, here we specify all commands that need to run with steps
    - build, we specify 2 things
        - docker
        - steps, we specify 2 things
            1. setups needed for our job like eb/setup
            2. commands that need to run after installing the setups like npm run build

4. workflow, here we specify the order that we need our job to run into

__Here all jops that listed from pipeline will run in order build first then deploy__
![CircleCi Jobs](images/circleci%20jobs.png)

__Here after the build jop finished__
![CircleCi Build](images/circleci%20build.png)

__Here after the deploy jop finished__
![CirceCi Deploy](images/circleci%20deploy.png)

__Here the results of after deployment process had run successfully__
![CircleCi Run](images/CircleCi%20out.png)
