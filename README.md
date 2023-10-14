# <h1 align="center"><font color = #119fbf>Introdução ao Sistema Operacional Linux</font></h1>
Neste repositório estou compartilhando algumas anotações para a consulta sobre os principais comandos do terminal Linux.

<div align="center"><img src='https://cdn.icon-icons.com/icons2/2699/PNG/512/linux_logo_icon_171222.png'></div>

## Sobre 
A linha de comando do Linux é uma interface de texto, todos os comandos são inseridos no formato de texto. Possui diversos nomes, podendo ser habitualmente chamado de shell, terminal, console ou prompt.

## Comandos básicos
⭐ ```pwd```: Indica qual o diretório atual;

⭐ ```cd```: Mudar de diretório;

- ```cd nome_diretorio```: Entra em um diretório;
- ```cd ..```:  Volta para o diretório anterior;
- ~: Indica o repositório home (ou /);

⭐ ```ls```: Lista os arquivos de um diretório;

- ```ls -l```: Informa detalhes sobre o arquivo;
  
⭐ ```clear```: Limpa o terminal;

⭐ ```exit```: Sair do terminal;

⭐ ```sudo```: Concede permissões temporárias de superusuário (root) para executar tarefas administrativas;

### Criação de diretórios

⭐ ```mkdir nome_diretorio```: Cria uma nova diretorio.

### Criação de arquivos com o Terminal

⭐ ```touch texto.txt```: Criar um arquivo de texto vazio;

⭐ ```echo mensagem```: Escreve uma mensagem na tela;

-  ```echo mensagem > texto.txt```: Escreve uma mensagem no arquivo .txt;

⭐ ```cat texto.txt```: Exibir o conteúdo do arquivo texto.txt;

⭐ ```more texto.txt```: Leitura do conteúdo do arquivo texto.txt;

⭐ ```gedit texto.txt```: Abrir o arquivo texto.txt.

### Copiar, mover e renomear arquivos

⭐ ```cp diret1/texto.txt diret2/.```: Copiar arquivo texto.txt do diret1 para o diret2;

⭐ ```mv texto.txt texto2.txt```: Renomear arquivo;

⭐ ```mv /home/servidor/diret1/texto.txt /home/servidor/diret2/texto2.txt```: Mover arquivo.

### Remover arquivos e diretórios
⭐ ```rm texto.txt```: Apagar arquivos;

⭐ ```rm -rf diret1/```: Apagar diretório;

⭐ ```rm -rf *```: Apagar todos os arquivos.

### Permissões de arquivos
⭐ ```chmod 777 arquivo.txt```: Inserindo todas as permissões a um arquivo;

- r: Leitura = 4;
- w: escrita = 2;
- x: execução = 1;
- Dono - Grupo - Todos.
  
⭐ ```sudo chown root:root arquivo.txt```: Alterar o dono de um arquivo.

### Root
- O usuário root (administrador-mestre do sistema operacional) tem permissão para visualizar e editar qualquer coisa no computador. Em geral, você pode ter um usuário com "permissões de root", ou seja, poderes similares ao root.
- Para usar os poderes de root, adicione a palavra sudo antes de seus códigos.

⭐ ```sudo apt-get install htop```: Instalar programa htop pelo terminal.

### Desligar o computador pelo terminal 

⭐ ```sudo shutdown -r now```: Reiniciar o computador;

⭐ ```sudo shutdown -h now```: Desligar o computador.

## Referências
- [Introdução ao Sistema Operacional Linux](https://www.udemy.com/course/linux-ubuntu/)
- [Como começar a usar a linha de comando (Terminal) no Linux – Tutorial para Iniciantes](https://marquesfernandes.com/self/como-comecar-a-usar-a-linha-de-comando-terminal-no-linux-tutorial-para-iniciantes/)

### 
