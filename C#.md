### 1. What is the difference between List and IEnumerable?<br/>
- List - List is a concreate class. It is not read-only.
- IEnumerable - IEnumerable is interface. It is read-only.
- https://stackoverflow.com/questions/17448812/practical-difference-between-list-and-ienumerable#:~:text=One%20important%20difference%20between%20IEnumerable,%2C%20you'll%20need%20List.<hr/>

### 2. What's the difference between Covert.ToString and .ToString method in C#?<br/>
- https://stackoverflow.com/questions/2828154/difference-between-convert-tostring-and-tostring<hr/>

### 3. What is constructor and how many types of constructor are there ?<br/>
- https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/constructors<hr/>

### 4. Difference Between Override & new in method overriding ?<br/>
- https://stackoverflow.com/questions/1399127/difference-between-new-and-override<hr/>

### 5. What is Coupling & Cohesion ?<br/>
- Coupling means dependency on others.
- Cohesion means completeness with itself.
- System should be Less Coupled and High Cohesive.<hr/>

### 6. What is Boxing and Unboxing?<br/>
- Boxing - It is process of converting value type to objet type ( Reference Type ) <br />
    Ex :- int i = 123;<br />
    // The following line boxes i.<br />
    object o = i;<br />
    
- Unboxing - It is process of converting objet type ( Reference Type ) to value type <br />
    Ex :- o = 123;<br />
          i = (int)o;  // unboxing<br />
- https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/types/boxing-and-unboxing<hr/>
