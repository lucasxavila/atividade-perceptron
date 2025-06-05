# Atividade - Inteligência Artificial: Perceptron e seus usos cotidianos

### Exercício 1 - Prática de Inteligência Artificial: Usando o Perceptron para Decidir se Devemos Levar Guarda-Chuva

### Contexto da Atividade 1

Imagine uma situação cotidiana onde você precisa decidir se deve ou não levar um guarda-chuva ao sair de casa. Você toma essa decisão com base em dois fatores simples:

- **Nuvens no céu** (0 - poucas ou nenhuma nuvem; 1 - muitas nuvens)
- **Previsão de chuva no app do celular** (0 - não há previsão; 1 - há previsão)

O Perceptron será treinado para ajudar nessa decisão, com base nessas duas entradas simples.

### Tabela de Valores 1 (Dataset)

| Nuvens no céu | Previsão de chuva | Levar Guarda-chuva? |
|--------------|--------------------|---------------------|
| 0            | 0                  | 0 (Não)             |
| 0            | 1                  | 1 (Sim)             |
| 1            | 0                  | 1 (Sim)             |
| 1            | 1                  | 1 (Sim)             |

### Exercício 2 - Prática de Inteligência Artificial: Decisão de Ir ao Parque

Agora, vamos usar o Perceptron para decidir se devemos ir ao parque ou não, considerando três fatores:

- **Tempo ensolarado** (0 - Não; 1 - Sim)
- **Dia da semana** (0 - dia útil; 1 - final de semana)
- **Parque lotado** (0 - Não; 1 - Sim)

### Tabela de Valores 2 (Dataset)

| Ensolarado | Final de Semana | Parque Lotado | Ir ao Parque? |
|------------|-----------------|---------------|---------------|
| 0          | 0               | 0             | 0 (Não)       |
| 0          | 1               | 0             | 1 (Sim)       |
| 1          | 0               | 0             | 1 (Sim)       |
| 1          | 1               | 0             | 1 (Sim)       |
| 0          | 0               | 1             | 0 (Não)       |
| 0          | 1               | 1             | 0 (Não)       |
| 1          | 0               | 1             | 0 (Não)       |
| 1          | 1               | 1             | 0 (Não)       |

### Exercício 3 - Prática de Inteligência Artificial: Decisão sobre Comer Fora ou Cozinhar em Casa

Neste exemplo, você deve decidir se vai comer fora ou cozinhar em casa considerando quatro fatores:

- **Cansado do trabalho** (0 - Não; 1 - Sim)
- **Dispõe de ingredientes em casa** (0 - Não; 1 - Sim)
- **Restaurante próximo aberto** (0 - Não; 1 - Sim)
- **Dia de pagamento recente** (0 - Não; 1 - Sim)

### Tabela de Valores (Dataset)

| Cansado | Ingredientes em casa | Restaurante aberto | Pagamento recente | Comer fora? |
|---------|----------------------|--------------------|-------------------|-------------|
| 0       | 1                    | 1                  | 1                 | 0 (Não)     |
| 1       | 0                    | 1                  | 1                 | 1 (Sim)     |
| 1       | 1                    | 0                  | 1                 | 0 (Não)     |
| 0       | 0                    | 1                  | 0                 | 1 (Sim)     |
| 1       | 1                    | 1                  | 1                 | 1 (Sim)     |
| 0       | 1                    | 0                  | 0                 | 0 (Não)     |
| 1       | 0                    | 0                  | 1                 | 0 (Não)     |
| 0       | 0                    | 0                  | 1                 | 0 (Não)     |

### Síntese do que foi feito

Neste exercício prático eu:

- Apliquei o Perceptron, um modelo básico de rede neural artificial, para resolver problemas cotidianos;
- Treinei e testei o perceptron com diferentes variáveis de entrada;
- Analisei como diferentes fatores influenciam decisões cotidianas.
