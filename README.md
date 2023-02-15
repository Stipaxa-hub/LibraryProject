# Description of project
The local library wants to switch to digital bookkeeping. I implemented a web application for them. Librarians are able to register readers, give them
books and release the books (after the reader returns book back to the library).
# Functional 
1) Pages for adding, changing, and deleting a person.
2) Pages for adding, modifying, and deleting books
3) Page with a list of all the people (clickable people - when you click
   Goes to the person's page).
4) Page with a list of all books (books are clickable - click to jump to
   goes to book page).
5) The person's page, which shows his field values and the list of books he
      took. If the person has not taken any books, instead of the list there should be the text "Person
      has not picked up any books yet".
6) The page of the book, which shows the field values of that book of this book and the name of the person who took the book. If this book was not taken by anyone, there should be the text "This
   book is free."
7) On the book page, if the book is taken by a person, there should be a button next to the person's name
   "Release Book." This button is pressed by the librarian when the reader
   returns the book back to the library. Once this button is pressed, the book again
   becomes free and disappears from the person's book list.
8) On the book page, if the book is free, there is a drop-down list 
      with all the people and a "Assign Book" button. This button is pressed by the librarian
      when the reader wants to take that book home. After pressing this button, the book
      belongs to the selected person and appears in their list of
      books.
9) All fields were validated - with @Valid and Spring Validator if
   required.
# Technologies
<ul>
    <li>Java</li>
<li>Spring MVC</li>
<li>PostgreSQL</li>
<li>JDBC template</li>
<li>HTML</li>
<li>CSS</li>
</ul>

 
