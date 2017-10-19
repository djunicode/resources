# resources
List of resources to get started with software development.

## Android

### Courses
- [Udacity: Developing Android Apps](https://in.udacity.com/course/new-android-fundamentals--ud851)

### Documentation

- [Android Developers Website](https://developer.android.com/develop/index.html)  
You will find pretty much **everything** that is present in standard Android here

- [Android Developers Reference](https://developer.android.com/reference/packages.html)  
Documentation on all classes is given here

- **Specific Guides**
    - [Intents](https://developer.android.com/guide/components/intents-filters.html)
    - [Activities](https://developer.android.com/guide/components/activities/index.html)  
        Take special note of the activity lifecycle, and the back-stack. The back-stack is a crucial, but oft-neglected part of effective android navigation.
    - [Fragments](https://developer.android.com/guide/components/fragments.html)  
        Read this once even if you know how to use Fragments. This is the most important concept for a front-end developer
    - [Services](https://developer.android.com/guide/components/services.html)  
        For any service that runs in the background, even when the app is closed
    - [Loaders](https://developer.android.com/guide/components/loaders.html)  
        For loading data into the UI from any source. Prevents the UI from being unresponsive
    - [ContentProviders](https://developer.android.com/guide/topics/providers/content-providers.html)  
        For creating a standardized and effective interface to access your app's data from within and outside the app. This is very important when doing any kind of local storage
    - **RecyclerView**: Everybody go through this, no matter what part of the Android stack you focus on
        - [Guide on Creating Lists and Cards](https://developer.android.com/training/material/lists-cards.html)
        - [RecyclerView reference](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html)
        - [RecyclerView layout](https://developer.android.com/guide/topics/ui/layout/recyclerview.html)
  
  
  
## Git  
Every modern development team requires a version control system, and git is probably the best. Linus Torvalds made this, in a mere two weeks to manage the (famously complex) Linux kernel project.
  
Note: This list has been ~~shamelessly plagiarized~~ sourced from University of Southern California's page [here](http://bits.usc.edu/cs104-sp17/git-resources.html)

### Books  
- [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/index.html) is brief and effective. A good read if you are in a hurry
- [Pro Git](https://git-scm.com/book/en/v2): A detailed, but thorough book on git. A must read, if you have time

### Tutorials  
- [Try Git](https://try.github.io/levels/1/challenges/1)  
An absolute beginner's guide to git. It gives a good start, but covers only the most basic stuff.
- [Git Immersion](http://gitimmersion.com/)  
A thorough tutorial on git.

### Workflow and Best Practices
- [A git workflow for small teams](http://toroid.org/git-central-repo-howto)
- [Oliver Steele's Blog Post on commit policies](http://blog.osteele.com/2008/05/commit-policies/)
- [A successful git branching model](http://nvie.com/posts/a-successful-git-branching-model/)
- [Git Best Practises](http://sethrobertson.github.io/GitBestPractices/)

