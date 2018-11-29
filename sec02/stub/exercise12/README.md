# Section 02 : Lab 01 - Greeter

## Given

I have provided several packages that you will need to install first to assist you with the lab. To install the packages you need, type: `go get github.com/striversity/glft/shared/...`

eg: $ go get github.com/striversity/glft/shared/...

After running this command, you now have access to several pacakges. You will use the 'input' and 'cal' pacakges in this lab.

## TODO 1

Write a Golang program which meets the following requirements:

1. Get the user and ask them for their name. *HINT* Use the 'input' package 'input.ReadString()' function.
2. Print the user's name with a message.
3. Inform the user of the current date and time using 'cal.DateNow()' and 'cal.TimeNow()'.

### Example program output:

```zsh
go run main.go
```

> What is your name: Verrol
>
> Hi, Verrol
> Today is Sat, 21 Apr 2018. The current time is 5:35PM.
