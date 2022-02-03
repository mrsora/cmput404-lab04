# Answers for lab
1. https://github.com/mrsora/cmput404-lab04
2. The install worked successfully! Congratulations!
3. Page not found (404); Hello, world. You're at the polls index.
4. Migrations are to update the database schema, creating new or modifying existing tables.
5. Site administration: AUTHENTICATION AND AUTHORIZATION, POLLS. Must create the model class in `models.py`, makemigrations, migrate, register in `admin.py`.
6.  /polls/38/
    >You're looking at question 38.

    /polls/38/results
    >You're looking at the results of question 38.

    /polls/38/vote
    >You're voting on question 38.

    /polls/asdfasdfas
    >Page not found (404)

    `<int:question_id>` -> `<str:question_id>`

7. It's a bad idea, eg. if the filename changes due to refactoring.
8. Can write new views easier. Less boilerplate code. Should use it when you can use it reduce repeated code.