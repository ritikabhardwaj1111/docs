<table>
  <th> 
    Title
  </th>
  <th>
    Description
  </th>
  <th>
    Subjects
  </th>
  <th>
    Tags
  </th>
  <th>
    CatalogContent
  </th>
  <tr> 
    <td> .multiplyExact() </td>
    <td> Returns the product of the arguments </td>
    <td> Computer Science </td>
    <td> Fuctions , Methods , Airthmetic </td>
    <td> learn-java , paths/computer-science </td>
  </tr>
  </table>
  
  
  
  The ```Math.multiplyExact()``` method returns the product of the arguments and 
  will throw an exception if the result of the multiplication overflows the data type.
  The result should always be winthin the range of the data type.
  
  
  <h2> Syntax </h2>
  Math.multiplyExact(num1, num2)
  <br>
  num1 and num2 are two parameters that will be multiplied.
  <br>
  NOTE: both the parameters should be either be int or long.
  
  <h2> Example </h2>
  The following example showcases the .multiplyExact() method being applied two variables:
  
```
import java.lang.Math;
  class Main{
    public static void main(String[] args){
        long a = 8814L;
        long b = 2179L;
        System.out.println(Math.multiplyExact(a,b));
        int c = 7;
        int d = 2147483647;
        System.out.println(Math.multiplyExact(c,d));
    }
}
```
This produces the following output:
```
19205706
Exception in thread "main" java.lang.ArithmeticException: integer overflow
```


  
