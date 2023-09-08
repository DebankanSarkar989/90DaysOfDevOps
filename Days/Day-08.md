# Setting up our GO enviroment 

Today we will deep dive into how to set up our GO enviroment in the local system . Before we head onto learning the basic of Go lang let us first walk through the steps to get Go installed in our local system . 

Lets install the Go lang from the <a href="https://go.dev/dl/ " > link here and download the installer based on the operating system you are working on . I will be working on the Windows system in this 90 days. 

<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-1.PNG"  align="center">

After downloading the installer based on the operating system you are operating on we can leave all the defaults in the place for now . Dnt worry if there is a version update and its not similar to mine . Proceed the same selecting the defaults still . 

<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-2.PNG"  align="center">

Run the Windows powershell/ terminal and check if Go is installed properly . 

```
go version
```
<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-3.PNG"  align="center">

In order to check the enviroment for Go . 
Make sure if the enviroment path is set and configured correctly . Copy paste the following code in the Powershell . 
```
go env
```
There would be a portion of the output where the Path set will be defined . If its not showing retry the steps again and check the process .  

```shell
GOPATH = C:\Users\Debankan\go
```

<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-4.PNG"  align="center">
If we try to navigate in the new directory we would get a error message like this .
This is because the directory isnt present in the user
<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-5.PNG"  align="center">

Our next step would be creating a directory go and subfolders bin,pkg,src 
```
cd C:\Users\(YourUser)
mkdir go
cd go
mkdir bin,pkg,src 
```
Install VS Code from <a href="https://code.visualstudio.com/">here</a>. Set the defaults while installing . 

<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-6.PNG"  align="center">
Head over to the folder we recently created and right click to open with code 
<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-7.PNG"  align="center">

In VS code on the left side make a new file in the src folder make a file name "main.go"

 As soon as you hit enter on the main.go you will be asked if you want to install the Go extension and also packages you can also check that empty pkg file that we made a few steps back and notice that we should have some new packages in there now?

 <img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-8.PNG"  align="center">

Lets write the basic "Hello program" for in our main.go file .

```Go
package main

import "fmt"

func main() {
	fmt.Println("Hello #90DaysOfDevOps")
}
```
Execute the following commands in powershell 
```
go run main.go
```
Now if we want to run this same program in other Window machine. We can do that by building our binary file using the command 
```
go build main.go
```
<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-9.PNG"  align="center">

## Additional Resources 

- <a href="https://www.youtube.com/watch?v=yyUHQIec83I">Golang Tutorial for Beginners | Full Go Course </a>

- <a href="https://www.w3schools.com/go/">Go Tutorial</a>

- <a href="https://www.youtube.com/watch?v=3lazW_dSXKM"> Learn Golang in 10 minutes! </a> 

<br>

Join me for <a href="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Days/Day-09.md">Day 9</a> to continue the journey together.






