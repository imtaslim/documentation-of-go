<h1>FAQ</h1>

<b>Q: My other programming language requires that each statement end witha semicolon. Doesn’t Go?</b><br>
    A: You can use semicolons to separate statements in Go, but it’s not required (in fact, it’s generally frowned upon). <hr>  

<b>Q: What’s this Format button? Why did we click that before running our
code?</b><br>
A: The Go compiler comes with a standard formatting tool, called go fmt. The
Format button is the web version of go fmt.
Whenever you share your code, other Go developers will expect it to be in the
standard Go format. That means that things like indentation and spacing will be
formatted in a standard way, making it easier for everyone to read. Where other
languages achieve this by relying on people manually reformatting their code to
conform to a style guide, with Go all you have to do is run go fmt, and it will
automatically fix everything for you.We ran the formatter on every example we created for this book, and you should
run it on all your code, too!<hr>
<b>Q: My other programming language requires that an if statement’s
condition be surrounded with parentheses. Doesn’t Go?</b><br>
A: No, and in fact the go fmt tool will remove any parentheses you add, unless
you’re using them to set order of operations.<hr>