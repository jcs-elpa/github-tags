[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![CI](https://github.com/jcs-elpa/github-tags/actions/workflows/test.yml/badge.svg)](https://github.com/jcs-elpa/github-tags/actions/workflows/test.yml)

# github-tags
> Retrieve tags information through GitHub API

```el
(let ((data (github-tags "jcs-elpa/github-tags")))
  (message "names: %s" github-tags-names)
  (message "zipball: %s" github-tags-zipball-urls)
  (message "tarball: %s" github-tags-tarball-urls)
  (message "commit: %s" github-tags-commits)
  (message "nodeId: %s" github-tags-node-ids)
  )
```

## Contribution

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
