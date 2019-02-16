# TestAssignment

This sample application demonstrates the string match from the files available in a directory.


Instruction for setup:

1. Copy the jar to a directory.
2. Open the terminal and navigate to the copied jar directory.
3. run the jar using : java -jar SimpleSearch.jar "Path to the Folder containing files" (Note: Folder path should be within Quotes)
4. Promted with input in the command line (eg : Search > )
5. Enter the term to be searched in the files (eg : to be or not to be) 
6. Result will be outputed based on the search term found in the files in the descending order of the percentage found.
7. If no motch found retuns "No Matchs Found".
8. Enter quit to terminate.


Input / Sample Response:

java -jar SimpleSearch.jar "C:\Eclipse\Backendtest\SearchJava\inputFiles"

Total 2 files readed and indexed from the directory location C:\Eclipse\Backendtest\SearchJava\inputFiles
Search >
to be or not to be
File1.txt : 100 %
File2.txt : 83 %
Search >
test
No Matchs Found
Search >
quit



Note : Please refer to Sample.png for reference.

Reference Code found in src.zip
