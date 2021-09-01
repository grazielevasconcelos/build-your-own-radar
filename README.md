Fork do projeto Radar da thoughtworks, projeto original [thoughtworks.com/pt/radar](https://www.thoughtworks.com/pt/radar).

## Como usar

Os dados devem estar de acordo com o formato abaixo para que o radar seja gerado corretamente.

### Planilha

Armazene a planilha `.csv` dentro de /sheets na estrtura mínima abaixo, exemplo do projeto original pode ser visto aqui: [estes dados](https://docs.google.com/spreadsheets/d/1OMQvrnN3qwzfBx8y6I77EskuTf10iESeh1Wpvw8hz_4/edit?usp=sharing).

#### Exemplos/Samples:

#### Inglês

| name          | ring   | quadrant               | isNew | description                                             |
|---------------|--------|------------------------|-------|---------------------------------------------------------|
| Composer      | adopt  | tools                  | TRUE  | Although the idea of dependency management ...          |
| Canary builds | trial  | techniques             | FALSE | Many projects have external code dependencies ...       |
| Apache Kylin  | assess | platforms              | TRUE  | Apache Kylin is an open source analytics solution ...   |
| JSF           | hold   | languages & frameworks | FALSE | We continue to see teams run into trouble using JSF ... |

#### Português

| name                 | ring        | quadrant                | isNew | description                                               |
|----------------------|-------------|-------------------------|-------|-----------------------------------------------------------|
| Compositor           | adote       | ferramentas             | TRUE  | Embora a ideia de gerenciamento de dependências ...       |
| Construções canárias | experimente | técnicas                | FALSE | Muitos projetos têm dependências de código externo ...    |
| Apache Kylin         | avalie      | plataformas             | TRUE  | Apache Kylin é uma solução analítica de código aberto ... |
| JSF                  | evite       | linguagens e estruturas | FALSE | Continuamos a ver as equipes enfrentando problemas ao ... |

## Docker Image Local
Executando o projeto e acessando a planilha armazenada:

```
$ docker-compose up web
$ open http://localhost:8080
```

Na home forneça o caminho local do seu `.csv`, exemplo:

```
Enter the URL of your Google Sheet or CSV file below…:
     http://localhost:8081/sheets/lab_radar_pt_br.csv

Build my radar
```

## Fork

Este projeto é um `fork` de https://github.com/thoughtworks/build-your-own-radar e também de melhorias feitas em https://github.com/dcasati/build-your-own-radar.

Acesse a [página](https://www.thoughtworks.com/radar/how-to-byor) para mais detalhes.

Agradecemos! :tada: