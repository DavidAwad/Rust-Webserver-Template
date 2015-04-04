#Rust Webserver Template

So I've been messing around with [Rust](http://www.rust-lang.org) for the past few days and I really like it. 

Taken straight from their 30 minute tutorial. "Rust is a modern systems programming language focusing on safety and speed. It accomplishes these goals by being memory safe without using garbage collection" 

This is a simple tutorial and boilerplate to get you started using Rust as a webserver, as it's REALLY fast at handling requests concurrently. 

If you've never used [Rust](http://www.rust-lang.org) before, try it out! You can try out the Rust Docs [here](http://rustbyexample.com). 

If you have never used it, throw this in a terminal to install the latest version.

```shell
$ curl -s https://static.rust-lang.org/rustup.sh | sudo sh
```
Rust is currently at release 1.0.0 Beta, so you might want to run this occassionally as Rust is being updated a good bit.   

So the web framework being used here is called [Iron](http://ironframework.io). It's an awesome web framework for Rust. (harharhar)

So you can clone this project. 
```shell
git clone https://www.github.com/DavidAwad/Rust-Webserver-Template/
```
Navigate to the directory.
```shell
cd Rust-Webserver-Template/ 
```
And use Crate to compile, build and run the project.  
```shell
cargo run
```
Then look up `localhost:3000`. 

## Thanks to the Rust Team
