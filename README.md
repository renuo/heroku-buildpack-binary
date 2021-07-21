# Heroku buildpack for executables

This buildpack can be used to deploy executable binary files to Heroku.

Your app **must** contain one single executable in the project root.
It **can** contain other non-executable files.
Simply add `https://github.com/renuo/heroku-buildpack-binary` to your Heroku app with "Add buildpack".

Attention: your executable must be cross-compiled for Heroku (x86_64).
You can find an example here: https://github.com/renuo/simple-single-tcp-rust
