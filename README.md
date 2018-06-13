## Semantic Versioning for Documents and meaningful version control 

I often work with documents that require proper versioning and version control. In the past I have often used or recommended using the [semantic versioning scheme](http://semver.org) knowing that the scheme has actually been developed for software development. While it is possible to apply the semantic versioning to documents, some of its characteristics need to be adopted. 

While I often simply ignored the need for this adoption in the past, I finally found the time to rework the semver specification for use with documents. 

Summary
-------

Given a version number MAJOR.MINOR.PATCH, increment the:

1. MAJOR version when your document has undergone **significant changes**,
1. MINOR version when **new information has been added to the document or information has been removed from the document**, and
1. PATCH version when you made minor changes (**e.g. fixing typos**).

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

For more details you can find the latest specification [here](https://github.com/nils-tekampe/semverdoc/blob/master/semverdoc.md).

Meaningful Manual Version Control (MMVC)
------------------------------------
In most cases, version control systems (e.g. git) are the better choice when it comes to the question, how different versions of a document should be maintained. If however - for what reason ever - a manual version control process is required, the [MMVC](mmvc.md) has proven useful over many years and many different projects. 

### Contributions or comments
If you’d like to leave feedback, please open an issue on [github](https://github.com/nils-tekampe/semverdoc/issues).
If you'd like to contribute, please consider starting a Pull Request. 

Credit
-------
This work is heavily based on the Semantic Versioning specification as authored by [Tom
Preston-Werner](http://tom.preston-werner.com).

License
-------
Creative Commons - CC BY 3.0
http://creativecommons.org/licenses/by/3.0/
