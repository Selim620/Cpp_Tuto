# Cpp_Tuto

# Exemple Permutation
void permuter (int *a,int *b)  // a est un pointeur (represente une adresse dans le RAM --> c'est un entier)
{int ox;
ox=*a; //ox recoit la valeur stoké dans l'@ a
*a=*b;
*b=ox;}

int main(){
permuter (&x,&y); //&x donne l'adresse de x


# En C++
void permuter (int& a ,int& b) la fonction va utiliser une zone memoire deja existante (x/y)
{int ox;
ox=a;
a=b;
b=ox;}
permuter (x,y);
