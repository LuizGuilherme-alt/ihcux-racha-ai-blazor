# ihcux-racha-ai-blazor

Nome do grupo: Caua Furst, Joao Vitor Pedrosa, Luiz Guilherme, Silas Caleb

## Implementação Blazor

O projeto foi desenvolvido utilizando Blazor e Bootstrap para criar uma interface moderna, responsiva e organizada.

A hierarquia visual construída inicialmente no Miro foi transformada em componentes reutilizáveis no Blazor, separando responsabilidades entre:

- Models → representação dos dados
- Components → interface reutilizável dos grupos
- Pages → estrutura principal da dashboard

Os cards superiores receberam cores diferentes para melhorar a percepção visual do usuário:
- Verde → valores a receber
- Vermelho → valores a pagar
- Azul → saldo geral

Também foi utilizado o sistema de Grid do Bootstrap para manter a responsividade em diferentes tamanhos de tela.

---

## Dificuldade Técnica

O maior desafio foi componentizar o GrupoCard.razor, principalmente no envio de parâmetros entre componentes e na lógica de alteração dinâmica das cores utilizando condições com Razor.

Também foi necessário entender como reutilizar o componente várias vezes na Dashboard sem duplicar código.
