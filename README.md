# App Layout.
 
*Sobre o Projeto*
Este é um aplicativo simples desenvolvido em Flutter como parte da Atividade do Módulo 2 do Curso Talento Tech. O objetivo do projeto é demonstrar a criação de layouts utilizando widgets básicos do Flutter, aplicando conceitos de Material Design e explorando a personalização de temas, estruturas de colunas e linhas, e containers com estilos variados.

*Funcionalidades*
Título Personalizado: Mostra o nome do aplicativo na AppBar.
Layouts Hierárquicos:
Layout superior com texto centralizado.
Layout central com três colunas, onde a coluna do meio contém um container estilizado com bordas arredondadas, sombra e cor de fundo.
Layout inferior com texto centralizado.
Botão Flutuante: Um botão no canto inferior direito com o ícone de adicionar (sem funcionalidade implementada no momento).
Tema Personalizado: A paleta de cores foi gerada com base na cor semente #75AB9F.

*Estrutura do Código*
Main Function: Inicializa o aplicativo.
Stateless Widget (App): Define o tema e a tela inicial.
Stateful Widget (HomePage): Responsável por renderizar o layout principal, que utiliza:
AppBar: Mostra o título.
Scaffold: Estrutura principal da tela com AppBar, body e FloatingActionButton.
Column e Row: Organizam o layout em diferentes seções.
Container: Usado para estilizar partes do layout com bordas, sombras e cores.

*Estrutura do Layout*
App
└── MaterialApp
    └── HomePage
        ├── AppBar
        └── Scaffold
            ├── Body
            │   └── Column
            │       ├── Container (Layout Superior)
            │       ├── Row (Layout Central)
            │       │   ├── Container (Esquerda)
            │       │   ├── Container (Centro com estilo)
            │       │   └── Container (Direita)
            │       └── Container (Layout Inferior)
            └── FloatingActionButton
