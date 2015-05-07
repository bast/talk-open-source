
# Open-source development: benefits and misconceptions

## Radovan Bast

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Code examples: [OSI](http://opensource.org)-approved [MIT license](http://opensource.org/licenses/mit-license.html).

---

template: inverse

# Benefits

---

layout: false

## Minimize distribution effort

- Distributing the code becomes trivial and effortless.
- Since all issues are public, there is no pressure to fix all issues prior to a release.

---

## Immediate availability of patches

- Patches become immediately available.
- Everybody can submit patches: users can submit issues and fix issues - less
  work for the core development team.

---

## Scientific reproducibility

- Peer-reviewed software.
- Full reproducibility.
- http://sciencecodemanifesto.org

---

## Allow external contributions

- Fork/merge-request mechanism makes it possible for everybody to submit patches.
- These can be reviewed, discussed, and accepted by the core development team.

---

## Probably more users

- Users tend to favor free open-source software over restricted software.
- Users who otherwise would have to choose between two (competing) proprietary
  systems, will naturally choose the free open-source alternative.
- Computing centers like open-source software.

---

## Allow derived products

- Open better than closed.
- Standard licenses better than custom (compatibility of licenses).
- Derived products increase visibility.
- Catalyze derived development.
- Derived products support the product they depend on.

---

## Simplify hosting and deployment of documentation

- Modern documentation using Sphinx, hosted on GitHub/GitLab close to the code,
  versionned and deployed to ReadTheDocs is the state of the art today.
- With an open-source code this solution becomes trivial and free.
- Documentation is refreshed automatically using post-receive hooks.
- Everybody can submit patches to the documentation, even users.

---

## Continuous integration and code coverage analysis

- https://travis-ci.org
- https://coveralls.io

---

## More funding opportunities

- We are funded by the public so we should give back to the public.
- Some funding opportunities are difficult or impossible to get if the code is
  not open source.

---

template: inverse

# Common misconceptions

---

## People will steal my work!

- No. If your work is on GitHub/GitLab, it is equivalent to having presented it
  in a workshop.
- Not only would it be grave scientific misconduct if anybody would try to
  steal your work, it would be very easy to prove (the committer and commit
  date are always included in the commit).

---

## I don't want to show what I'm working on yet!

- You can easily choose not to push the latest developments to the open repo quite yet.
- This is one of the great advantages of distributed version control.

---

## People will use my still unpublished feature!

- Probably not.
- Your program is nearly impenetrable to non-experts, and it's quite hard to
  use unofficial features.
- One can also ask people not to use features not on the master branch without
  asking the authors first.

---

## Somebody will make money with my work!

- This can be controlled by the license.

---

## There will be many versions of my code, some of them bad/wrong - this will harm my reputation!

- You can control redistribution by the license.
- If redistribution of derivative work is allowed by the license, this does not
  imply that the derivative is endorsed by the authors of the original product.

---

## I will lose control over my code - I want to decide what functionality goes in!

- You keep full control about what is incorporated through the
  fork/merge-request mechanism.
- Experience shows that people nearly always look to the official versions of
  codes.
- Even if somebody creates a version you do not agree with, it will have
  minimal impact (unless of course your concerns are false, but then you can
  just include the changes later).
