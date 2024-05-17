# Literature as Markdown

A collection of classic literature presented in markdown format. All titles from the public domain.

This is my own spin on [mlschmitt](https://github.com/mlschmitt)’s amazing collection.
My attempt is to make this library compatible with [Obsidian.md](https://obsidian.md/).

To-Do:
- [ ] Insert yaml metadata.
- [ ] Create bibliography for the authors.
- [ ] Expand the collection.

Other excellent resources for classic books:
* [Standard Ebooks](https://standardebooks.org/)
* [Project Gutenberg](http://www.gutenberg.org/)


[[List of Authors]]

***
## Properties
### Literature Properties
Metadata in the individual literature files.

| Name of Property    | Description                                                                                                                                                                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| aliases             | [Obsidian] Alternative names for the file when linking.                                                                                                                                                                                                          |
| tags                | [Obsidian] Tags for the file.                                                                                                                                                                                                                                    |
| prefer-view         | [Obsidian] Sets the default view to Read. (Require ‘[Set View Mode per Note](obsidian://show-plugin?id=frontmatter-viewmode)’ plugin.)                                                                                                                           |
| title               | The title of the book.                                                                                                                                                                                                                                           |
| full-title          | The full title, including sub-titles.                                                                                                                                                                                                                            |
| short-title         | A shortened version of the title.                                                                                                                                                                                                                                |
| author              | Name of the author(s). [Obsidian] WikiLink to the bibliography.                                                                                                                                                                                                  |
| contributor         | Name of the contributor(s). [Obsidian] WikiLink to the bibliography.                                                                                                                                                                                             |
| year-of-publication | The year the work was first published.                                                                                                                                                                                                                           |
| number-of-words     | Number of words in the work, only counting the main text.                                                                                                                                                                                                        |
| length              | (Only for prose.) Determined by ‘number-of-words’.<br><br>Micro (0-100 Words)<br>Flash (100-1000 Words)<br>Short (1000- 7,500 Words)<br>Novelette (7,500-20,000 Words)<br>Novella (20,000-50,000 Words)<br>Novel (50,000-110,000 Words)<br>Epic (110,000+ Words) |
| literary-genre      | All that applies, with _no_ complicated genre taxonomy.                                                                                                                                                                                                          |
| language            | The language the current version is in.                                                                                                                                                                                                                          |
| original-language   | The language of the original work.                                                                                                                                                                                                                               |
| translator          | Name of translator(s) of current version. (Ignore if ‘Language’ == ‘Original Language’)                                                                                                                                                                          |
| series              | Name of the series that work is part of. (If applies.)                                                                                                                                                                                                           |
| editor              | Name of the editor(s). (If applies.)                                                                                                                                                                                                                             |
| note                | Any additional comments.                                                                                                                                                                                                                                        |

### Bibliography Properties
Metadata in the bibliography file.

| Name of Property | Description                                                                                                                                          |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| name             | Full name of the author. Inverted order (“_Austen, Jane_”) for western names.                                                                        |
| life-time        | Date of birth and date of death connected with a en-dash `–`. <br>ISO 8601 format without separators. <br>YYYY MM DD <br>(_1775 10 16 – 1817 07 18_) |
| nationality      | Country of origin.                                                                                                                                   |
| common-genres    | Genres that the author commonly written in.                                                                                                          |
| common-themes    | Usual themes for the author.                                                                                                                         |
| biography        | Short history of the author.                                                                                                                         |
| note             | Any additional comments.                                                                                                                             |

### Table Heading
The table in the bibliography files. (Essentially the same as “Literature Properties”.)

| Name of Table Heading | Description                                                                                                                                                                                                                                                      |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ✓                     | Work is in directory                                                                                                                                                                                                                                             |
| Number                | Some collection of works have numberings.<br>(Like Shakespeare’s Sonnet #18.)                                                                                                                                                                                    |
| Title                 | Title of the work. (Same as file name.) [Obsidian] Using wikiLinks.                                                                                                                                                                                              |
| Year                  | Either year of publication or year written (if the work is unpublished).                                                                                                                                                                                         |
| Contributor           | Name of person who contributed to writing the work. (“Co-authors”).                                                                                                                                                                                              |
| Words                 | Number of words.                                                                                                                                                                                                                                                 |
| Length                | (Only for prose.) Determined by ‘number-of-words’.<br><br>Micro (0-100 Words)<br>Flash (100-1000 Words)<br>Short (1000- 7,500 Words)<br>Novelette (7,500-20,000 Words)<br>Novella (20,000-50,000 Words)<br>Novel (50,000-110,000 Words)<br>Epic (110,000+ Words) |
| Genre                 | Genre of the  work.                                                                                                                                                                                                                                              |
| Language              | Language of the work. OG or Translation.                                                                                                                                                                                                                         |
| Translator            | Name of translator (if applies).                                                                                                                                                                                                                                 |
| Series                | Name of the series the work is in (if applies).                                                                                                                                                                                                                  |
| Editor                | Name of editor (if applies).                                                                                                                                                                                                                                     |
| Note                  | Any additional comments.                                                                                                                                                                                                                                         |

***
