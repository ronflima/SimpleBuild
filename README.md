# SimpleBuild

Simple build is a small set of Makefiles that are intended to automate Xcode
builds from the command line. Its design goal is to use simple tools to achieve
common build tasks like unit testing, coverage, archiving and app store
submission.

Since it is actually a Makefile, it let you use common tools already installed
on your macOS system. Its makefile is based on GNU Make 3.81 that is already
installed on your macOS system.

# Why SimpleBuild?

GNU Build system is on the market for years. It is pretty stable and works
pretty fine. For a standalone build, it is more than useful.

# How to use it?

Install the Makefile on your project directory. Create a _project.mk_ file with
your project's definitions and you are set. You can customize the Makefile
behavior by creating your own rules on _project.mk_.

Be sure to have both files _Makefile_ and _project.mk_ on the same directory of
your workspace or project bundles.

# License

This project is released under [MIT License](LICENSE).

