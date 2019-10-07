# Code review

## O que é

Code review é uma prática de revisão de código muito utilizada em projetos open-source ou em projetos empresariais. Ela consiste em os membros do time revisarem o código de um colega antes de integrá-lo à base de código.

## O que é um Pull Request (PR)

Pull request é quando você envia uma sugestão de melhoria para o repositório.

## Passos na criação de um PR

1. Ao criar um PR certifique-se se ele segue a seguinte descrição:
```
* Funcionalidade: <Funcionalidade que você está adicionando>
* Card: <Link do card no Trello que corresponde a essa tarefa>
* Descrição: <curta descrição do que foi feito>
```

2. Verificar você mesmo o código em busca de falhas de padronização e erros
3. GIT
   - Todos os commits são pequenos e divididos logicamente
   - Os commits têm mensagens curtas e descritivas
   - O commit está livre de arquivos de IDE/editor e afins

## Checklist

Itens que você deve checar antes de abrir o PR ou ao revisar o PR de outro membro

### Aspectos gerais

1. O código está funcionando?
2. O layout ou especificação está de acordo com o definido?
3. Você testou o que desenvolveu?
4. Você verificou se não quebrou outra parte da aplicação?
5. O seu código está seguindo os padrões de organização do projeto?
6. O código está repetitivo?
7. O nome de variáveis, funções, arquivos, classes, métodos... está de acordo com os padrões de projeto?
8. Você está separando as responsabilidades do código de maneira adequada?
9. A branch do PR está sincronizada com a de destino e livre de conflitos?

## Estilo de Código

1. Certifique-se que você está evitando valores "hardcoded" e está separando os valores em arquivos para constantes, strings...
2. Você está evitando ternários e blocos muito longos de `if/else`?
3. Adiciona comentários quando necessário, descrevendo o porquê?

## Limpeza

1. Seu código está livre de itens para depuração, como logs desnecessários?
2. O código está formatado de acordo com as diretrizes do projeto?

## Outros

1. Segurança
2. Usabilidade

