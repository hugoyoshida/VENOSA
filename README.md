Projeto de Cor Dinâmica Unity3D e Servidor Web

1. Descrição
    Este projeto consiste em duas partes principais: um servidor web e um projeto Unity3D. O servidor web gera uma cor aleatória em formato hexadecimal, que é enviada para o projeto Unity. O projeto Unity, por sua vez, acessa o servidor a cada segundo para obter uma nova cor e aplica esta cor a um objeto (cubo) na cena.


2. Configuração e Execução
    2.1. Servidor Web
        2.1.1. Requisitos
            - Node.js instalado no seu sistema.

        2.1.2. Instruções de Configuração
            - Navegue até a pasta "Servidor" do projeto.
            - Execute "npm install" para instalar todas as dependências necessárias (se houver).

        2.1.3. Executando o Servidor
            - Dentro da pasta "Servidor", execute o comando "node server.js".
            - O servidor iniciará e ficará ouvindo na porta especificada (por padrão, 3000).


    2.2. Projeto Unity3D
        2.2.1. Requisitos
            - Unity3D instalado no seu sistema.

        2.2.2. Configuração do Projeto
            - Abra o Unity Hub.
            - Clique em "Adicionar" e selecione a pasta "Unity3D" deste projeto.
            - Clique no projeto adicionado para abri-lo no Unity.

        2.2.3. Executando o Projeto Unity
            - No Unity, abra a cena que contém o cubo.
            - Pressione o botão "Play" para iniciar a simulação.
            - O cubo na cena começará a mudar de cor com base na resposta do servidor web.

3. Notas Adicionais
    - Certifique-se de que o servidor web esteja em execução antes de iniciar a simulação no Unity.
    - O servidor e o projeto Unity estão configurados para trabalhar em "localhost". Se você estiver executando em ambientes diferentes, atualize as URLs no script Unity e no servidor conforme necessário.
