# Dicas GIT

#### Comandos:

- mkdir => cria repositorio

- cd => navega entre repositorios

- cd (nome do repositorio) entra no repositorio

- cd .. => volta uma pasta

- ls => lista itens do repositorio

- ls -a => lista repositorios ocultos

- cls => limpa tela

- mv => move 

- git -v => lista repositorios 

- git inti => cria um repositorio

- git clone => clona um repositorio para sua pasta local

- git status => descrição do status 

  ####Passos para gerar commit

  1. git add * 

  2. git commit -m "descrição" 

     caso gere erro por 2 pssoas estarem alterando a mesma linha:

     1. git pull origin master (vai te contar o local)
     2. altera o arquivo deixando mais atualizado
     3. git add * 
     4. git commit -m "descrição" 

  3. git push 