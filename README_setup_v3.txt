Comic Library v3 - Setup

Files:
- index.html       Public comic library
- admin.html       Owner-only admin page
- books.csv        Book catalog editable in Excel
- images/          Sample cover images
- supabase_requests_setup.sql

What changed:
- Public users can submit requests from the popup on each comic
- Requests are saved into your Supabase table
- You can log in on admin.html and view / mark requests as Done

Important Supabase steps:
1. In Supabase SQL Editor, run supabase_requests_setup.sql
2. In Supabase Authentication, create an owner user:
   - Go to Authentication -> Users
   - Add user
   - Enter your owner email and a password
3. Upload these files to your GitHub repo root:
   - index.html
   - admin.html
   - books.csv
   - images/

How owner login works:
- Open https://artyom-r.github.io/books/admin.html
- Log in with the email/password you created in Supabase Authentication

How public requests work:
- Visitor opens a book
- Fills name/contact/message
- Clicks Send request
- Request is saved to Supabase

How to update books:
- Edit books.csv in Excel
- Save as CSV
- Upload the new books.csv to GitHub
