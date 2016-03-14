# Introduction #

Once the user chooses to proceed to checkout, the order is saved in an Excel 2003 worksheet.


# Details #

<p>The Excel sheet is stored in the folder "excel". This can be changed in the "settings.php" file. Since this new Excel file will need to be created, make sure your "excel" folder has write permission.</p>
<p>The excel file names are according to the order numbers sent to CC Avenue. So, order number 2's data will be in the file "excel/2.xls"</p>
<p>The algorithm for the Order Number, is according to the maximum number in the file name. So, if you have two orders, you will have files 1.xls and 2.xls in your folder. Based on this, the next order number "3" is picked because the highest number in the folder is 2. So make sure you do not delete these files unless you want to start your orders all over again, or you don't mind having repeat order numbers in CC Avenue.</p>
<p>To be more secure, you can <strong>password protect</strong> this folder to avoid any un-wanted access to this information.</p>