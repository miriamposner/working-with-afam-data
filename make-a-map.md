# Make a map

Our dataset doesn't have a lot of locations in it, but we did provide locations of companies' founding whenever we could. In this tutorial, we'll use the web-mapping platform [CartoDB](https://cartodb.com/) to place these companies on a map.

This is the very barest-bones mapping tutorial -- there's a lot more to say about mapping, both technically and theoretically.

To learn how web-mapping works, I like Alan McConchie's and Beth Schechter's [*Anatomy of a Web Map*](http://maptime.io/anatomy-of-a-web-map/#0)* *and [Maptime's list of resources](http://maptime.io/lessons-resources/). On mapping in the digital humanities, you might look at Todd Presner, Dave Shepard, and Yoh Kawano's [*Hypercities: Thick Mapping in the Digital Humanities*](http://www.worldcat.org/oclc/861478405).

## 1. Switch to the Companies table

The **Companies** is the only one of our tables that contains location information. Switch to the **Companies** table by clicking on that tab.

![][1]

[1]: images/make-a-map/switch-to-the-companies-table.png

## 2. Filter the data

We don't have location information for every company (alas!), so let's filter this table so that it only shows companies for which we do have locations. This will make mapping easier later. Add a flter **Where Location founded is not empty**.

![][2]

[2]: images/make-a-map/filter-the-data.png

## 3. Export the data

Now that we only have records that contain locations, we'll export those records from the database. Click on the button with three dots on it and then download the table as a [CSV](https://support.bigcommerce.com/articles/Public/What-is-a-CSV-file-and-how-do-I-save-my-spreadsheet-as-one).

![][3]

[3]: images/make-a-map/export-the-data.png

## 4. Sign up for a CartoDB account

We're going to use the web-based mapping application CartoDB to map our data. CartoDB is often my first choice for web-based maps because it's very user-friendly, but also has some sophisticated features. You can easily share and embed CartoDB maps on websites. My students and I also like the way CartoDB maps look -- they're a little nicer-looking than Google maps, for example.

Sign up for a CartoDB account at [https://cartodb.com/signup](https://cartodb.com/signup) (after reading the terms and conditions, of course!).

![][4]

[4]: images/make-a-map/sign-up-for-a-cartodb-account.png

## 5. Click on "New Map" to see your dashboard

This is where you'll upload the data from which you'll build your maps. A note on terminology: CartoDB uses the phrase **Connect dataset** rather than **Upload dataset** because you *do *have the option of connecting CartoDB to a table that changes -- a Google spreadsheet that you continuously update, for example. That way your map will always be up to date.

We're just going to upload a spreadsheet today, but it's nice to know about this other option.

![][5]

[5]: images/make-a-map/click-on--new-map--to-see-your-dashboard.png

## 6. Click on Connect dataset and drag your table into CartoDB

After clicking on the **Connect dataset** tab, drag the file you downloaded in **Step 3** onto the field that says **Drag & drop your file.**

Then, click on **Connect Dataset** (the big green button at the bottom of your screen).

![][6]

[6]: images/make-a-map/click-on-connect-dataset-and-drag-your-table-into-cartodb.png

## 7. You have a map!

You might have to drag the map a bit so that it centers on the United States. CartoDB mapped your points automatically because the table you downloaded from our database contained geocoordinates (latitude and longitude coordinates), which CartoDB was smart enough to recognize.

![][7]

[7]: images/make-a-map/you-have-a-map-.png

## 8. Configure the infowindows

**Infowindows** is the name CartoDB gives to the little pop-up windows you expect to see when you click on a point. From the toolbar on the righthand side of the window, click on the icon that looks like a speech bubble.

Then, switch the toggles to the "on" position for all the fields you want to see in your infowindow.

You can also drag the fields to change the position in which they appear in the infowindows.

Now try clicking on your map's points again. You should now see infowindows.

![][8]

[8]: images/make-a-map/configure-the-infowindows.png

## 9. Save your map

Click on the title of your map to give it a title of your own.

![][9]

[9]: images/make-a-map/save-your-map.png

## 10. Publish your map

Click on the **Publish** button on the top right of the window. You can, at this point, either copy the link to the standalone map or copy a snippet of code that will allow you to embed your map on a webpage (like a WordPress blog). 

Copy the standalone link now and admire your map. You can now share your map with others!

![][10]

[10]: images/make-a-map/publish-your-map.png