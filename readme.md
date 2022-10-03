# Mita in Yoruba language means counter

Application responsible in counting

## You can count words, letter, signs from the following files

- PDF
- EXCEL
- TXT

## Rules

### There are few types of users in the application
* Guest user - no login required, can count from text files only 
* Registered user - login required, can count from text, pdf
* Premium user - needs to buy subscription, can count from text, pdf, excel
* Administrator - administrates an application

### Potential services
User management service:
- User will register here,
- User will be able to change its data, like nickname,email,password
- Panel will display information about the user status

FileUploader
- File will remain for 15minutes in storage, then it will be deleted

AccountPlan
- There is one plan, premium that can be bough for 10$ for 1month

File extractor
- Is able to extract the file contents from storage

Counter
- Uses file extractor to extract the content from uploaded file and based
on the response counts words, letters

WebApp that will show the frontend

### Usage scenario
As a guest user I enter mita.local
I saw the front page with a button to pick a txt file from the storage
File is imported to the storage
Then the counter picks the file from the storage, extracts its data, and counts
words or letters. Word is qualified as a string that contains at least 2 characters without
a whitespace in between.

