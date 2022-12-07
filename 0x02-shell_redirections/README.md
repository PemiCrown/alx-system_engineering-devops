echo Hello, World : To print "Hello,World";
echo  -e "\"(Ôo)'" : To display confuse smiley;
cat /etc/passwd : Display content of a file;
cat /etc/passwd /etc/hosts : Display contents of files;
cat /etc/passwd | tail: Display last 10 lines of a file;
cat /etc/passwd | head : Display first 10 lines of a file;
cat ./iacta | tail --lines=+3 | head -1  : Display third line of a file;
echo "Best School" >> "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)" : Create a file;
ls -la > ls_cwd_content : Write a script into a file;
cat ./iacta | tail --lines=1 >> iacta : Duplicate last line of a file;
find -name '*.js' -type f -delete : Delete js files;/n
find . -type d -path './*' -print | wc -l : Count the number of dirs and sub-dirs in the cd;/n
ls -t | head  : Display the 10 newest files in the current directory;/n