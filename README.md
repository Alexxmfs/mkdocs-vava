# Projeto Interdisciplinar III - Sistemas de Informação ESPM

<p style="text-align: center;">
    <a href="https://www.espm.br/cursos-de-graduacao/sistemas-de-informacao/"><img src="https://avatars.githubusercontent.com/u/49880458?s=200&v=4" alt="Sistemas de Informação ESPM" style="height: 200px; width: 200px;"/></a>
</p>

### 2024-03

## Integrantes
- [Alex Macedo](https://github.com/Alexxmfs)
- [Henrique Sardella](https://github.com/henrique-sdc)
- [Thiago Alonso](https://github.com/ThiagoAlonso05)
- [Rafa Ambrosio](https://github.com/rafaambrosio)
- [Débora Duarte](https://github.com/duartedebis)

# Documentação do Projeto Valorant Player Dashboard

Este repositório contém a documentação do projeto Valorant Player Dashboard, criada utilizando o MkDocs.

## Sobre

O Valorant Player Dashboard é um projeto interdisciplinar desenvolvido por estudantes do curso de Sistemas de Informação da ESPM. O objetivo do projeto é criar um dashboard para visualização e análise de dados de jogadores do jogo Valorant, incluindo estatísticas como partidas jogadas, pontuações, taxas de vitória, entre outros.

## Acesso à Documentação

A documentação está disponível online em [LINK PARA A DOCUMENTAÇÃO](https://alexxmfs.github.io/mkdocs-vava/diagrama/microservices/gateway/) ou pode ser executada localmente seguindo as instruções abaixo.
 
Você pode instalar as bibliotecas necessárias executando o seguinte comando no terminal:

```bash
pip install requests
pip install lxml
pip install pandas
pip install fake_useragent
```

## Uso

1. Execute o arquivo `main.py`.
2. O programa irá raspar os dados dos jogadores do Valorant do site Tracker.gg.
3. Os dados coletados serão pré-processados e enviados para uma API local.

## Estrutura do Projeto

- `main.py`: Arquivo principal que inicia o processo de raspagem de dados.
- `utils.py`: Contém funções utilitárias para processamento e inserção de dados.

## Licença

Este projeto é licenciado sob a [MIT License](https://github.com/tech-espm/inter-2sem-2023-eventos/blob/main/LICENSE).