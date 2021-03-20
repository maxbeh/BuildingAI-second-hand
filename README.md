<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Second-Hand data base

Final project for the Building AI course

## Summary

An data base with up to date iformation about the inventory of all second hand stores that wishes to participate. Automated uploads of new items and removal of sold ones 
with an AI based object recognition program for smart phones or perhaps an raspberry pi based camera and set up for easy streamlined photos with plain background. Program detects what kind of item and proposes a price determined by similar items. User can easily change and add description before a one click upload with necessary information like at what store the item is located, what it costs, what condition it is in and when it was uploaded. The set up then prints a QR code that will automatically remove the item from the database when scanned at check out.


## Background

The idea was from the start focused on only books after realizing the enormous amounts of books some second hand stores stash and how much place they take up. The low retail price and low demand in combination with the fact that a lot of people still want to buy books, but more than often a certain one rather than just browsing through the shelves of random books. The environmental aspect of the buy and trash culture we have in the western world needs to change and to combat online retailers second hand stores need to keep up with the conveniences of internet shopping.

List of challenges
* The low margins of second hand stores forces the set up to be very cheap.
* With plenty of smaller stores and personel without expertise in IT the set up needs to be easy and efficient to not cause more problems than it solves.
* The learning curve needs to be small so that the second hand personel is not put off at first try feeling that it would take too much of their time.
* Browsing the database must be user friendly so that it is as easy as the big retailers.
* A system of reservation for the costumers would be optimal so that you don't go to the store just to find the item already gone. A system that is enough flexible so that costumers in the store wont be frustrated with the fact that what they want to buy isn't available.


## How is it used?

The ideal solution is a tiny setup with an integrated computer, camera and, if neccesary, lighting. This in combination with a simple white background, a hanger for clothes and some sort of table to place smaller objects would serve as a form of automated photo booth. The store personal could conveniently just place the item in the setup, a photo would be taken and price, condition, size and other information would be proposed and easily confirmed before the upload to the database. At best it would take no longer than a few seconds more than just unpacking and inspecting the items like normal before putting them up for sale. The QR code would either be printed for each item or there could be reusable "QR-tags" that would be scanned and linked to the item in question.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
(![Second hand photo setup](Second_hand_photo_setup.jpg))

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
