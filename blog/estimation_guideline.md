# Estimation Guideline

For those who estimate User Stories with points. This guideline tries to help development teams have a standard way to estimate complexity and risk, by proposing a concise definition of each level, and giving some practical examples.

_Note: This guideline is not for estimating extension. We assume that if there's a story that is not complex but involves many simple tasks, it should most likely be split, or be made just a task list._

## [ 1 point ] Trivial stories/tasks

A one point story or task is so trivial that can be done by someone that knows programming, but never tried the technology/languages being used to develop the current app. They usually don’t need any testing, or updating the tests is also as trivial.

Examples:

        As a Visitor I should be able to read “Terms and Conditions” instead of “Terms & Conditions”
        As a User I should be charged $15 instead of $25 for the basic membership
        As a User I should be able to see a maximum of 5 pages of results instead of 10

## [ 2 points ] Simple stories

Two points stories are very simple. Usually it involves simple server side functionality, like listings, or CRUDs of entities without many validations or complex relationships; and/or mobile views with out of the box controls and elements, but without major structural or style customizations.

Examples:

        As a User I should to see a list of all the products I’ve added to the system
        As a User I should be able to add tweet long notes to any of my products
        As a User I should be able to select several products to be deleted from the list of products

## [ 3 points ] Usual stories

Three point stories are complex but don’t necessary mean they have a high risk for unknowns. Usually they might involve complex entities relationships or validations on the server side, but a simple UX on the client side, or vice versa. They might also involve handling several simple entities that are all related to each other, or several simple UX screens. In any case these type of stories usually only require knowledge of the main programming technologies being used on the current app. Features that are common to many apps, and have an extensive documentation available might also qualify as three point stories.

Examples:

        As a User I should be able to create a product specifying its title, description, price, special parts, tags, and categories
        As a User I should be able to sort my friends by name, last connection time, last reply time, and/or organization
        As a User I should be able to drag and drop my selected products into different days of the current week

## [ 5 points ] Complex stories with a moderated risk factor

Five points stories usually involve third party services or tools; several complex entities or features being used together; or a complex customized UX. Thus the bigger difference with 3 points stories, is the risk factor, as five point stories usually involve research, or after implementation testing and tweaking.

Examples:

        As a User I should be able to see the pictures of the friends that are closer to me on a map
        As a User I should receive a payment deposit when the affiliates of my affiliates register a new user
        As a User I should be able to see the stock market value of my favorite companies

## [ 8 points ] Complex stories with a high risk factor

Eight points stories are driven by its risk factor. Usually involves complex and/or unusual third party tools, or extensive UX customizations. It might even be a risk of not being able to achieve the expect result due to technology limitations. Any 5 points story that becomes an 8 points story only because is too extensive, should probably be divided in several stories, instead of making an 8 points story.

Examples:

        As a User I should be able to see the faces in my uploaded pictures tagged automatically with the corresponding names
        As a User I should be able to navigate through my playlist by using hand gestures made 2 meters away from the cell phone
        As a User I should be able to hear my voice tone corrected by the app based on a MIDI file
