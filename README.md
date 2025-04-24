# Writing an Interpreter in Go

This is my implementation of an interpreter for the Monkey programming language published in the book, ["Writing an Interpreter in Go"](https://interpreterbook.com).

## Chapter 0

Thorsten Ball says you'll be able to understand the code in the book even if you've never written a line of Go, and assuming you have some prior programming experience, that might be true.  But it doesn't mean you know how to set up a new Go project.  It's not hard, follow along below.

1. Download and install [Visual Studio Code](https://code.visualstudio.com/download):
2. Download and install Go from https://go.dev/doc/install.
  - <b>Note</b>: close and reopen Visual Studio Code if it's open otherwise it won't be aware of the new Go installation.
3. Install the official [Go add-on](https://marketplace.visualstudio.com/items?itemName=golang.go) for Visual Studio Code
4. Open a new folder for your project (call it something like `waiig` or `monkey`).
5. Open a new terminal and run `go mod init monkey`.  This will create a go.mod file in the root of your project identifying it as a module called monkey.
6. When you see a comment at the top of a section of code like `// token/token.go` that means create a new file called `token.go` in a new subfolder called `token`.
7. The first time you open a `.go` file VSCode should install some Go tools.  It doesn't give any indication of progress and takes around a minute.  Wait for the `ll tools successfully installed. You are ready to Go. :)` message before continuing.

Download the accompanying materials from:
- [Completed exercises](https://interpreterbook.com/waiig_code_1.7.zip)
- [The "Lost" Chapter](https://interpreterbook.com/waiig_lost.zip) (read about it [here](https://interpreterbook.com/lost/))
