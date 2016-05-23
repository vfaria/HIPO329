# MACO329
========


EP2 - Terceiro Exercício-Programa
========

#### Alunos ####

NUSP  | Nome
------------- | -------------
4898948 | André Meneghelli Vale
5173890 | Evandro Fernandes Giovanini
7289482 | Gilmar Cintra da Silva
8515919 | Victor Oreliana Fernandes Faria

Comentários
========

Foram implementados três circuitos auxiliares e um principal com o funcionamento do computador. Para iniciar o funcionamento basta carregar na RAM o arquivo de teste em anexo ou escrever o seu próprio programa. As instruções disponíveis são:

 * **LDA**: Carrega dado do endereço AB no acumulador (0x0B)
 * **STA**: Carrega acumulador no endereço AB (0x0C)
 * **NOP**: Sem operação (0x32)
 * **JMP**: Salto não-condicional para o endereço AB (0x33)
 * **STP**: Fim da execução (0x46)

#### PC ####

Circuito implementado com flip-flops com capacidade de armazenar 8 bits que serão utilizados para apontar edereços da RAM.

#### CTRL ####

Circuito que controla o fluxo de funcionamento do programa, possui um clock interno com frequência diferente do clock externo para evitar problemas com a instrução *STA*.

#### CMP ####

Circuito utilizado para facilitar a comparação das instruções, além de dois pinos de acesso de 8 bits que serão comparados também recebe um bit para habilitar ou negar a saída do resultado.
 
