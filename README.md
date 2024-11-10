get_next_line é uma implementação em C que permite ler uma linha de texto de um arquivo de forma incremental, ou seja, uma linha por vez.

A função lê o arquivo em blocos de tamanho fixo (definido neste projecto por um buffer de 5). Ela acumula os dados até que encontre um caractere de nova linha (\n) ou o final do arquivo (EOF).
