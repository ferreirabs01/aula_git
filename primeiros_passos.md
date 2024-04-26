Pré-requisitos:
##

>Ter o Git instalado em seu computador: Acesse https://git-scm.com/downloads e baixe a versão adequada para o seu sistema operacional.
>Criar uma conta no GitHub: Acesse https://github.com/ e crie sua conta gratuita.

Passo 1: Criando um Repositório Local
##

Abra o terminal ou prompt de comando: No Windows, você pode encontrar o prompt de comando no menu Iniciar. No Mac ou Linux, utilize o terminal.
Navegue até o diretório do seu projeto: Utilize o comando cd para navegar até a pasta onde seus arquivos de projeto estão armazenados.
Inicialize um repositório Git: Digite o comando git init e pressione Enter. Isso transformará sua pasta em um repositório Git local.
Adicione os arquivos ao repositório: Utilize o comando 
git add <nome_do_arquivo> 
para adicionar cada arquivo que você deseja incluir no versionamento. Você também pode usar 
~~~cmd
git add . 
~~~

para adicionar todos os arquivos de uma vez.
Faça um commit das alterações: Digite o comando git commit -m "Mensagem do commit" e pressione Enter. Substitua "Mensagem do commit" por uma descrição breve das alterações que você fez.

Passo 2: Criando um Repositório Remoto no GitHub

Acesse o GitHub e crie um novo repositório: Faça login em sua conta do GitHub e clique no botão "Novo repositório". Dê um nome descritivo ao seu repositório e marque a opção "Inicializar com um README". Clique em "Criar repositório".
Copie a URL do repositório remoto: Na página do seu novo repositório no GitHub, copie a URL que começa com "https://github.com...". Essa URL será utilizada para conectar seu repositório local ao remoto.
Passo 3: Conectando ao Repositório Remoto

No terminal, retorne ao diretório do seu projeto: Utilize o comando cd para navegar até a pasta onde o repositório local foi criado.
Vincule o repositório local ao remoto: Digite o comando git remote add origin <URL_do_repositório_remoto> e pressione Enter. Substitua <URL_do_repositório_remoto> pela URL que você copiou do GitHub.
Suba seus arquivos para o repositório remoto: Digite o comando git push -u origin master e pressione Enter. Isso enviará seus arquivos e o histórico de commits para o repositório remoto no GitHub.
Parabéns! Você concluiu com sucesso a criação e o upload do seu primeiro repositório Git. Agora, você pode compartilhar seu código com outros desenvolvedores, colaborar em projetos e acompanhar o histórico de alterações do seu software de forma eficiente.

Dicas Extras:

Utilize mensagens de commit informativas: Descreva claramente o que você alterou em cada commit para facilitar a compreensão do histórico do seu código.
Faça commits frequentes: Não aguarde grandes mudanças para fazer um commit. Realize commits frequentes para manter um histórico detalhado do seu trabalho.
Utilize branches para diferentes funcionalidades: Crie branches para trabalhar em novas funcionalidades sem afetar o código principal.
Aprenda sobre as melhores práticas do Git: Explore tutoriais e documentações online para aprimorar suas habilidades no uso do Git e otimizar seu workflow de desenvolvimento.
Lembre-se que o Git é uma ferramenta poderosa que pode aprimorar significativamente sua organização e colaboração em projetos de software. Com prática e dedicação, você se tornará um expert em versionamento de código e estará pronto para enfrentar os desafios do desenvolvimento moderno.