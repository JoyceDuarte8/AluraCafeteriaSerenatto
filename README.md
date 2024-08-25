![image](https://github.com/user-attachments/assets/08a4e70b-a5d1-4059-a6e0-6c39474bac64)

# Cafeteria Serenatto

Aplicação Web de simulação de Administração de produtos de uma Cafeteria. Elaborado durante o curso da Alura.

## 🔨 Funcionalidades do projeto

A Aplicação Web lista produtos com imagem, título, descrição e valor. Também, é possível cadastrar, editar e excluir os produtos. Todo armazenamento é mantido no Banco de Dados.

![image](https://github.com/user-attachments/assets/9b668351-d309-45e3-8783-cad491731b39)

![image](https://github.com/user-attachments/assets/1a649248-2dc5-4bb7-9bab-99739872017c)

![image](https://github.com/user-attachments/assets/f2636f7f-682c-443a-bc01-6dba285a3ba3)

Baixa um arquivo PDF da lista de produtos cadastrados:

![image](https://github.com/user-attachments/assets/1f3edbc0-cc72-44e1-865e-177e1fef4e11)


## ✔️ Técnicas e tecnologias utilizadas

As técnicas e tecnologias utilizadas pra isso são:

- `Framework`: PhpStorm;
- `Linguagens`: PHP, HTML, CSS e JavaScript;
- `PDO`: Classe que permite a conexão com o Banco de Dados e aplicação de métodos;
- `fetchAll()`: É usada em conjunto com uma consulta ao banco de dados para recuperar todos os registros resultantes dessa consulta;
- `array_map`: Aplica uma função de callback a todos os elementos de um ou mais arrays e retorna um array com os resultados;
- `FETCH_ASSOC`: Retorna um array associativo;
- `ob_start`: Função que iniciar um buffer de saída, e tudo que vir depois dessa função será carregado mas ainda não vai ser exibido na página. 
- `ob_get_clean()`: Armazena o conteúdo em uma variável
- `dompdfs`: Biblioteca para geração de PDF ( Baixar no site https://packagist.org/packages/dompdf/dompdf )

## 🎯 Desafio : Aplicações que fiz além do curso

- Tela de Login
- Menu Produtos
- Roteamento das páginas

## 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir no PhpStorm, e após isso acesse o terminal e execute o seguinte comando:

    php -S localhost:8080

        ou

     php -c php.ini -S localhost:8080 


Para gerar o PDF:
No site Packagist, vamos pesquisar por "pdf" e selecione a biblioteca dompdf/dompdf (https://packagist.org/packages/dompdf/dompdf) .
Para baixar essa biblioteca, vamos copiar o comando que está logo abaixo do nome dela.

     composer require dompdf/dompdf

## 📚 Mais informações do curso

Você pode [acessar o curso](https://cursos.alura.com.br/course/php-mysql-criando-primeira-aplicacao-web)
