# JSON Formatting for the Resource List
***
- Each resource `resource_object` will have the following set of attributes:
  - `"title"`: The title of the resource; a `String`
  - `"subject_tags"`: Primary descriptive tags of the resource, i.e. the language being discussed and/or the specific disciplineary focus; an array of `String`s
  - `"author"`: The author or place of origin of the resource; a `String`
  - `"link_to_resource"`: The link to the resource; a `String`
  - `"other_tags"`: Secondary descriptive tags of the resource, i.e. information on the medium of delivery or audience focus; an array of `String`s