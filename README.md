### Hi there 👋
### Mi nombre es Octavio Pino
 
 #### Soy un estudiante de 4°2da Avionica  _*aprendiendo*_:
 1. c
 2. java 
 3. python
 

 
<!--
**OctaPin/Octapin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
#include <stdio.h>

int main(void){
    int dinero=0;

    printf("Ingrese su monto: ");
    scanf("%d",&dinero);
    printf("su monto sera de %d!\n",dinero);  

    if(dinero<20) {       
        printf("el monto es insuficiente para retirar");
        return 0;
    }
     if(dinero>5000) {         
        printf("el monto es demasiado para retirar");
        return 0;
    }
    return 0;    
}
