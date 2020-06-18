## Sortable

### Instructions

You are a villain and your dream is to end with those annoying, yoga pants,
weird masks wearing superheroes. You never understood why are some of them
considered superheroes just because they are rich. Others annoy you with their
philosophical speeches. And of course that something tragic has had to happen
to them for the people to feel sorry for them. Anyway, we've found confidential
information about those superheroes.

Your task for the moment is to build a web page in order to organize all the
data from those smartypants. This information can be found [here](https://public.01-edu.org/public/subjects/sortable/data.json).

- All the data must be contained in a table
  - Images should be shown too, as images and not as a string
- The information must be displayed in multiple pages displaying from 10, 20,
  50, 100 or all results
- It must be possible to filter information by searching the name as a string
  (ex: superheroes that contain `man` in their name)
- It must be possible to sort all columns of the table (either alphabetically
  or numerically)
  -Initially all rows should be sorted by the column id by ascending order
  - First click will order the column by ascending value
  - Consecutive clicks will toggle between ascending and descending order
  - Note that, for example, the column `weight` will be composed of strings, so
    the correct order would be `['78 kg', '100 kg']` instead of the other way
    around

### Optional

Optionally you can make the search filtering system better, this way it would
be easier to pick your next target.

With the new and updated searching system :

- Will be possible to search for all fields
- Will be possible to search using handle operators like: include/ exclude for
  strings and equals/ not equals/ greater than/ lesser than/ greater or equal/
  lesser or equal for numbers (this includes weight and height)
- The url must be updated with the search, so if you copy and paste this url it
  will present the same result(s).
