# 02_NamingConvCSharp



1. Always use camelCase with  Function parameter and local variables
   public string GetPosts(string postId)
{
    int numberOfPost = 0;     //local
}



2. Always use PascalCase for class names
public partial class About : Page
{
   //...
}


3.Always use PascalCase for method names or function name
public string GetPosts(string postId)
{
   //...
}



4.Property name : PascalCase
public int Name{get;set;}
public int HouseNumber {get;set;}



5.Interface
Always use letter "I" as prefix with name of interface. After letter I, use PascalCase.

public interface IUserName
{
    //...
}


6.Private variable name : use prefix _name and remaining is camelCase;
private int _salary = 100;


7.public variable name : use PascalCase for public variable
public int Salary = 100;


8. enum : write in PascalCase



