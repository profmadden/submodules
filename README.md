# submodules
Test project, to experiment with submodules.....  

Using instructions from [GitHub](https://github.blog/2016-02-01-working-with-submodules/)

For a bunch of projects, there are some common libraries, and chunks of stuff that need to get linked in.

```
git submodule add https://url-to-project project
```

Submodules don't automatically update on a git pull.  To get that to happen, run this:

```
git submodule update
```
