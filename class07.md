# Tables
The <table> element is used to add tables to a web page.
A table is drawn out row by row. Each row is created with the <tr> element.
Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header).
You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
For long tables you can split the table into a <thead>, <tbody>, and <tfoot>
BASIC TABLE STRUCTURE

< table> The < table > element is used to create a table. The contents of the table are written out row by row.

< tr> You indicate the start of each row using the opening < tr> tag. (The tr stands for table row.) It is followed by one or more < td> elements (one for each cell in that row). At the end of the row you use a closing </ tr> tag.

< td> Each cell of a table is represented using a < td> element. (The td stands for table data.) At the end of each cell you use a closing </ td> tag.

< th> The < th> element is used just like the < td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

< thead> The headings of the table should sit inside the < thead> element

< tbody> The body should sit inside the < tbody> element.

< tfoot> The footer belongs inside the < tfoot> element.

 

 

# CONSTRUCTOR NOTATION:
Object constructors can use a function as a template for creating objects. First, create the template with the object’s properties and methods. A function called Hotel will be used as a template for creating new objects that represent hotels. Like all functions, it contains statements. In this case, they add properties or methods to the object. The function has three parameters.

e,i: class Polygon { constructor() { this.name = ‘Polygon’; } }

    const poly1 = new Polygon();

    console.log(poly1.name);
output:”Polygon”

 