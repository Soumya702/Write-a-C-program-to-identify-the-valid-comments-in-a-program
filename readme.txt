Install Process

sudo apt get install flex
sudo apt get update


Running Flex
vi file_name.lex
press esc
press shift+:
write wq 
press enter
lex file_name.lex
cc lex.yy.c
./a.out
