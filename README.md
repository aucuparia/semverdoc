## Document Semantic Versioning

In often work with documents that require proper versioning. In the past I have often used or recommended using the semantic versioning scheme knowing that the scheme has actually been developed for software development. While it is possible to apply the semantic versioning to documents, some of its characteristics need to be adopted. 

While I often simply ignored the need for this adoption in the past, I finally found the time to rework the semver specification for use with documents. 

Summary
-------

Given a version number MAJOR.MINOR.PATCH, increment the:

1. MAJOR version when your document has undergone significant changes,
1. MINOR version when new information has been added to the document or information has been removed from the document, and
1. PATCH version when you made minor changes (e.g. fixing typos).

Additional labels for pre-release and build metadata are available as extensions
to the MAJOR.MINOR.PATCH format.

For more details you can find the specification [here](https://guides.github.com/features/mastering-markdown/).

### Contributions or comments


Credit
-----
This work is heavily based on the Semantic Versioning specification as authored by [Tom
Preston-Werner](http://tom.preston-werner.com), inventor of Gravatar and
cofounder of GitHub.