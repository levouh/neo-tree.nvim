# Contributing to Neo-tree

Contributions are welcome! To keep everything clean and tidy, please follow the
guidelines below.

## Code Style

This is open for debate, but here is the current style choices being observed:

- snake_case for all variables and functions
- unless it is a class, then use PascalCase
- other OOP things, like method names should use camelCase
- BUT we don't currently have any OOP parts and I don't think we want any

I prefer `local name = function()` over `local function name()`, just to be
consistant with the `M.name = function()` exports.

## Commit Messages

We use **semantic**, aka **conventional** commit messages. The official guide
can be found here: https://www.conventionalcommits.org/en/v1.0.0/

You can also just take a look at the commit history to get the idea. The
optional scope for this project would usually be the source, i.e.
`feat(filesystem): add awesome feature that does xyz`.

## Branching

The default branch is et to the current major version to make it simple for end
users visiting the repo. Pull Requests, however, should go to the `main`
branch. After a short testing period, it will be merged to the current release
branch.

This project requires a **linear history**. I don't trust merge commits.
This means you will have to rebase your branch on main before the pull request
can be merged. This can get a bit annoying in a busy repository, but I think it
is worth the effort.
