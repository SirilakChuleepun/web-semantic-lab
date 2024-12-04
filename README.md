# web-semantic-lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development
## รายละเอียด
- การใช้ Semantic HTML
- Form Validation
- ARIA Labels

# 1 Start
- git clone <your-repo-url>
- แก้ไข README.md 
- git add README.md 
- git commit -m "Create Project Start"

# 2 Create branch Development
- git checkout -b development
- สร้างไฟล์ index and contact
- git commit -m "Create Simple Start Project"
- git push

# 3 Create branch feature/homepage
- git checkout -b feature/homepage
- git add index.html
- git add contact.html
- git commit -m "Create Simple Start Project"
- git add index.html
- git commit -m "Add header and nav in Homepage"
- git add index.html
- git commit -m "Add main and article in Homepage"
- git add index.html
- git commit -m "Add aside and footer in Homepage"

# 3 Create branch feature/contact
- git checkout -b feature/contact
- git add contact.html
- git commit -m "Create simple start in contactpage"
- git add contact.html
- git commit -m "Add form in contactpage"
- git add contact.html
- git commit -m "Add validation in form"
- git add contact.html
- git commit -m "Add ARIA labels in form"
- git add contact.html
- git commit -m "Add ARIA landmarks in nav"

# END
- git checkout development
- git merge feature/homepage
- git merge feature/contact
- git push origin development












