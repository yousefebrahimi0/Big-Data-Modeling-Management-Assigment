# Big-Data-Modeling-Management-Assigment

As it was shown in classes, graph databases are a natural way of navegating distinct types of data. For this first project we will be taking a graph database to analyse beer and breweries!

For reference the dataset used for this project has been extracted from kaggle, released by Evan Hallmark. Even though the author does not present metada on the origin of the data it is probably a collection of open data from places like [beeradvocate](https://www.beeradvocate.com/).

## Problem description

Explore the database via python neo4j connector and/or the graphical tool in the NEO4J webpage. Answer the questions. Submit the results by following the instructions

## Questions

    How many different countries exist in the database?
    Most reviews:
        Which Beer has the most reviews?
        Which Brewery has the most reviews for its beers? [Hint: 5-node path]
        Which Country has the most reviews for its beers? [Hint: 5-node path]
    Find the user/users that have the most shared reviews (reviews of the same beers) with the user CTJman?
    Which Portuguese brewery has the most beers?
    From those beers (the ones returned from the previous question), which has the most reviews?
    On average how many different beer styles does each brewery produce?
    Which brewery produces the strongest beers according to ABV? [Hint: database has NaN values]
    If I typically enjoy a beer due to its aroma and appearance, which beer style should I try? (Justify your answer well!) [Hint: database has NaN values]
    Using Graph Algorithms answer one of the following questions: [Hint: make sure to clear the graph before using it again]
        Which two countries are most similiar when it comes to their top 10 most produced Beer styles?
        Which beer is the most influential when considering beers are conected by users who review them? [Please use limit of 1000 on beer-review-user path]]
        Users are connected together by their reviews to beers, taking into consideration the "overall" score they review as a weight, how many communities are formed from these relationships? How many users has the biggest community? [Please use limit of 1000 on beer-review-user path]]
    Using Graph Algorithms answer one of the following questions:
        Which beer has the most similar reviews as the beer Super Bock Stout? [Hint:inspect two subsets: with and without the beer in question]
        Which user is the most influential when it comes to reviews made?
    If you had to pick 3 beers to recommend using only this database, which would you pick and why? (Justify your answer well!) [Hint: database has NaN values]
    Questions 8 to 10 are somewhat open, which means we'll also be evaluating the reasoning behind your answer. So there aren't necessarily bad results there are only wrong criteria, explanations or execution. 
