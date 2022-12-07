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
find -name '*.js' -type f -delete : Delete js files;
find . -type d -path './*' -print | wc -l : Count the number of dirs and sub-dirs in the cd;
ls -t | head  : Display the 10 newest files in the current directory;
sort | uniq -u : List of words as input and prints only words that appear exactly once;
grep root /etc/passwd  : Display lines containing the pattern “root” from a file;
grep -c bin /etc/passwd : Display the number of lines that contain the pattern “bin” in a file;
grep -A 3 root /etc/passwd  : Display lines containing the pattern “root” and 3 lines after them in a file;
grep -v bin /etc/passwd : Hide this word;
grep '^[A-Za-z]' /etc/ssh/sshd_config : Display all lines of a file starting with a letter;
tr Ac Ze : Replace all characters A and c from input to Z and e respectively;
tr -d cC : Remove all letters c and C from input;
rev : Reverse its input;
cut -d':' -f1,6 /etc/passwd | sort : Display all users and their home directories, sorted by users;
find . -empty -printf %f'\n' : Find all empty files and dirs in the cd and all sub-dirs;
find . -type f -name \*.gif -printf "%f\n" | LC_ALL=C sort -f | rev | cut -b 5- | rev : List all the files with a .gif extension in the cd and all sub-dirs;
cut -c 1 | paste -s -d '' : Decode acrostics that use the first letter of each line;
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev |\
 cut -d ' ' -f -1 | rev  : Biggest fan;
 