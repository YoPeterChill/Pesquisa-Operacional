# Como rodar o código

Para executar o código deste repositório, siga os passos abaixo:

1. Compile o código usando o `gcc`:
   ```bash
   gcc ./main.c -o "nome_do_exe"
   ```
   Substitua `nome_do_exe` pelo nome que deseja para o arquivo executável.

2. Execute o arquivo gerado com o desafio desejado:
   ```bash
   ./nome_do_exe ./desafio1.txt
   ```
   Certifique-se de substituir `desafio1.txt` pelo arquivo que contém os dados do problema que você quer resolver.

---

## Sobre o código

Este código foi desenvolvido para aprofundar o entendimento do Método Simplex, uma técnica amplamente utilizada para resolver problemas de programação linear.

### Funcionalidades
- O programa processa a função objetivo e as restrições fornecidas no arquivo de entrada.
- Realiza o processo completo do Método Simplex através do tableau.
- Exibe a solução ótima ao final do processamento.

O Simplex é essencial para resolver problemas que envolvem maximização ou minimização de recursos sob certas condições (restrições), e este código oferece uma implementação clara e educacional desse método.

### Arquivos de entrada
Os arquivos de entrada devem estar no formato especificado e conter:
1. A função objetivo.
2. As restrições do problema.

Certifique-se de revisar os exemplos incluídos neste repositório para entender melhor o formato exigido.

