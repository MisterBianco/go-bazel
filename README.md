# Go - Bazel

An extremely simple go app that uses bazel for its build
system. Nothing fancy just experimenting with Bazel.

## Install tooling

#### Manjaro

```bash
$ yay -S taskfile-git bazel
```

#### Mac

```bash
$ brew install go-task/tap/go-task
$ brew tap bazelbuild/tap
$ brew install bazelbuild/tap/bazel
```

## Build project

#### Using task

```bash
$ task build
```

#### Manual

```bash
$ bazel build :all
```

TODO: Add docker rules and build a container.
