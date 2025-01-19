![image](https://github.com/user-attachments/assets/844b2974-cec7-405a-97be-253336643fe6)  
 ![image](https://github.com/user-attachments/assets/d9755ac6-de34-48a7-aeee-be3a19e00f84)  
 ##### Architecture of .NET Application  
 ![image](https://github.com/user-attachments/assets/1af593b3-ce49-4991-8a58-24fb2e9df26e) ![image](https://github.com/user-attachments/assets/a35ba9b6-6bcc-4317-9685-9952a189f4e6)  
 Namespace is container for related classes. 
 ![image](https://github.com/user-attachments/assets/e969afe2-248e-4068-8496-833bb7c30e8c) ![image](https://github.com/user-attachments/assets/ceffd3ae-648a-4cef-b7cd-2702fd6d8663)  
 
Variables and Constants:  
![image](https://github.com/user-attachments/assets/4d29f291-61f2-4bf4-8267-ab96d55b8c0e)  
- We need to initializa a variable before we use it.
  - ##### Rules for Identifier
  - Cannot start with a number
  - Cannot include white space
  - Cannot be a reserve key word - can use @int if u want to use.
  - Use Meaningful name.
 ![image](https://github.com/user-attachments/assets/89331ef6-2a7f-4871-9b1e-fc8e6cf5b651)
![image](https://github.com/user-attachments/assets/a97c2a5e-56c8-4246-bd5c-b09c86bf6f00)

##### Non-Primitive Types  
- String
- Array
- Enum
- CLass

##### Overflowing  
byte  num = 255;  
num = num + 1;  

so the new value overflows the byte range which is not automatically checked in Dot Net  
we need to put as below:  

```c#
checked
{
byte  num = 255;  
num = num + 1; 
}
//due to this overflow will not happen and an exception is thrown.
```
##### Scope  
![image](https://github.com/user-attachments/assets/85d5a418-a1f3-4a74-8895-f67668214568)  
Within a block a variable can be accesible.  






 

