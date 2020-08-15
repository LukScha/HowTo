# Forking Tutorial

### Fork use cases
Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

##### Propose changes to someone else's project
For example, you can use forks to propose changes related to fixing a bug. Rather than logging an issue for a bug you've found, you can:

- Fork the repository.
- Make the fix.
- Submit a pull request to the project owner.

##### Use someone else's project as a starting point for your own idea.
Open source software is based on the idea that by sharing code, we can make better, more reliable software.
When creating your public repository from a fork of someone's project, make sure to include a license file that determines how you want your project to be shared with others.

### How to fork
- On GitHub, navigate to the desired repository.
- In the top-right corner of the page, click Fork.
- Create a local clone of your fork.

### Keep your fork synced
When you fork a project in order to propose changes to the original repository, you can configure Git to pull changes from the original, or upstream, repository into the local clone of your fork.

- Type ```git remote -v``` to see the current configured remote repository for your fork.
```
$ git remote -v
> origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
> origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
```
- Type ```git remote add upstream [https link from parent repo]``` to sync them
- Type ```git remote -v``` again, to verify your changes
```
$ git remote -v
> origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
> origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
> upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (fetch)
> upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (push)
```



For further information see [Fork a repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)
