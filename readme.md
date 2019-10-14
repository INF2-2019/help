# O básico

Aqui são introduzidos alguns conceitos e práticas recomendadas e/ou necessárias para manter a organização do projeto.  
Perguntas recorrentes serão adicionadas como outros arquivos `.MD` aka MarkDown neste repositório.

## Organização das `branch`es

Isso pode vir a ser modificado, porém prosseguiremos assim até segunda ordem.

### Branches principais

Teremos duas branches principais:

- `dev`
- `release`

#### `dev`

Na branch dev, serão adicionadas periodicamente as modificações e funcionalidades aprovadas pelos líderes. Essa branch deve servir de espelho para a criação de outras branches.

#### `release`

Na branch release, serão adicionados todas as modificações presentes na dev após serem testadas. Nessa branch, estarão os lançamentos que serão enviados para os professores e gerência testarem. _Somente os gerentes e quem for autorizado diretamente por eles poderá modificar essa branch de qualquer forma_.

### Branches de funcionalidade

Toda funcionalidade que você estiver desenvolvendo deve estar centralizada em uma única branch dedicada a essa funcionalidade, seguindo o padrão `feature/{funcionalidade}`. Por exemplo, digamos que você esteja trabalhando na funcionalidade de login, sua branch de trabalho deve se chamar `feature/login`.

Toda correção em que você estiver trabalhando deve também estar centralizada em uma única branch. No caso o padrão é `fix/{correção}`.

## Code Review

Code Review, em brasiliense, revisão de código, é uma prática importante para manter a qualidade do código e a padronização do projeto. Ela consiste na revisão do seu código por membros da equipe antes de ele ser mesclado com o progresso atual do projeto. Isso evita conflitos e garante um código mais homogêneo e menos falho.

_Verifique o [CodeReview.md](CodeReview.md) no repositório._

## Links úteis

Tutorial de Git básico: [aqui](https://rogerdudler.github.io/git-guide/index.pt_BR.html)

Tutorial de Git e GitHub da RocketSeat: [aqui](https://youtu.be/2alg7MQ6_sI)

Git Kraken GUI pra quem não é fã do terminal ou prefere interface gráfica: [aqui](https://www.gitkraken.com/)

Pull Request Inútil
