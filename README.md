# Docker Apache Web Application

Este projeto utiliza **Docker Compose** para rodar uma aplicação HTML simples em um servidor Apache dentro de um container Docker. Ele pode ser expandido com estilos em **CSS** e interatividade em **JavaScript** para construir uma aplicação web completa.

## Tecnologias Utilizadas
- **Docker Compose**
- **Apache (httpd)**
- **HTML5**
- **CSS3** (para estilização adicional)
- **JavaScript** (para interatividade adicional)

## Estrutura do Projeto
- `docker-compose.yml`: Arquivo de configuração do Docker Compose para subir o servidor Apache.
- `html/`: Diretório onde ficam os arquivos HTML da aplicação. O arquivo principal é o `index.html`.

## Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o **Docker** e o **Docker Compose** instalados na sua máquina. Você pode verificar se ambos estão instalados corretamente executando:

```bash
docker --version
docker-compose --version
```

### Passos para executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/mario-evangelista/container-app-web.git
   ```
   
2. Navegue até o diretório do projeto:
   ```bash
   cd container-app-web
   ```

3. Suba os containers com o Docker Compose:
   ```bash
   docker-compose up
   ```

4. Acesse a aplicação no navegador:
   ```
   http://localhost:8080
   ```

Você verá a página `Hello, Docker World!`.

### Personalizando o Projeto
- Para editar o conteúdo da página, modifique o arquivo `html/index.html`.
- Para adicionar estilos, crie um arquivo CSS dentro da pasta `html` e referencie-o no `index.html`.
- Para adicionar interatividade com JavaScript, inclua seus scripts também dentro da pasta `html`.

## Referências
- [Documentação do Docker](https://docs.docker.com/)
- [Documentação do Apache HTTP Server](https://httpd.apache.org/docs/)
- [Documentação HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [Documentação CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [Documentação JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## Contribuição
Fique à vontade para abrir issues e fazer pull requests com melhorias ou correções. Todas as contribuições são bem-vindas!

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
```

Este `README.md` cobre as informações essenciais sobre o projeto, instruções para rodar o container com Docker Compose e links úteis para quem quiser entender melhor o funcionamento do projeto ou contribuir com ele.
