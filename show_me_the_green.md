- [X] 01 - Just a Hello World Build: https://circleci.com/gh/JonathanC503/cci-koans/1 

- [X] 02 - YAML Life: https://circleci.com/gh/JonathanC503/cci-koans/7 

- [X] 03 - Database Ace: https://circleci.com/gh/JonathanC503/cci-koans/11 

- [X] 04 - Skipped due to master showing as "incomplete" for Parallelism 05/20

- [X] 05 - Test Summary Mummary: 

- [X] 06 - Branch Filters FTW: https://circleci.com/gh/JonathanC503/cci-koans/29
                         > https://circleci.com/gh/JonathanC503/cci-koans/30

- [X] 07 - Tag & Filter Wilter: https://circleci.com/gh/JonathanC503/cci-koans/37

- [X] 08 - Workflow Fan In & Fan Out Madness: https://circleci.com/gh/JonathanC503/cci-koans/80
    > I am not exactly sure why this works and the previous bajillion builds failed... 
    > For reference, my original formatting followed this: https://circleci.com/docs/2.0/workflows/#fan-outfan-in-workflow-example
    > Moving `requires:` to deploy seems to work, though. 
    > Finally figured this out. I had a floating `-` that was causing the `requires:` to be read as a sequence instead of a `key; value`
    > Updated link above to the correct build with requirements

- [ ] 09 - Sequential Workflow Lowdown: 

- [ ] 10 - Reusable Config "Recycle!": 

[![CircleCI](https://circleci.com/gh/JonathanC503/cci-koans.svg?style=svg)](https://circleci.com/gh/JonathanC503/cci-koans)