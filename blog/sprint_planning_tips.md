# Sprint Planning Tips

These tips should help the development team avoid in-sprint delays or roadblocks by mitigating risks during planning.

## Calibrating expectations

Make sure everyone is aware of the following before starting the meeting. The input of a planning meeting is a prioritized product backlog and an expected sprint goal. The development team, and the product owner are required to attend and participate. The output should be a sprint goal, and a sprint backlog.

### Expected sprint goal

The Product Owner/Manager is expected to have the backlog prioritised by the time the sprint meeting starts. That priority should follow its expected sprint goal.

The expected sprint goal its a simple statement that can be achieved during this sprint. Nevertheless, the development team should challenge that statement and make sure its valid and feasible given the workload that they'll pick. If everyone agrees its valid, it becomes the sprint goal, but if not, everyone should come to an agreement on what will the sprint goal be.

### These are a few examples of expected sprint goals.

1. Being able to sign in with Facebook, Twitter, and Github
2. Finish payment workflow
3. Solve all the listed bugs

### If the development team doesn't find those feasible, they could suggest these instead:

1. Being able to sign in with Facebook and Twitter
2. Finish PayPal integration.
3. Solve all the bugs related to the newsletter

## Challenge the backlog prioritisation

When everyone has an understanding and agrees on a sprint goal. Its good to take another look at the backlog prioritisation and make sure it make sense given the decided sprint goal. This time the Product Owner/Manager will have the input of the development team.

### Here are few tips on what to look for when evaluating the prioritization.

- Usually you shouldn't go further than the first 10 stories, as the sprint goal should not have changed much, but if it did, make sure you take a look at all the stories
- Remember that some user stories might depend on other, in that case, its possible you should reorder them.
- Some stories might be easier to do first than others, make sure you take that into consideration in case both stories are aligned to the sprint goal


## Split stories by feature

The most usual reason to split a story, is because it involves more than one feature. Usually thats easier to see during planning, because you start looking for clarification on its requirements and acceptance criteria.

### Here we have a few examples on this type of stories.

        As a User I should be able to sort the products list

Usually you can split this story by type of sorting. For example sorting by product attributes could be one card, sorting by categories and tags could be a different one.

        As a User I should be able to sign up with my email and password

This will most likely involve email confirmation, or maybe a forgot password feature, sometimes it might also be required to pick an image from Gravatar.

        As an Admin I should be able to delete a user account

Sometimes its a requirement to delete everything related to the user. That kind of requirement might have a very complex set of acceptance criteria that usually you can split in two stories.

## Split high risk features

8 or sometimes even 5 points stories involve risk, that usually mean you might find yourself unexpected roadblocks that can impact the development time. Its better to avoid having stories that can take longer than one sprint to be delivered.

Sometimes those stories involve only one complex feature. Either for being able to work in parallel with a team mate, or just because you prefer the divide and conquer way of development, you'll try to split that story.

### There are two usual ways of splitting those stories:

- Horizontal Split
- Vertical split

### Let me give you example stories, and the pros and cons of each approach.

        As a User I should be able to see my nearest friends on a map.

#### Horizontal Split

One story for developing the part to show the map and the markers
Another story for getting the list of closest friends and its location

Pros: The end result is just what the PO and/or Stake holders wanted and there is no wasted effort

Cons: The PO and/or Stake holders don't see anything until both stories are finished, thus they are not be able to give feedback sooner.

#### Vertical Split

        As a User I should be able to see a LIST of my nearest friends
        As a User I should be able to see my nearest friends as markers on a map

Pros: Enables feedback earlier (the basic of Agile methodologies)

Cons: There is wasted effort in showing the friends as a list, nevertheless the idea is to make that effort insignificant by using out of the box controls for display.

We strongly recommend splitting vertically. The main difficulty there is to be product minded. As you need to be able to visualize partial steps that deliver value to the end user.
