# Working with this data

We want you to use this data! It should be pretty easy for you to download data from our database so that you can create your own visualizations and analyses.

What should you do with the data once you've downloaded it? See our [list of tutorials](http://dhbasecamp.humanities.ucla.edu/afamfilm/working-with-the-data/) for working with this data.

## 1. View a larger version

As a first step, it'll make your life easier to view a full-size interface to the database. Click on the **View larger version** button at the bottom of the database window.

![][1]

[1]: images/working-with-this-data/view-a-larger-version.png

## 2. Understanding the tables

Our data is constructed as a simple relational database, with tables for **People**, **Films**, **Companies**, and **Sources**. All of the tables are linked: for example, **People** appear in **Films**, and **Films** are made by **Companies**. Linking these tables this way makes it possible to connect entities.

If you click on one of the linked entities -- a film title, for example -- you can see more about it. (You can't enter data, though! This version of the database is read-only.)

To read more about what each of these fields means, see our Data Dictionary.

![][2]

[2]: images/working-with-this-data/understanding-the-tables.png

## 3. Export the data

You can export data from our database one table at a time. Doing that is easy. Just click on the button with three dots (just to the right of the **Apply sort** button) and select **Download CSV**. (A CSV, or comma-separated value document, is like a generic table; it will open in any spreadsheet application.)

Then you can save the spreadsheet wherever you want!

![][3]

[3]: images/working-with-this-data/export-the-data.png

## 4. Filter the data

Airtable, the application we're using to host our data, gives you some nice options for filtering and sorting data. For example, here's how you can use the filters to find all the **actors** in our dataset.

Click on **Add filters**. Then **Add a filter**, specifying you want records where **Films (Appeared In)** is **not empty**. This will give you a list of all the people in our dataset who appeared in films.

You can layer filters, too. For example, you could filter records so that you only see people who were *both *actors and directors by specifying that you only want to see records where **Films (Appeared in) **and **Films (Directed) **are not empty.

![][4]

[4]: images/working-with-this-data/filter-the-data.png
