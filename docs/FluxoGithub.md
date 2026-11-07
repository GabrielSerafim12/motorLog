# Fluxo GitHub

- `main`: versão estável e protegida.
- `develop`: integração do grupo.
- `feature/nome-da-tarefa`: trabalho individual.
- `fix/nome-da-correcao`: correção pontual.

## Rotina
1. Atualizar a cópia local a partir de `develop`.
2. Criar branch feature a partir da develop atualizada.
3. Implementar apenas o escopo atribuído.
4. Compilar e testar.
5. Fazer commits objetivos e Push.
6. Abrir Pull Request da feature para develop.
7. Corrigir observações e aguardar aprovação.
8. Integrador faz merge.
9. Quando estável, integrador abre PR de develop para main.

Nunca faça commit direto em main/develop, não use Force Push e não altere estruturas compartilhadas sem combinar.
