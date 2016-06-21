void boolean isWhite(String cell){
int a = convertToAscii(cell);
if(a %2 == 0){
    return true;
} else {
   return false;
}
}

void int convertToAscii(String cell) {
int tong = 0 ;
for (int i=0;i<cell.lenght;i++){
char character = name.charAt(i);
int ascii = (int) character;
tong = tong + ascii;
}
return tong;
}
