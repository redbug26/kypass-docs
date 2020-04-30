# Automatic import

Do you know that KyPass Companion could import a dynamic kdb/kdbx database or .csv file in your kdbx \(KeePass v2\) database ?

![import1](https://i2.wp.com/www.kyuran.be/wp-content/uploads/2015/12/import1-150x150.png?resize=150%2C150)How ?

1. Select the folder where you want to insert/update the exported entry.
2. Go to File/Create Import Task
3. Give a name for your task.
4. Select the URL of the kdb/csv file or select directly the file from the file browser.  
   For the .csv file, the format is:

   1. Line 1: &lt;fieldname&gt;;&lt;fieldname&gt;;.. with fieldname is title, username, password, url or any name for custom attributes.
   2. Line 2 and others, your values separated by a semicolon

   ![import2](https://i2.wp.com/www.kyuran.be/wp-content/uploads/2015/12/import2-1024x737.png?resize=474%2C341)

5. Enter the password and/or the keyfile if the import file is a kdb database.
6. Check the ‘add to task’ checkbox. It will save the task in the folder you have selected previously in step 1.
7. Check ‘update entries’ checkbox if you want that, when then task is launched, the entries are update and not created each time.
8. Check ‘ignore groups’ checkbox if you don’t want to keep the tree in the imported kdb database.
9. Click on the ‘run’ button to do the first import.

The task is now created.

![import3](https://i2.wp.com/www.kyuran.be/wp-content/uploads/2015/12/import3-150x150.png?resize=150%2C150)

Each time you want to run again the task, go in View/Display task list and select the task you want to run.

{% file src="../../.gitbook/assets/sample.csv" caption="Sample file" %}

