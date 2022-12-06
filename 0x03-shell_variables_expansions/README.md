alias ls="rm *" : To create alias;
echo hello MyUser : To print user;
export PATH="$PATH:/action" : To add /action to PATH;
echo $PATH | tr ":" "\n" | wc -l :  To print dirs in PATH;
printenv : To print environment/global variables;
set : To print local global  variables & its functions;
BEST="School" : To create a local variable;
export BEST="School" : To create a global variable;
echo $((128+$TRUEKNOWLEDGE)) : For addition of values;
echo $(($POWER/$DIVIDE)) : Divide and rule values;
echo $(($BREATH**$LOVE)) : Display BREATH to power LOVE;
echo $((2#$BINARY)): To covert base 2 to 10;
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" : To combine;
printf "%.2f\n" $NUM : To print a number with two decimal places;

