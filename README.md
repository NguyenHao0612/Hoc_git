# Hoc_git

# *Lần đầu tạo git*

git init

git status

git add .

git commit -m "lan thu nhat"

git branch -M main

git remote add origin https://github.com/NguyenHao0612/Hoc_git.git

git push -u origin main
 
# *Lần thứ hai add nhưng file mới*

git status

git add .
 
git commit -m "lan thu hai"

git push

git pull // tải những thay đổi về lại máy

# *Lần thứ ba tạo nhánh cho git*
`Nếu để file mới trong thư mục chứa nhanh main (Hay vị trí mà push lên main) thì khi tạo nhánh mới và add thì nó sẽ add cả file cũ lẫn mới vào nhánh đó`

`Nếu tạo thư mục mới từ máy tính và tạo git mới từ đó thì khi add nó sẽ chỉ chứa file trong thư mục chứ ko chứa thư mục đó`

git clone <link git>     # nếu lỡ xoá file thì clone tất cả về máy

git status

git branch <tên nhánh>                    # tạo nhánh mới 

git checkout <tên nhánh>                  # chuyển sang nhánh vừa tạo

git add .                                  # add tất cả file 

git commit -m "<comment>"

git remote add origin <link git>

git push origin <tên nhánh>

git checkout -b <tên nhánh>              # vừa tạo nhánh vừa chuyển sang nhánh mới tạo

# *Lần thứ tư merge các nhánh vào nhanh main*

`Khi thực hiện thì file bên nhanh này sẽ được merge qua nhanh kia`

`Có được 2 nhánh với file giống hệt nhau`

# *Command line*
mkdir myproject     # make new folder
ls                  # it will list the files in the directory
git add -A          # this is git add -all 
git statur --short
git commit -a -m    # So let's commit it directly
