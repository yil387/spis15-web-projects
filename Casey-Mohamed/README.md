Notes from Phill for Casey and Mo

Try this: http://docs.python-guide.org/en/latest/scenarios/scrape/

* In the http://hdh.ucsd.edu/DiningMenus/default.aspx?i=64 HTML, we find:

```
  <td style="vertical-align:top;" class="menuList">
```

That is probably the element you want to look for when trying to find the menu items.

Inside that, we have stuff like this:

```
 <ul class="itemList">
                                                                        
                                <p class="category">Breakfast Special</p>
                                <li style="margin-bottom:10px; margin-left:40px;"><a href="nutritionfacts.aspx?i=362227163" target="_blank">Corned Beef Hash</a>&nbsp;<img src="images/glutenfree18.png" border="0" alt="gluten free item" /></li>
                                                               
                                <p class="category">Hot Breakfast</p>
                                <li style="margin-bottom:10px; margin-left:40px;"><a href="nutritionfacts.aspx?i=362227164" target="_blank">Assorted Breakfast Toast</a></li>
                                                               
                                
                                <li style="margin-bottom:10px; margin-left:40px;"><a href="nutritionfacts.aspx?i=362227165" target="_blank">Beans</a>&nbsp;<img src="images/vegan18.png" border="0" alt="vegan item" />&nbsp;<img src="images/glutenfree18.png" border="0" alt="gluten free item" /></li>
                                                               
                                
                                <li style="margin-bottom:10px; margin-left:40px;"><a href="nutritionfacts.aspx?i=362227166" target="_blank">Cage Free Scrambled Eggs</a>&nbsp;<img src="images/vegetarian18.png" border="0" alt="vegetarian item" />&nbsp;<img src="images/glutenfree18.png" border="0" alt="gluten free item" />&nbsp;<img src="images/tastebuds18.png" border="0" alt="taste bud approved item" /></li>


```
