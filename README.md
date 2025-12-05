# Certifique-se que está na pasta do projeto
cd hello-world

# Verifique o que tem no README
cat README.md

# Crie o arquivo hello.c CORRETAMENTE
echo '#include <stdio.h>

int main() {
    printf("Hello World!\\n");
    return 0;
}' > hello.c

# Corrija o README.md (conteúdo mais limpo)
echo '# Hello World

Este repositório contém um programa simples em C que imprime "Hello World!".

## Como compilar e executar:

```bash
gcc hello.c -o hello
./hello
```' > README.md
git add .
git commit -m "Correção: arquivo hello.c e README"
git push origin main
