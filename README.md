Download Link: https://assignmentchef.com/product/solved-ucs1411-exercise-12-file-organization-techniques
<br>
To develop a C program to implement the following file organization techniques

<ol>

 <li>Single level Directory</li>

 <li>Two level Directory</li>

 <li>Hierarchical Structure</li>

 <li>DAG</li>

</ol>

Procedure:

<ol>

 <li>Single Level Directory

  <ol>

   <li>Maintain a table containing the filename and the starting address location of that file.</li>

   <li>Give options for creating a new file.</li>

   <li>When creating the file, check for name collision.</li>

   <li>Update the table accordingly.</li>

  </ol></li>

 <li>Two level Directory

  <ol>

   <li>Maintain tables for MFD and UFD.</li>

   <li>Each MFD entry is a directory which in turn has entries for files.</li>

   <li>Give options for creating a directory, creating a file and searching for a file.</li>

   <li>Update the respective tables accordingly.</li>

  </ol></li>

 <li>Tree Structured Directory

  <ol>

   <li>Maintain tables for each directory starting from root.</li>

   <li>Limit each directory to have a maximum of five sub-directories and files.</li>

   <li>For each sub-directory follow the same table structure as described above.</li>

  </ol></li>

 <li>DAG

  <ol>

   <li>Data structure is same as tree structured directory but can create a link to an existing file.</li>

   <li>Give options for creating a directory, file and also links.</li>

  </ol></li>

</ol>

SAMPLE INPUT &amp; OUTPUT:

File Organization techniques

1.Single Level Directory

2.Two Level Directory

<ol start="3">

 <li>Tree structures directory</li>

</ol>

4.DAG

Enter your option: 1

1.Create a file

2.List the files

Enter your option:1

Enter the name of the file: file1 File created!

1.Create a file

2.List the files

Enter your option:1

Enter the name of the file: file2

File created!

1.Create a file

2.List the files

Enter your option:1

Enter the name of the file: file2 File already exists!

Enter your option:2

Contents of root directory

File Name    Location

*****           ***

*****           ***

<ul>

 <li></li>

 <li></li>

</ul>

 Similarly for all other structures