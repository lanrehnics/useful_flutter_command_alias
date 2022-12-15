# useful_flutter_command_alias

What is an Alias ?

An alias is a way to make a command or series of commands in the terminal shorter or more convenient to use. This can be helpful if you have a long or complex command that you use frequently, as it allows you to use a shorter, easier to remember version of the command instead.

To create an alias, you can use the **`alias`**
 command in the terminal. For example, to create an alias for the **`git`**
 command, you could use the following command

```jsx
alias g="git”
```

As a flutter developer, I found myself running flutter commands like 

```jsx
flutter pub run build_runner build --delete-conflicting-outputs
```

also, when you have different flutter projects with different flutter versions then you might find yourself running flutter commands via proxy with tools like `fvm` (Flutter Version Manager). 

The command above with fvm will be. 

```jsx
 fvm flutter pub run build_runner build --delete-conflicting-outputs
```

Imagine having to remember and type this every time. !!!!

You can simply configure the command above for a shorthand version, example below.

```jsx
alias build_watch_delete="fvm flutter pub run build_runner watch --delete-conflicting-outputs”
```

all you need to next time when you need the command is run 

```jsx
build_watch_delete
```

**voila** .
