# Belajar GIT
Ini adalah deskripsi dari GIT


## Command Dasar
adapun beberapa command dasar pada `git` adalah sebagai berikut :

```bash
git config --global user.name "your github name"
git config --global user.email "your github email"
```
untuk memasukkan global config pada git local

```bash
$ git clone your_url_repo
```
untuk mengcloning repository

```bash
$ git add your_file_name
```
untuk menambahkan file yg `untracked` ke status staging

```bash
$ git add .
```
untuk menambahkan semua file yg `untracked` ke status staging

```bash
$ git commit -m "message here"
```
untuk melakukan commit file yang berada di staging

```bash
$ git push your_url_name your_branch 
```
untuk melakukan push ke repository pada url `your_url_name` , dengan branch `your_branch`.


```bash
$ git push -u origin master
```
untuk melakukan push juga, cuma bedanya ada `-u` sebagai `upstream`. Jadi, nanti selanjutnya bisa dilakukan `git push`, maka secara otomatis akan ngepush data ke origin master


```bash
$ alias graph="git log --all --decorate --oneline --graph"
$ graph
```
Untuk liat graph perubahan commit pada git


```bash
$ git branch
```
untuk melihat branch yang sudah di buat


```bash
$ git branch --merged
```
untuk melihat branch yang sudah di merged
