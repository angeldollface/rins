# RINS :hamburger:

![GitHub CI](https://github.com/angeldollface/rins/actions/workflows/rust.yml/badge.svg) :hamburger:

***A small server to serve a directory locally. :hamburger:*** 

## ABOUT :books:

***RINS*** is a small file server I wrote to make my life easier. What it does is very simple: If you have some files in a directory that you'd like to serve on your local machine for whatever reason, ***RINS*** does this for you. :heart_on_fire:

## INSTALLATION :inbox_tray:

Make sure that you have the following tools installed and available from the command line:

- [Rust](https://www.rust-lang.org/tools/install)
- [Git](https://git-scm.com/downloads)

One you have that done, you can simply run this command from the command line:

```bash
$ cargo install --git https://github.com/angeldollface/rins
```

To check that the installation succeeded, run this command:

```bash
$ rins -v
```

## USAGE :hammer:

To serve a directory using ***RINS***, run this command, where `your_dir` represents the directory you'd like to serve. (You can view the result in your browser at the address ***RINS*** tells you.)

```bash
$ rins --sdir your_dir
# OR
$ rins -s your_dir
```

## CHANGELOG

### Version 1.0.0

- The Doll Update.
- Initial release.
- Initial upload to GitHub.
- Updated, published, and uploaded under my new name.

## NOTE :scroll:

- *RINS :hamburger:* by Alexander Abraham :black_heart: a.k.a. *"Angel Dollface" :dolls: :ribbon:*
- Licensed under the MIT license.
