# faithfulgit
Branch dependent files in git repos

This set of scripts enables files that won't change on merges with other branches.

Assume two branches master and second
merging master on second won't change the faithful file
commiting will work as before, version control is still available.
merging master of repo one on master of repo two will merge the faithful file

# dependecies
fish shell

# installation
Put installfaithfulgit.fish in your repo and execute it. This will install a custom merge driver and a post-commit hook. A hidden directory .faithfulgit will be created and filled.