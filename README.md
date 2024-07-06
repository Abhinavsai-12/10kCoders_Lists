# 10kCoders_Lists
Create a page using types of lists in HTML


Html list tags
1)      Unordered list
2)      Ordered list
3)      Description list
Unordered List <ul>:
Creates a list of items without any specific order.
Attributes:
type: Specifies the bullet style. Values can be "disc" (default), "circle", or "square".



    <ul type="circle">
      <li>Item 1</li>
      <li>Item 2</li>
    </ul>
 
Ordered List <ol>:
Used to create a list of items In specific order
Attributes:
type: Specifies the numbering style. Values can be "1" (default, decimal), "A" (uppercase letters), "a" (lowercase letters), "I" (uppercase Roman numerals), "i" (lowercase Roman numerals).
start: Specifies the starting value of the first item.
reversed: Reverses the numbering order.
    <ol type="I" start="10" reversed>
      <li>Item 1</li>
      <li>Item 2</li>
    </ol>
   
 
Description List <dl>:
Creates a list of term-description pairs.
Attributes:
None.


  <dl>
      <dt>Term 1</dt>
      <dd>Description 1</dd>
      <dt>Term 2</dt>
      <dd>Description 2</dd>
    </dl>



