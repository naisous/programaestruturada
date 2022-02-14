#include <stdio.h> 34

#include <string.h>

36 37

typedef struct aluno { char nome[45];

38 39

40

int matricula; float nota;

char sexo;

35

41 Aluno;

42

43 typedef struct professor { 44

char nome[45]; 45 char curso[4][60];

46 47

Professor;[

48 typedef struct escola { 49

char nome[45]; 50 Professor professores[10];

51 Aluno alunos [10];

52 Escola; 53

54 int main()

55 - {

56

57

Aluno alunos[2];

58 strcpy(alunos[0].nome, "Fulana"); alunos[0].matricula 1020;

59

60

61

62

63

alunos[0].nota = 9.5;

alunos[0].sexo = 'F';

strcpy(alunos [1].nome, "Beltrano");

alunos[1].matricula = 1020;
