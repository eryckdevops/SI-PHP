# Sistema Erick Rodrigues MULTI X

**Resumo da aplicação**
O sistema Sistema Faculdade foi pensado para que as escolas
possam administrar uma página web e gerenciar a escola em um único
sistema. Com nosso painel de controle o administrador
pode alterar praticamente tudo da página inicial(Imagens do 
slide, descrição da escola, textos do slide, imagem principal), 
além de administrar os conteúdo, acontecimentos e desempenho da Faculdade.

**EXECUTANDO O PROJETO**

Basta ter instalado algum ambiente de simulação de servidor, como o XAMPP, WAMP 
ou EASYPHP. Habilitar o Apache e o MySQL. Mover a pasta "sistema" para a pasta 
que o ambiente reconhece como localhost. No caso do XAMPP é a pasta htdocs, do 
EASYPHP e do WAMP é a www.


**BANCO DE DADOS**
O banco de dados está no arquivo system.sql, na pasta sistema

Basta importar ele por meio do mySql no phpMyAdmin


**INFORMAÇÕES ADICIONAIS**

:heavy_check_mark: MVC
:heavy_check_mark: Seguindo um padrão de projeto para verificar meu conhecimento em PHP!

:heavy_check_mark: Em uma arquitetura típica de aplicação seguindo o padrão MVC (Model-View-Controller) ou similar, a comunicação entre as camadas é estruturada da seguinte forma:

### View 

:heavy_check_mark: Responsável pela apresentação da interface gráfica ou de usuário.

:heavy_check_mark: Interage com o usuário, capturando eventos e enviando solicitações para os controllers.

### Controller :

:heavy_check_mark: Recebe as requisições da view e processa essas solicitações.

:heavy_check_mark: Manipula os dados recebidos da view e decide como interagir com o modelo (service).

:heavy_check_mark: Geralmente, encaminha os dados relevantes para o modelo junto com a requisição.

### Model:

:heavy_check_mark: Representa a lógica de negócios e os dados da aplicação.

:heavy_check_mark:  O serviço (service) dentro do modelo lida com a interação direta com o banco de dados.

:heavy_check_mark: Realiza operações CRUD (Create, Read, Update, Delete) no banco de dados para persistir ou recuperar informações.

:heavy_check_mark: Retorna resultados para o controlador, geralmente incluindo um valor booleano para indicar o sucesso da operação e uma mensagem descritiva.

### Service:

:heavy_check_mark: Parte do modelo encarregada de interagir diretamente com o banco de dados.

:heavy_check_mark: Implementa métodos específicos para realizar operações no banco de dados, seguindo a estrutura das entidades no esquema de banco de dados.

:heavy_check_mark: Pode envolver a criação, atualização, leitura ou exclusão de registros no banco de dados.


========================================================================================

:heavy_check_mark: AJAX
Todas as requisições são feitas via AJAX:
View->Ajax.js->Controller->Service->Controller->Ajax.js->View

:heavy_check_mark: Componentes
Todas as views do painel de controle (adm, aluno, professor)
são componentes que são chamados por meio da index.php.


# Screenshots do sistema

- **Projeto Erick Rodrigues**
![This is an image](/Prints/Home.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/Home2.png)

- **Projeto Erick Rodrigues**
![This is an image](/Prints/Cursos.png)

- **Projeto Erick Rodrigues**
![This is an image](/Prints/Cursos2.png)

- **Projeto Erick Rodrigues**
![This is an image](/Prints/conectada.png)

- **Projeto Erick Rodrigues**
![This is an image](/Prints/conectada2.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/FeitologinHome.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/FeitologinHome1.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/Notasdash.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/cadastrousuario.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/cadastroTurma.png)


- **Projeto Erick Rodrigues**
![This is an image](/Prints/VerificacaoTurma.png)



- **Projeto Erick Rodrigues**
![This is an image](/Prints/Descricao.png)






## 🤝 Desenvolvedor

Software Engineer

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/109317442?v=4" width="160px;" alt="Erick Rodrigues"/><br>
        <sub>
          <b>Erick Rodrigues</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 Licença

Este projeto está sob licença. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

&#xa0;



<a href="#top">Volte para o topo</a>