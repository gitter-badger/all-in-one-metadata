# Schema Properties Used

We use different types in every of these 3 levels
- **Network level**
  - WebSite
- **Site level**
  - Book
  - Course
- **Post level**
  - WebPage
  - Chapter
------------------------
# Site level
## Book

Properties from: [Book](https://schema.org/Book  "https://schema.org/Book")

| **Used By** | **Property** | **Type** | **Description** |
| ----------- | ------------ | -------- | --------------- |
| PB - Metadata | [bookEdition](http://schema.org/bookEdition)|[Text](https://schema.org/Text)|The edition of the book.|
|PB - Core| [bookFormat](http://schema.org/bookFormat)|[BookFormatType](http://schema.org/BookFormatType)| The format of the book. |
|PB - Metadata | [illustrator](http://schema.org/illustrator)|[Person](http://schema.org/Person)| The illustrator of the book. |
| Not Used | [isbn](http://schema.org/isbn)|[Text](https://schema.org/Text) | The ISBN of the book.|
| Not Used | [numberOfPages](http://schema.org/numberOfPages) | [ Integer ](http://schema.org/Integer) | The number of pages in the book. |

Properties from: [Creative Work](https://schema.org/CreativeWork "https://schema.org/CreativeWork")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Core | [about](http://schema.org/about "http://schema.org/about") | [Thing](http://schema.org/Thing "http://schema.org/Thing")| The subject matter of the content.|
| PB - Core | [alternativeHeadline](http://schema.org/alternativeHeadline "http://schema.org/alternativeHeadline") |  [Text](https://schema.org/Text "https://schema.org/Text") | The subtitle of the book. |
| PB - Core | [author](http://schema.org/author "http://schema.org/author") | [Person](http://schema.org/Person "http://schema.org/Person") | The author of the book. |
| PB - Core | [copyrightHolder](http://schema.org/copyrightHolder "http://schema.org/copyrightHolder") | [Thing](http://schema.org/Thing "http://schema.org/Thing") | Name of the copyright holder. |
| PB - Core | [copyrightYear](http://schema.org/copyrightYear "http://schema.org/copyrightYear") | [Number](http://schema.org/Number "http://schema.org/Number") | Year that the book is/was published. |
| PB - Core | [datePublished](http://schema.org/datePublished "http://schema.org/datePublished")| [Date](http://bib.schema.org/Date "http://bib.schema.org/Date") | Date of first broadcast/publication. |
| PB - Core | [editor](http://schema.org/editor "http://schema.org/editor") | [Person](http://schema.org/Person "http://schema.org/Person") | Specifies the Person who edited the book.
| PB - Core | [inLanguage](http://schema.org/inLanguage "http://schema.org/inLanguage") | [Language](http://schema.org/Language "http://schema.org/Language") | The language of the book.|
| PB - Core | [keywords](http://schema.org/keywords "http://schema.org/keywords") | [Text](https://schema.org/Text "https://schema.org/Text") | Keywords or tags used to describe this content. |
| PB - Core | [offers](http://schema.org/offers "http://schema.org/offers") | [Offer](http://schema.org/Offer "http://schema.org/Offer") | An offer to provide this item. |
| PB - Core | [publisher](http://schema.org/publisher "http://schema.org/publisher") | [Person](http://schema.org/Person "http://schema.org/Person") | The publisher of the book. |

Properties from: [Thing](https://schema.org/Thing "https://schema.org/Thing")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Core | [description](http://schema.org/description "http://schema.org/description") | [Text](https://schema.org/Text "https://schema.org/Text") | A short paragraph about your book. |
| PB - Core | [image](http://schema.org/image "http://schema.org/image") | [URL](https://schema.org/URL "https://schema.org/URL") | The cover of the book. | 



## Course

Properties from: [Course](https://schema.org/Course  "https://schema.org/Course")

| **Used By** | **Property** | **Type** | **Description** |
| ----------- | ------------ | -------- | --------------- |
| PB - Metadata | [courseCode](https://schema.org/courseCode "(https://schema.org/courseCode") | [Text ](https://schema.org/Text ) | The identifier for the Course used by the course provider (e.g. CS101 or 6.001). |
| PB - Metadata | [coursePrerequisites](https://schema.org/coursePrerequisites) | [AlignmentObject](https://schema.org/AlignmentObject) | Requirements for taking the Course. |
| Not Used | [hasCourseInstance](https://schema.org/coursePrerequisites) | [CourseInstance ](http://schema.org/CourseInstance) | An offering of the course at a specific time and place or through specific media or mode of study or to a specific section of students. |

Properties from: [Creative Work](https://schema.org/CreativeWork "https://schema.org/CreativeWork")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Metadata | [educationalAlignment](https://schema.org/educationalAlignment "https://schema.org/educationalAlignment") | [AlignmentObject](https://schema.org/AlignmentObject "https://schema.org/AlignmentObject") | The educational level according to ISCED or/and to another framework of our choice. Also the Subject name and the subject type according to ISCED. |
| PB - Metadata | [interactivityType](https://schema.org/interactivityType "https://schema.org/interactivityType") | [Text ](https://schema.org/Text "https://schema.org/Text") | The predominant mode of learning supported by the learning resource. Acceptable values are 'active', 'expositive', or 'mixed'. |
| PB - Metadata | [provider](https://schema.org/provider "https://schema.org/provider") |  [Thing](https://schema.org/Thing "https://schema.org/Thing") | The Organization, University or Person who provides this subject. |
| PB - Metadata | [typicalAgeRange](https://schema.org/typicalAgeRange "https://schema.org/typicalAgeRange") | [Text ](https://schema.org/Text "https://schema.org/Text") |The target age of this book. |
| PB - Metadata | [learningResourceType](https://schema.org/learningResourceType "https://schema.org/learningResourceType") | [Text ](https://schema.org/Text "https://schema.org/Text") | The kind of resource this book represents. |
| PB - Metadata |  [license](https://schema.org/license "https://schema.org/license") | [URL](https://schema.org/URL "https://schema.org/URL")  | A license document that applies to this content, typically indicated by URL. |
| PB - Metadata | [isBasedOnUrl](https://schema.org/isBasedOnUrl "https://schema.org/isBasedOnUrl") | [URL](https://schema.org/URL "https://schema.org/URL") | The URL of a website/book this book is inspirated of. |

Properties from: [Thing](https://schema.org/Thing "https://schema.org/Thing")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Metadata | [description](https://schema.org/description "https://schema.org/description") |[Text ](https://schema.org/Text "https://schema.org/Text") | A short description about this subject. |
| PB - Metadata | [name](https://schema.org/name "https://schema.org/name") | [Text ](https://schema.org/Text "https://schema.org/Text")|The name of the subject. |

-----

# Post level

## WebPage

Properties from: [Creative Work](https://schema.org/CreativeWork "https://schema.org/CreativeWork")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Core | [about](http://schema.org/about "http://schema.org/about") | [Thing](http://schema.org/Thing "http://schema.org/Thing")| The subject matter of the content.|
| PB - Core | [copyrightHolder](http://schema.org/copyrightHolder "http://schema.org/copyrightHolder") | [Thing](http://schema.org/Thing "http://schema.org/Thing") | Name of the copyright holder. |
| PB - Core | [copyrightYear](http://schema.org/copyrightYear "http://schema.org/copyrightYear") | [Number](http://schema.org/Number "http://schema.org/Number") | Year that the book is/was published. |
| PB - Core | [inLanguage](http://schema.org/inLanguage "http://schema.org/inLanguage") | [Language](http://schema.org/Language "http://schema.org/Language") | The language of the book.|
| PB - Core | [publisher](http://schema.org/publisher "http://schema.org/publisher") | [Person](http://schema.org/Person "http://schema.org/Person") | The publisher of the book. |

## Chapter

Properties from: [Creative Work](https://schema.org/CreativeWork "https://schema.org/CreativeWork")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Metadata |[author](http://bib.schema.org/author "http://bib.schema.org/author")| [Person](http://schema.org/Person "http://schema.org/Person") | The author's id name. |
| PB - Metadata | [dateModified](http://bib.schema.org/dateModified "http://bib.schema.org/dateModified") | [Date](http://bib.schema.org/Date "http://bib.schema.org/Date") | The date on which the Chapter was most recently modified. |
| PB - Metadata | [datePublished](http://schema.org/datePublished "http://schema.org/datePublished") | [Date](http://bib.schema.org/Date "http://bib.schema.org/Date") | Date of first broadcast/publication. |
| PB - Metadata | [timeRequired](http://bib.schema.org/timeRequired "http://bib.schema.org/timeRequired") | [Duration](http://bib.schema.org/Duration "http://bib.schema.org/Duration") | The class learning time in minutes. |

Properties from: [Thing](https://schema.org/Thing "https://schema.org/Thing")

| **Used By** | **Property**| **Type**  | **Description** |
| ----------- | ----------- | --------- | --------------- |
| PB - Metadata | [name](https://schema.org/name "https://schema.org/name") | [Text ](https://schema.org/Text "https://schema.org/Text") | The title of the chapter. |
| PB - Metadata | [url](http://bib.schema.org/url "http://bib.schema.org/url") | [URL](http://bib.schema.org/URL "http://bib.schema.org/URL") | The URL of a forum/discussion about this page. |

