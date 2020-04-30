# Belajar GIT
Ini adalah deskripsi dari GIT


## Command Dasar
adapun beberapa command dasar pada `git` adalah sebagai berikut :

- #### untuk memasukkan global config pada git local
```bash
$ git config --global user.name "your github name"
$ git config --global user.email "your github email"
```


- #### untuk mengcloning repository
```bash
$ git clone your_url_repo
```


- #### menambahkan sebuah file ke staging

```bash
$ git add your_file_name
```
untuk menambahkan file yg `untracked` ke status staging


- #### menambahkan semua file ke staging
```bash
$ git add .
```
untuk menambahkan semua file yg `untracked` ke status staging


- #### commit from staging
```bash
$ git commit -m "message here"
```
untuk melakukan commit file yang berada di staging


- #### untuk melihat branch
```bash
$ git branch
```
untuk melihat branch yang sudah di buat


- #### untuk melihat merged branch
```bash
$ git branch --merged
```
untuk melihat branch yang sudah di merged


- #### untuk melihat remote url
```bash
$ git remote -v
```
untuk melihat remote url yang telah dibuat


- #### untuk menambah remote url
```bash
$ git remote add remote_name remote_url
```
untuk menambah remote url 


- #### untuk mengubah remote url
```bash
$ git remote set-url remote_name new_remote_url
```
untuk mengubah remote_url


- #### untuk melakukan push ke repository
```bash
$ git push your_remote_name your_branch 
```
untuk melakukan push ke repository. 


- #### untuk melakukan push ke repo dengan upstream
```bash
$ git push -u origin master
```
untuk melakukan push juga, cuma bedanya ada `-u` sebagai `upstream`. Jadi, nanti selanjutnya bisa dilakukan `git push`, maka secara otomatis akan ngepush data ke origin master


- #### untuk liat graph perubahan commit pada git
```bash
$ git log --all --decorate --oneline --graph
```
untuk melihat graph commit pada repo lokal






