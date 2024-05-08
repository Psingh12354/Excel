# Excel
 
- 1,048,576 rows by 16,384 columns
- Select all column **CTRL + SPACE**
- Select all row **SHIFT + SPACE**
- Use row height and column width to modify block size.
- Press **Tab** to move to next column
- Press **Enter** to move to next row
- Modification can be removed by using "ESC"
- Delete the data including Format use **Delete**
- Clear will preserve the format
- **=** or **+** sign to start a formula
- **CTRL + X** to cut
- **CTRL + 1** format a cell.
- **ALT + E + S** to paste special
- To apply find in specific column select that column and press **CTRL + F**.
- **Column(Reference)** type this command and select any specific column and move it u will get the Reference.
- Use **VLOOKUP** to transfer data from one excel to other with comparison.
- Instanct movement in any corner press **CTRL + ARROWS**
- When we copy one formula to other cell it remained fixed put $ to make it flexible it will move to other column to multipy example-: "=$G4*H4" and "=$G4*I4" In this example G4 is fixed while H4 and I4 is flexible $ provides u this advantage.
- Press **ALT+Enter** to move split output to next row. Example "Hello World" if we press the key before World we get World in new row.
- Text to column in Data tab we can use it to split the data according to delimeted or by fixed width in multiple column.
- Select a range of column and press **F5** and choose special to select rc of specific type.
- DynamiC Nameing is the method to make attribute name dynamic in nature example-: **="Column_Selected"&Press_column**. You get the following output Column_SelectedColumn
- Select a range in a column and give name in the name box and apply operation. Example-: **Sum(Name)**.
- In Custom formating **0** represent fixed place holder while **#** represent variable placed holder.
- To use developer mode right click on the ribon and choose customize ribon and select developer.
- In developer mode we can start recording and perform repeative task by it like creating column schemas.
- To create a drop down list we can have data validation which help to choose from drop down menu. Steps go to data and click on data validation choose list or any as per you requirement and also u can enter the value by range or manual by comma split. If u try to enter any other value it gives error to stop go to data validation and stop errors.
- (Insert-> hyperlink-> Place in the documnet) Through this we can jump from one sheet to another.
- Freeze colum will be beneficial use this go to (select row below header-> Go to view -> Freze space) and now u can scroll freely without moving the header.
- Press **ALT** to open a tab shortcut key.
- **ALT + A + T** to create a filter.
- **File -> Options -> Quick access to toolbar** to know more about shortcuts.
- **Count** to count total number of cell.
- **Counta** counts non empty cell.
- **Countif** To count with condition.
- **Countifs** To count with multiple conditions.
- **Sum, Sumif and Sumifs** do the same as count.
- **Average** and **Averageif** use to find average.
- **Left**, **Right**, and **Mid** to find element in the selected column it's like slicing.
- **Upper** and **Lower** it is use to make the selected value in upper case or lower case.
- **Proper** it is use to make 1st character as capital and rest as small. Ex-: Hello.
- **&Concatenate** to concatenate multiple column. Ex-: with spaces =B1&" "&C1.
- **Max** and **Min** to get max and min values in selected.
- **Round** to do round of number.
- **VLOOKUP** stands for vertical lookup. Ex-: "=VLOOKUP(H4,B4:F12,2,FALSE)" by adding dollar we can make it flexbile and just copy and paste the commands "=VLOOKUP($H5,B4:F13,3,FALSE)"
- **HLLOKUP** is same as VLOOKUP only difference is change in direction work horizontally.
- Index to get value at particular index **=INDEX(B4:C12,5,2)**
- Match return specific item in array **=MATCH(H4,B4:B12,0)**
- Use Xlookup because it is more flexible "=XLOOKUP($H5,$B$4:$B$12,C$4:C$12)" and can easily be shift from one col to other with change in values.
- IFERROR to handle error condition **=IFERROR(F4/$F$13,"na")**.
- Pivot table help to interact dynamically **Select the columns -> Insert Bar -> Pivot Table**.
- Choose provide flexibily to choose.
- Goal **Data -> What if analysis -> Goal**.
- Data **Data -> What if analysis -> Data**.
- In find in files Notepadd++ we can give *.* to select all and to replace *.txt and then click replace all.
- **ALT + A + T** to filter.
- **CTRL + Minus symobl** Can delete the selected row
- CTRL + HOME to move in beginning notepad++
- Cummulative Sum for column ```=SUM($C$1:C1)```
- To remove 1st and last square bracket ```=LEFT(TEXTAFTER(D2,"["),LEN(TEXTAFTER(D2,"["))-1)```
- Extract data from xml or web xml use below query
```
#to pass url of xml
=WEBSERVICE("https://www.w3schools.com/xml/simple.xml")
#to print all the value in xml in 1 col
=FILTERXML(A1,"//breakfast_menu//food//*")
#to print only 1 col values
=FILTERXML(A1,"//breakfast_menu//food//name")
#to print the 1st value
=FILTERXML(A1,"//breakfast_menu//food//name")
#print in 3 different col
=CHOOSE({1,2,3},FILTERXML(A1,"//breakfast_menu//food//name"),FILTERXML(A1,"//breakfast_menu//food//price"),FILTERXML(A1,"//breakfast_menu//food//description"))
```
- Insert -> Table -> Create Table ```=[@Column1]*[@Column2]``` this formula will help to mutliple 2 col value without pointing to individual row
