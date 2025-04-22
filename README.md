# API de Galeria de Fotos

Esta é uma API de galeria de fotos que armazena fotos em um banco de dados e as exibe na tela para o usuário.

## Funcionalidades

- Upload de fotos
- Armazenamento de fotos em um banco de dados
- Exibição de fotos na tela para o usuário

## Tecnologias Utilizadas

- Python
- Flask (ou outro framework web)
- Banco de dados (por exemplo, SQLite, PostgreSQL, MySQL)
- HTML/CSS para a interface do usuário

## Como Usar

1. Clone este repositório para sua máquina local.
2. Instale as dependências necessárias.
3. Configure o banco de dados.
4. Execute a aplicação.
5. Acesse a aplicação no seu navegador.

## Endpoints da API

- `POST /upload`: Faz o upload de uma foto.
- `GET /photos`: Retorna todas as fotos armazenadas.
- `GET /photos/<id>`: Retorna uma foto específica pelo ID.

## Exemplo de Uso

### Upload de Foto

```bash
curl -X POST -F 'file=@/caminho/para/sua/foto.jpg' http://localhost:5000/upload
