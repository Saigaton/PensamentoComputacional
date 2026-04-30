**Estudante:** Davi Pereira dos Santos  
**RGM:** 32075821

## Descrição do Problema
No modelo de trabalho *home office*, a imersão nas tarefas e o excesso de reuniões dificultam a realização de pausas essenciais para o bem-estar físico.

---

## Análise do Pensamento Computacional

### 1. Decomposição
- Dificuldade de interromper o fluxo de trabalho para movimentação física.
- Acúmulo de tarefas geradas pelo alto volume de reuniões diárias.

### 2. Identificação de Padrões
- Procrastinação da pausa devido a compromissos agendados na hora seguinte.
- Substituição do descanso físico pelo uso passivo do celular.

### 3. Abstração
- Foco na **frequência e duração** das pausas, independentemente do tipo específico de exercício ou da complexidade da tarefa em mãos.

---

## Algoritmo da Solução

O algoritmo abaixo utiliza a lógica de *Time Blocking* e *Pomodoro* para garantir a hidratação e o movimento:

```pseudo
Iniciar jornada de trabalho;

Enquanto (Jornada de Trabalho <= 8 horas)
    Configurar Timer (50 minutos);
    
    Se (Timer == 0) então
        Levantar-se imediatamente;
        Beber 200ml de água;
        Executar 2 minutos de alongamento;
    Fim Se

    Se (Tem Reunião Agendada) então
        Participar da chamada de pé;
    Fim Se
Fim Enquanto

Encerrar jornada de trabalho;
```
