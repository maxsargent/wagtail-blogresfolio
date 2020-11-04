# wagtail-blogresfolio
A website made using Pythons Django framework and wagtail CMS.

A blog, resume and portfolio site - blogresfolio.

Will be following https://www.conventionalcommits.org/en/v1.0.0/#specification for commit message formatting.

Will try to limit the number of types to:

- feat - new additions to the source
- fix - changes to existing source
- docs - updating the readme or any other docs
- misc - miscellaneous type for everything else

As for scopes we will add them as we go, I think breaking out the Django apps into feats will work well:

- blog - any work on the blog
- res - any work on the resume
- folio - any work on the portfolio
- dependencies - adding to requirements.txt 
- config - modifying configuration files suck as dockerfiles or gitignores etc 

Another consideration is branching. To keep things simple we are going to follow this model https://nvie.com/posts/a-successful-git-branching-model/.
This means that after this commit I will create a separate development branch. When we get something half decent I will branch to a release branch.
Once all the kinks are worked out of that branch (remember bug fixes only no feature work) I will deliver it back to this main/master branch.

Here are some resources for wagtail that we will be using on this project:

- https://learnwagtail.com/
- https://docs.wagtail.io/en/stable/
- https://docs.wagtail.io/en/v2.0/editor_manual/
