
## Notice boxes
You can make `info`, `warning` and `alert` boxes like this. Examples of what they look like can be found here: https://squidfunk.github.io/mkdocs-material/getting-started/


**Info box**
```
!!! info "Call for Contributions: Add languages/translations to Material"

    Help translate Material into more languages - it's just **one click** and
    takes approximately **2 minutes**: [click here](http://bit.ly/2EbzFc8)
```

<br>

**Warning**

```

!!! warning "Installation on macOS"

    When you're running the pre-installed version of Python on macOS, `pip`
    tries to install packages in a folder for which your user might not have
    the adequate permissions. There are two possible solutions for this:

    1. **Installing in user space** (recommended): Provide the `--user` flag
      to the install command and `pip` will install the package in a user-site
      location. This is the recommended way.

    2. **Switching to a homebrewed Python**: Upgrade your Python installation
      to a self-contained solution by installing Python with Homebrew. This
      should eliminate a lot of problems you may be having with `pip`.



```

<br>

**Failure**
```
!!! failure "Error: unrecognized theme 'material'"

    If you run into this error, the most common reason is that you installed
    MkDocs through some package manager (e.g. Homebrew or `apt-get`) and the
    Material theme through `pip`, so both packages end up in different
    locations. MkDocs only checks its install location for themes.
```