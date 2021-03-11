# Рубежныйй контроль
1) 3мя способами:
```
cd
cd ..
cd home/user
сd ~/
```
2) Это просто
```
 grep -v 
 ```
3)
```
mkdir test
cd test
vim test.txt
```
4)
```
tar -cvf test ./test
```
5)
```
grep -w 'aaa&bbb' ./
```
6)
```
ls -d
```
7)
```
find . -type f -exec ls -s {} ; | sort -n | head -10
```
Выводит  10 самых больших
# Part 2
1)
```
git init
git pull
git clone
```
2)
Выведет ошибку, как я считаю, но если и пройдет то последнее изменение файла
3) master to patch1
4) master to patch1
5) Тот у кого быстрее интернет запушит а второй получит ошибку
6) Как выглядит? Вот так:
```
<<<<<<< HEAD
// This is a comment!!!
=======
/*Jast a comment*/
>>>>>>> fa367e6048425646c8175b47b59fa4bcf693d4fd
```
