This is our README.md

How to work with git in your R Project:

1. Create a Github account
2. Get a token made from https://github.com/settings/tokens/ (select repo, user, and workflow). Set the expiry for a few months and copy the generated token somewhere
2. In Rstudio in the console type in the following code and press enter after each one: 
install.packages("usethis")
library(usethis)
use_git_config(user.name = "[USERNAME]", user.email = "[EMAIL")
gitcreds::gitcreds_set()
3. The console will ask for your token credential from step 2, paste it in now
4. Create a new RStudio Project
5. Choose "Other Versions" instead of "New Directory"
6. In the git directory paste in: "https://github.com/Mwolbergum/TO414-Group-Project"
7. Name the project whatever you want
8. To pull (download) updated data from the repository go to the "Git" tab in the top right panel and click the blue down arrow
9. To push (upload) your work