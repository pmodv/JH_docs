# JuliaHub Quick Start Tutorial - Part 3

Welcome to *Part 3* of the *Quick Start* JuliaHub Tutorial!

Recall, for the purposes of this tutorial, imagine there are two users within our organization, who do the following:

1) A scientist, who writes a sophisticated program which generates a CSV output

2) An analyst, who performs various analyses on the scientist's program's CSV result 

The power of JuliaHub is its ability to enable seamless collaboration across a variety of users within an organization. 

This is the third part of our three-part tutorial:

* Part 1:  Creating a `Project` entity in JuliaHub
* Part 2:  Executing `Project` code and logging it; Sharing a `Project`
* Part 3:  Data Analysis Within JuliaHub Using `Pluto` notebooks

# Part 3

In this last part of the tutorial, we will:

* Access the project created in the prior two projects
* Connect to a `Pluto` instance
* Create a `Pluto notebook`
* Analyze the CSV-file data attached to the project
* Share results
  


## Objective 1 - Load Pluto ##

Recall in `Part 2`, we *shared* our project, `Demo - 3 Variable Model` with our analyst colleague(in our case, `Matt`), and we gave him `View` access rights to the project:  he is not expected to need to edit the code or even *run* the code - simply evaluate its output - the dataset. 

While `Pluto` may appear on your landing page, if it does not, click on the highlighted red rectangle `more...`:

![prepare pluto](images/before_pluto.png)

... to bring up a new page, in which you can then select to open, `Pluto`.  Click on `Launch`, within the highlighted red rectangle:

![open pluto](images/load_pluto.png)

If you notice, there will *briefly* appear a green modal in the top-right of your screen, in which you can click `Connect` to go to `Pluto`:

![connect pluto](images/pluto_connect_modal.png)

If, however, this modal disappears or you do not want to naviage this way, note that opening a `Pluto` notebook is considered an instance of a `Job`, and so you may navigate to the `Jobs` page, and connect there, as well, to your `Pluto` instance:

![connect pluto](images/job_list.png)

... and from within the list of `jobs`, choose to connect to your `Pluto` instance:

![connect pluto](images/pluto_connect_jobs.png)

Congratulations!  You have connected to your first `Pluto` instance.  You should see this page, now:

![loading](images/loading_page_pluto.png)

... and once it loads, you will be in your `Pluto` instance:

![in pluto](images/in_pluto_new.png)

Click on the, `Default (private)`, option for `Create a new notebook`:

![create new](images/click_new_notebook.png)


## Objective 2 - Create Pluto Workbook and load `Project` data ##

First, we will change the name of our notebook.  In the highlight region below...

![change name](images/replace_name.png)

... enter the notebook name, `Part_3_Workbook.jl`,

![rename](images/rename_notebook.png)

... and then click `Rename`, directly to the right of it:

![rename](images/rename_button1.png)



