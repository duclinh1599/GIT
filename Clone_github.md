## Cách clone trên github về
- Khai báo thông tin user_name với email:
    
        #git config -global user.name 'duclinh1599' (lưu ý name là tên trên github)
        
        #git config -global user.email 'duclinh1599@gmail.com'
- Dùng git clone để clone repo từ github về.
- Sau khi clone về ta sẽ dung các bước sau để đẩy lại những gi đã sửa lên gibhub.

        #git add . (đẩy toàn bộ những chỉnh sửa lên staging).
        #git commit -m 'descrition' 
        #git push