
### :computer: Tecnologias usadas
Projeto foi desenvolvido com as seguintes tecnologias:

* C

### 🎓 Projeto
"Filósofos" é um projeto desenvolvido para a disciplina Programação Paralela e Distribuída no curso Sistemas de Informação da UFSC.


### 📝 Sobre

O problema “Jantar dos Filósofos” consiste em 5 (cinco) filósofos que estão sentados ao redor de uma mesa circular para o jantar. Cada filósofo possui 1 (um) prato para comer
macarrão. Além disso, eles dispõem de garfos e cada um deles precisa de 2 (dois) garfos para comer. Entre cada par de pratos, existe apenas 1 garfo. Os garfos precisam ser
compartilhados de forma sincronizada.

Algumas das regras são:
- os filósofos comem e pensam, alternadamente;
- não é permitido deadlocks;
- nenhum filósofo deve entrar em estado de starvation esperando por um garfo;
- quando comem, pegam apenas 1 garfo por vez;
- se conseguir pegar os 2 garfos, come por algunsinstantes e depois solta os garfos;
- deve ser possível que 2 filósofos comam ao mesmo tempo.
