# Virtual Cookbook

Link to Application: https://jandrews16.github.io/virtual-cookbook/

This application allows users to create their own virtual cookbook as well as find recipes based on their desired ingredients. Key features the ability to save personal  recipes on different devices as well as search and save recipes based on specific ingredients.


## Code Description

The code uses a server-side api which returns various recipes based on specific ingredient inputs. 


## Overview

WHEN a user enters the page
THEN they are greeted to the home page which will display any cookbooks that they may have saved
IF user does not have any cookbooks
THEN they are able to navigate to the top of the page where they can click on "Add Recipe" and input their own recipes
WHEN user clicks on "submit"
THEN their recipe will be added to their dashboard and will be able to open the recipe to view its contents
IF user is tired of their own recipes
THEN they can navigate to the top of the page and click on "Search" where they can then search for recipes based on ingredients
WHEN user enters the search page
THEN they will input ingredients that they already have available which will then be used to run our API to search for recipes
WHEN user clicks on "Search"
THEN they will be presented with 5 different recipe titles to choose from
WHEN user clicks on recipe title
THEN they will be presented with the ingredients and instructions for that recipe
IF user likes a recipe
THEN they can click on "Save" which will save that recipe on their dashboard

FINALLY
WHEN user leaves the application or refreshed page 
THEN their cookbooks will be stored in local storage


## Demo of Application

![vrtual cookbook demo](./assets/images/Virtual Cookbook Demo.mp4)