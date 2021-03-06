Q: A new Excel workbook does not populate as part of the data import.
---------------------------------------------------------------------

**A:** Some users have reported issues with Microsoft Excel not generating the workbook populated and linked to WQReview. The issues are not consistent among users and many have reported no problems. If there are any open, unsaved Excel workbooks, try saving them and exiting out/restarting WQReview. If there is an open Excel workbook that has the "Enable Content" warning banner at the top, click the banner before running WQReview. Try closing all other instances of Excel before launching and running WQReview.

Q: After importing data and populating the Excel workbook, there's no stations or parameters available in the Result-level review tab.
--------------------------------------------------------------------------------------------------------------------------------------

**A:** Return back to the Import/save Data -&gt; Import from internal NWIS server tab. Even if the progress bar in the bottom right has finished, wait for a summary of the data import to populate on the tab (Number of samples retrieved, number of results retrieved, etc.). Longer date ranges and sites with many parameters can take minute to sync after populating Excel. After the summary has loaded, return to the Result-level review tab and the stations and parameters should now be populated.

Q:I click "Get Data" in the import screen and nothing happens except I get the messages "Problem with data import, please check import criteria" and "first argument is not an open RODBC channel".
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**A** This error indicates that your ODBC connection is not setup correctly. Follow the steps in the installation instructions for setting up the ODBC connection. Make sure that the "DSN" entry box contains the name of your NWIS ODBC connection EXACTLY as named in the ODBC administrator User DSN section.

Q: How do I remove an entry from an input box, like deleting a site or parameter selection?
-------------------------------------------------------------------------------------------

**A** Simply click the specific entry you want to delete and hit "backspace" or "delete" to remove it. Alternatively, click the cursor in the input box as if adding a new entry, but hold down backspace to delete entries.

Q: Nothing appears in my Blank, Replicate, or Whole vs Part tables and I get an error message.
----------------------------------------------------------------------------------------------

**A** There are no data available at your site(s) for these tables. In the case of replicates, this could be due to miscoded environmental-replicate sample pairs. Make sure both the environmental and replicate sample of the pair are coded with Sample Type = 7

Q: I try to read in a QWDATA site file to pull data and it does not work.
-------------------------------------------------------------------------

**A** QWDATA site files will not work because the agency code is placed infront of the site number. The sitefile must be 1 column of site numbers only.

Q: I have tons or parameters at my site, is there an easier way to select a parameter than scrolling through hundreds of parameters?
------------------------------------------------------------------------------------------------------------------------------------

**A** Yes. Click in the input box for parameter code and type part of the parameter code number or the analyte name and the box will automatically filter to your search.

Q: Can I save or print plots I generate in the GUI?
---------------------------------------------------

**A** Yes. For interactive plots, hovering over the plot will bring up a menu in the plot's upper left corner. Use the "Download plot as a png" option. For non-interactive plots right-click on the plot and select "save image as".

Q: Can I plot multiple sites on the same plot?
----------------------------------------------

**A** In most cases, yes. Select multiple sites in the station number input. By default all sites will be plotted on the same plot, with no symbology to differentiate the sites. If you would like to have separate plots, select "Facet" from the Multisite drop down menu.

Q: Why are some symbols highlighted in orange?
----------------------------------------------

**A** Samples or results that have been selected from the tables in Chrome will show up as highlighted in the corresponding plots.
