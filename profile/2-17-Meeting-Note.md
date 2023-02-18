## New issues raised in midst of meeting discussion:

displaying link to seller's profile on selling page
https://github.com/CSE187-Team2/.github/issues/39
in the sellers page, display list of items and the people that sold them
for now, can just redirect to the generic user page

category/subcategory id relation validation in inserting/updating an item.
https://github.com/CSE187-Team2/backend/issues/123
when updating/inserting the category, the subcategory id should be within the list of subcategories for that category id.
as for the structure, we are gonna keep it as is (category and subcategory as separate tables) unless there is a need to change to profs tree structure for items/infinite nestings of subsubsub...categories

search bar
https://github.com/CSE187-Team2/.github/issues/40
need to develop a search bar and some means of comparing the user search text to items. Something like the LIKE operator in SQL. for instance, let's say we want to search for "mouse" and say the suer types "mou" so far. the sql query LIKE(mou%) could be used to match to items that start with mou (mouse, mousepad, mountain, etc). these items are displayed in some sort of side bar component.
