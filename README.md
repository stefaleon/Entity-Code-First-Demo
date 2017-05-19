# Code First Demo
[Entity Framework in Depth: The Complete Guide](https://www.udemy.com/entity-framework-tutorial/)

&nbsp;
## 00 Start the project
* In VS, create a Console Application project.

&nbsp;
## 01 Install Entity Framework
* In Package Manager Console, install Entity Framework:
```
PM> install-package EntityFramework
```

&nbsp;
## 02 Add the Posts class
* Create some code first. Add a class for posts.
```
public class Post
    {
        public int PostID { get; set; }
        public System.DateTime DatePublished { get; set; }
        public string Title { get; set; }
        public string Body { get; set; }
    }
```
