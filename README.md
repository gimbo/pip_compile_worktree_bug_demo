# `pip_compile_worktree_bug_demo` — dependent repo for demo of a pip-compile pre-commit bug

This is part of a demonstration of a strange bug in the pip-compile tool when run as a
pre-commit hook under a git worktree, where it corrupts the worktree's git index.

See [pip-tools issue 1598](https://github.com/jazzband/pip-tools/issues/1598) and/or
[this gist](https://gist.github.com/gimbo/c2d43c9ff2f63771c6d1086422311b2b) for
information.
