:package: rfsfrn's Brewfile
===========================

Requirements
------------

- An Intel CPU
- Mac OS X 10.5-10.11, macOS 10.12 or higher
- Command Line Tools: `xcode-select --install`,
  [https://developer.apple.com/downloads][1] or [Xcode][2]
- [Homebrew — The missing package manager for OS X][3]
- [Brew Bundle · GitHub][4]

See also

- [Interesting Taps & Branches · GitHub][5]
- [External Commands · GitHub][6]

Use Brewfile
------------

Paste that at a Terminal prompt:

```
curl "https://raw.githubusercontent.com/rfsfrn/homebrew-brewfile/master/Brewfile" -o ~/.Brewfile | brew bundle --file=.Brewfile
```



[1]: https://developer.apple.com/downloads "Sign in with your Apple ID - Apple Developer"
[2]: http://itunes.apple.com/us/app/xcode/id497799835 "Xcode"
[3]: http://brew.sh/ "Homebrew — The missing package manager for OS X"
[4]: https://github.com/Homebrew/homebrew-bundle
[5]: https://github.com/Homebrew/brew/blob/master/share/doc/homebrew/Interesting-Taps-%26-Branches.md
[6]: https://github.com/Homebrew/brew/blob/master/share/doc/homebrew/External-Commands.md
