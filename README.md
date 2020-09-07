# Teste fullstack, frontend e backend

A ideia desse projeto é conhecer melhor seus conhecimentos técnicos

Escolha a missão de acordo com a vaga que está buscando:
- Frontend
- Backend
- Fullstack (Frontend + Backend)

Leia primeiro todo o projeto, faça sua estimativa de horas para o desenvolvimento e envie um email com o título `[Teste <tipo-vaga> <seu-nome>] Estimativa` para ana@ykron.com

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) e envie um email com o título `[Teste <tipo-vaga> <seu-nome>] Finalizado` para ana@ykron.com

##Arquitetura e documentação

No arquivo README do projeto explique o funcionamento e a arquitetura da solução adotada na sua implementação. Descreva também os passos para executar corretamente seu projeto.

## Missão backend

Desenvolver uma **API JSON RESTful**, que utilize todos os métodos (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).  
Faça o teste unitário da **API** (Bônus :star:)
### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
marca:     string
ano:       integer
descricao: text
vendido:   bool
created:   datetime
updated:   datetime
```

Utilize um banco NoSQL ou SQL para armazenar os dados que a **API** irá consumir.

### API endpoints

`GET /veiculos`

Retorna todos os veículos

---

`GET /veiculos/find`

Retorna os veículos de acordo com o termo passado parâmetro `q`

---

`GET /veiculos/{id}`

Retorna os detalhes do veículo

---

`POST /veiculos`

Adiciona um novo veículo

---

`PUT /veiculos/{id}`

Atualiza os dados de um veículo

---

`PATCH /veiculos/{id}`

Atualiza apenas alguns dados do veículo

---

`DELETE /veiculos/{id}`

Apaga o veículo


## Missão frontend

Desenvolver uma **UI (User Interface)** de acordo com o desenho que está na pasta [layout](https://github.com/TExTecnologia/teste-fullstack/tree/master/layout). Encaminhar um print das telas desenvolvidas junto do e-mail de finalização(Enviar [gifs](https://www.screentogif.com/) das interações é um bom diferencial).

### Especificação

- Cross browser support (IE11+)
- Consumir **API** criada acima (caso sua vaga for fullstack)
- Simular o consumo da **API** criada acima martelando o retorno dos dados (caso sua vaga for frontend)
- Criar uma tela que tenha...
    - Listagem de veículos
    - Detalhe do veículo
    - Busca
    - Formulário de novo/edição de veículos

Utilizar React é um diferencial(Bônus :star:)

### Dica

Utilize algum framework para auxiliar no desenvolvimento da interface.


## Avaliação

Entre os critérios de avaliação estão:
- Facilidade de configuração do projeto
- Performance
- Código limpo e organização
- Documentação de código
- Documentação do projeto (readme)
- Arquitetura
- Boas práticas de desenvolvimento
- Design Patterns

## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste <tipo-vaga> <seu-nome>] O assunto que vc deseja` para ana@ykron.com

##Créditos

Esse desafio foi construido com base no desafio da [TExTecnologia](https://github.com/TExTecnologia/teste-fullstack) e da [Contabilizei](https://github.com/contabilizei/fullstack-java-teste).
