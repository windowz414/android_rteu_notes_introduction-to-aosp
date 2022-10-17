---
template: main.html
---

## Log Creation

run following the command via git-bash and copy output to following content

```bash
git log 
```

## Course Notes Changelog


```bash
commit d3943cd634238d61b79e2dad0686634e67a5eae4
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Tue Oct 18 00:24:50 2022 +0300

    docs: Nuke homeworks folder
    
    * No homeworks for this lecture. :D
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 3e59e11a4c7625dee90885a6b25bd26109a5fcf3
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Tue Oct 18 00:23:46 2022 +0300

    docs/license: Add notice for GPL 2.0
    
    * Sublicensed under that by Beru on behalf of me for additional
      code and design-wise.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit deb9791b215ca41c6c86e43ba1e5cb3efafa735b
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Tue Oct 18 00:22:04 2022 +0300

    docs/week-^: Remove color property for first slide
    
    * Looks gore, so let's keep it at default black.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit f75f8916c01b4bd18376ded0cfe5663e6c3d0486
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 15:23:11 2022 +0300

    docs: Purge out redundant files
    
    ```
    INFO     -  The following pages exist in the docs directory, but are not included in the "nav" configuration:
                  - index.tr.md
                  - license.tr.md
                  - changelog\index.tr.md
                  - resume\index.en.md
                  - resume\index.tr.md
                  - syllabus\syllabus.en.md
                  - syllabus\syllabus.tr.md
    ```
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 41f09cd4f645b94973b06e6c58537250c429a56a
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 15:17:10 2022 +0300

    Remove Turkish language and some pages that might not be needed
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 2ec66092e241ce158c755a1e3076207bc89ea0b7
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 15:05:09 2022 +0300

    docs: week-2: Initial changes
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit f9c81ed974eec4d9acd382b493f2137271ea7be7
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 12:37:14 2022 +0300

    docs: week-1: Remove RTEU branding
    
    * That branding also includes the class name which is irrelevant
      with my course notes.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 789c1c18a02bde37141d0ebc5dadd614eb158e1d
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 12:04:26 2022 +0300

    [REVERTME] docs: week-2: Replicate modifications for Week 1 material
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 2124ea28ba1ffddc0745f4afe5c4b467e0eb6fc6
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 12:02:54 2022 +0300

    docs: week-1: Build English variant
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit fa6c9c9a122bd4482c374e6b58b01e33313d8b98
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 12:01:13 2022 +0300

    [REVERTME] docs: week-1: Remove Turkish variants
    
    * Previous commit removed repeated build targets. That change would
      allow only first detected file, which is original, English
      variant, to be built. Remove Turkish variants to avoid mismatches
      between content and showing dummy one.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit ce42aeb5565df71c620c5b8f41022c9c1bc7e428
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Sun Oct 16 11:58:35 2022 +0300

    [REVERTME] docs: week-1: build: Remove repeated build
    
    * I intend to build just English version for now.
    
    TODO: Translate this to Turkish and build both together in a wider
          time.
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 1b62d433ee6f0816fffbe648fa075c5ed872cce8
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Fri Oct 14 19:37:04 2022 +0300

    docs: week-1: Make my own modification and notes
    
    * Also regenerate the assets.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 9b0b7a6aa0ffdf99a696627b34e7a30c2980fae5
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Fri Oct 14 08:39:44 2022 +0300

    mkdocs: Properly localize Turkish translation for "Changelog"
    
    * "Geçmiş" in Turkish means "History". However, "changelog" is rather
      meant to say "version history", which translates to Turkish as
      "Sürüm Geçmişi" or something similar. Do the change accordingly.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 86b923afab173b7ea9048fe3c2126b0bde0d1584
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Thu Oct 13 15:31:43 2022 +0300

    docs/images: Replace images with my own designs
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 2794d1d4c7bc1f221f6f64d68fae29798dc5c916
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Thu Oct 13 15:31:15 2022 +0300

    Fix a little typo on mkdocs
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit ca47880146219d96979fa5408f3f43f91e04760d
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Thu Oct 13 13:21:30 2022 +0300

    docs: Remove redundant resources
    
    * We removed definition of these in previous commit. We remove the
      actual resources to save some space now.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 1bccafe38f9a9fb2af2c84359fd54cf7239b56e3
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Thu Oct 13 13:01:52 2022 +0300

    Update configuration to my own
    
    * Let's begin with introduction to AOSP now, shall we?
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit fc7629e9de10c1d0d3f8b91892c3966dc34e2667
Author: Uğur CORUH <ugur.coruh.tr@gmail.com>
Date:   Thu Oct 13 06:57:32 2022 +0300

    Update README.md

commit e816b9bdd7174b376e70e5ad0deb64625aaa2d64
Merge: a6918da 581c74b
Author: Uğur CORUH <ugur.coruh.tr@gmail.com>
Date:   Thu Oct 13 06:53:09 2022 +0300

    Merge pull request #3 from windowz414/main
    
    Reduce external dependencies and run new cmd instances for external package managers

commit 581c74b360ffa67146e11f0d87b7eeefb79c8ef1
Merge: 3ecdb54 a6918da
Author: Uğur CORUH <ugur.coruh.tr@gmail.com>
Date:   Thu Oct 13 06:52:59 2022 +0300

    Merge branch 'main' into main

commit a6918da222277db2c0d3d6f4e127d65b8f6b6deb
Merge: c5871e7 53b2f9c
Author: Uğur CORUH <ugur.coruh.tr@gmail.com>
Date:   Thu Oct 13 06:47:17 2022 +0300

    Merge pull request #1 from ahmetkayatr/main
    
    Fix Scoop installation

commit 3ecdb5447189e0d32f24c51becdfc320a676763b
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Wed Oct 12 20:31:25 2022 +0300

    Take advantage of `start` to spawn new CMD windows to run package mgrs (#2)
    
    * Since installing package managers require shell restart because
      they add themselves to PATH, we need to restart the shell or spawn
      new CMD window for each package installation process (this also
      gives us availability to perform install tasks in parallel :D).
      Let's take advantage of `start` in combo with `cmd` with `/C`
      switch to do this for us.
    
    * Commit 2 of 2, as an alternative to make the shell restart.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 12d5c560ef9de2ee35c694a82e1f5cb7667b5ac8
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Wed Oct 12 19:35:23 2022 +0300

    Align script with a better codestyle and install Python from MS Store (#2)
    
    * This is because of a few reasons.
    
    * The user already installs latest updates to Windows and practically
      already has Windows 10 21H2+ installed on their machine (even if
      it's legacy!) so why bother trying to use deprecated old
      functions and software?
    
    * Along with latest updates, the user already installs latest UWP
      apps and so get the latest command line tools provided by UWP apps
      (such as winget) so we should already be able to use them.
    
    * Python on MS Store, which is what winget installs Python from,
      already downloads and installs latest version of Python from their
      official website so why install it from an external source that's
      most probably not even using Python's website as source?
    
    * Windows 10 1803 onwards already ship curl CMDline utility inbuilt
      so why overwrite it?
    
    * Why was the last pip-install separated from others? Align that and
      establish consistency.
    
    * Why do we need to change into the directory script was run from when
      we do literally nothing that changes its contents? Remove it.
    
    * Commit 1 of 2, reducing dependencies on other package managers.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit e0c6f285541812628a2401c5638ba14a96808c06
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Wed Oct 12 18:18:01 2022 +0300

    Fix Scoop installation
    
    * Done by aligning installation command with newer one. Also fixed
      syntaxing for PowerShell.
    
    TODO: Also restart terminal after installing package managers.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit 53b2f9c1717cbfd02946d386e6d1f121b6bc17a3
Author: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>
Date:   Wed Oct 12 18:18:01 2022 +0300

    Fix Scoop installation
    
    * Done by aligning installation command with newer one. Also fixed
      syntaxing for PowerShell.
    
    TODO: Also restart terminal after installing package managers.
    
    Signed-off-by: Bedirhan KURT <bedirhan.kurt.trjp@gmail.com>

commit c5871e7af099362bbe0db70e57a84c2fcfa3139e
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Wed Mar 9 23:30:31 2022 +0300

    yml fixed

commit 080a0d82ebf352af234903625853d2836431cddf
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Wed Mar 9 23:28:19 2022 +0300

    video plugin added

commit c68c4343e8627f5e40da97157f58b1a8ad6232d3
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Mon Mar 7 02:42:27 2022 +0300

    README.md updated for publish operation

commit 4724b5d73ddaadee2e1c388c8c0bb625eac3d719
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Mon Mar 7 02:33:03 2022 +0300

    README.md updated for commit and push

commit ecf4a3ebe9ac62632285a6ae64fe7a2afac46a5c
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Mon Mar 7 02:32:01 2022 +0300

    README.md updated

commit a9431cbd6d80d4c69b1f446c9cea9f1fe6c18eaf
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Mon Mar 7 00:32:49 2022 +0300

    Turkish and English Support Added for Overall Content

commit da9526a92f88e45aac7284971f6a3a5e401e4fa4
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Sun Mar 6 17:25:08 2022 +0300

    yaml file github repo names are updated

commit 9ae43c746fcaaec5072fc818396d8a04a2532951
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Sun Mar 6 17:22:33 2022 +0300

    jar files added for plantuml.jar

commit 0f7237169ab5be4cf7b1f55e1798272af421cd7f
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Sun Mar 6 17:20:56 2022 +0300

    multi language try

commit 0e3474fbc089ea19d84879fc364c80e3d1bc0fc8
Author: Ugur Coruh <ugur.coruh.tr@gmail.com>
Date:   Sun Mar 6 16:50:51 2022 +0300

    initial commit
```