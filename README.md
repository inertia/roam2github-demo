# roam2github-demo

For those who are having issues with [MatthieuBizien/roam-to-git](https://github.com/MatthieuBizien/roam-to-git/) in GitHub Actions, try my new solution:

1. Add secrets for the following values:

    - R2G_EMAIL
    - R2G_PASSWORD
    - R2G_GRAPH
    
2. Update your main.yml with the code here: https://github.com/everruler12/roam2github-demo/blob/main/.github/workflows/main.yml

    - _If you created your repo before October 1st, 2020, you may need to change the branch name from 'main' to 'master'_

Note that this will only backup the JSON file (for now) and not export markdown.

See more info at https://github.com/everruler12/roam2github
