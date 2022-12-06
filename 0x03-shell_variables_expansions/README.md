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
printf '%x\n' $DECIMAL : Convert from base 10 to base 16;
tr 'A-Za-z' 'N-ZA-Mn-za-m':  Encode and decode text using the rot13 encryption;
paste -d, - - | cut -d, -f1 :  Print every other line from the input;
printf "%o\n" $(( $((5#$(echo $WATER | tr water 01234))) + $((5#$(echo $STIR | tr stir. 01234))) )) | tr 01234567 bestchol : Add two numbers and print.

