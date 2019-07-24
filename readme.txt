Hello World Program.


C Program:
$ gedit HelloWorld.c
$ cat HelloWorld.c
#include <stdio.h>

int main(){
    printf("Hello World!\n");
    return 0;
}
$ gcc HelloWorld.c -o HelloWorld
$ ./HelloWorld
Hello World!


C++ Program:
$ gedit HelloWorld.cpp
$ cat HelloWorld.cpp
#include <iostream>
using namespace std;

int main(){
    cout<<"Hello World!"<<endl;
    return 0;
}
$ g++ HelloWorld.cpp -o HelloWorldCpulsplus
$ ./HelloWorldCpulsplus
Hello World!


Java Program:
$ gedit HelloWorld.java
$ cat HelloWorld.java
public class HelloWorld{
    public static void main(String[] args){
        System.out.println("Hello World!");
    }
}
$ javac HelloWorld.java
$ java HelloWorld


Python Program:
$ gedit HelloWorld.py
$ cat HelloWorld.py
print("Hello World!")
$ python HelloWorld.py
Hello World!

$ cat HelloWorld.py
#!/usr/bin/python
print("Hello World!")
$ chmod 755 HelloWorld.py
$ ./HelloWorld.py
Hello World!
