#### CodeRary Django-Online-Library-Management-System

Reqiremenths - python , Django 3.0 or above (SQlite is also recommended)
first Clone the repository or download zip
run the commands below -
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

#### key Features =>

### 3 types of Users/Panels -

                   1) Admin
                   2) Publisher
                   3) Librarian

### Book Cover , Author , published year, Publisher ,Description , BOOK PDF View / Upload / Download functionalities

### Group Chats

simultaneous chatting functionality with date , time stamps , type of user , username.

### Password Hashing

stay stafe with password hashing , Even Admin can't take a peek at your password.

### Delete Book Feature

only publisher/uploader of the book is allowed to request deletion of published books

### Delete Book Request section specific to librarians & admin

### search Book by ID , sorting available

Every book has unique Id , sort in ascending / descending order by id, author.

### manage Users functions specific to Admins/Superuser

update user data like name,type & creating new user (superuser can be created with help of terminal commands as well as by admin).

By default new user is registered as publisher unless specified by admin.
used SQlite3 for db storage.

feel free to contact if facing any issues

### upcoming updates -

                  pagination fix , individual section update instead of entire book deletion , better UI/UX.
