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
If we try to navigate in the new directory we would get a error message like this 
<img src="https://github.com/DebankanSarkar989/90DaysOfDevOps/blob/main/Picture/GO/Install/Go-5.PNG"  align="center">

Our next step would be creating a directory go and subfolders bin,pkg,src 
```
mkdir go
cd go
mkdir bin,pkg,src 

```



