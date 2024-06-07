# Dunder Mifflin

## Contribuindo com o projeto

### Gitflow

#### Nomenclaturas de branchs

Ao criar uma branch com suas mudanças, atente-se em utilizar o modelo sugerido abaixo, seguindo a convenção de prefixos.

> Sempre certifique-se que sua branch esteja atualizada com a `main`

O modelo para o nome da branch consiste em indicar o tipo da mudança como prefixo e então um nome curto separado por uma barra: `<tipo da mudanca>/nome-breve-para-mudanca`.

São esses os prefixos para as mudanças:

- `config/` Para mudanças relacionadas à configurações
- `feature/` Para novas funcionalidades
- `fix/` Para correções de problemas não críticos
- `hotfix/` Para problemas críticos em produção
- `docs/` Para mudanças relacionadas à documentação

#### Fluxo de trabalho

Após concluir o desenvolvimento de uma atividade, as mudanças devem seguir o seguinte fluxo:

- Pull Requests devem ser enviados para a branch `staging`
- Após o sinal verde da esteira de Qualidade, a branch `staging` será mesclada na branch `next/release`
- Uma vez que um número rasoável de funciondalides estejam prontas para publicação em Produção, será gerado um release e as mudanças serão mescladas na `main`
