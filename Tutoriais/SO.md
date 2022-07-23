<p align='center'>
<a href="https://github.com/felipenlunkes/osdevbr"><img height="250" src="https://github.com/felipenlunkes/osdevbr/blob/main/img/header.gif"></a>&nbsp;&nbsp;
</p>

> Atenção! O conteúdo está em constante atualização!

# O que é um sistema operacional?

Um sistema operacional (SO) nada mais é que um conjunto de programas responsáveis por gerenciar os componentes do computador, fornecendo acesso controlado dos programas ao processador, memória, discos e outros dispositivos, sendo uma ponte que possibilita a comunicação dos programas que serão executados sobre ele e o dispositivo do usuário. O sistema operacional também é o responsável por reservar memória, carregar programas do usuário a partir do disco e servir as solicitações destes programas através de uma interface padronizada e documentada (API), além de garantir segurança e isolamento entre eles[^1].

Um SO é dividido, geralmente, em carregador de inicialização, kernel, bibliotecas e utilitários do usuário. Cada um destes componentes realizam uma função bem definida. O carregador de inicialização, ou boot loader, é o primeiro componente do sistema operacional carregado e é responsável por procurar no disco o segundo componente, o kernel. O kernel é o núcleo do sistema operacional, como será visto adiante. Após o carregamento e inicialização do kernel, o mesmo carrega e executa os utilitários do usuário, que fazem requisições ao kernel para acessar dispositivos e para carregar bibliotecas que permitem o correto funcionamento.

[^1]: https://en.wikipedia.org/wiki/Operating_system