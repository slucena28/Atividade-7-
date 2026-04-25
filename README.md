# Atividade-7-Dividir o código SASS em múltiplos arquivos parciais, organizados por função ou componente:

_base.scss (estilos base como body, tipografia, reset)

_variaveis.scss (cores, espaçamentos, fontes)

_mixins.scss (estilos reutilizáveis)

_layout.scss (estrutura geral da página)

_componentes.scss (componentes como botões, cards, menus, etc.)

estilos.scss (arquivo principal que importa os demais com @use)

2. Uso de Variáveis e Mixins:

Utilizar variáveis SASS para cores, espaçamentos, fontes e tamanhos.

Criar pelo menos 2 mixins reutilizáveis (ex: espaçamentos padrão, botão básico).

Utilizar operadores para calcular tamanhos proporcionais (ex: margin-bottom: calc($espacamento / 2)).

3. Aninhamento e Organização:

Aplicar aninhamento de seletores com moderação, seguindo boas práticas.

Organizar os estilos por seções e componentes usando a metodologia BEM para nomeação das classes (.bloco__elemento--modificador).

4. Compilação e Estrutura:

Configurar o ambiente de desenvolvimento:

Compilar via linha de comando com Node.js;

O código final deve gerar um arquivo CSS final compilado.

O código SASS deve estar na pasta scss/, separado do css/ compilado.
