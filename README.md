# EpiGestão

## Objetivo
O EpiGestão é um aplicativo web para localização de hospitais com baixa ocupação. O problema resolvido é a peregrinação de pacientes em busca de atendimento, ajudando o cidadão comum a encontrar rapidamente um hospital com vagas disponíveis.

## Escopo
O sistema exibe um mapa interativo com pinos coloridos (verde, amarelo, laranja e vermelho) baseados na porcentagem de ocupação de cada hospital. O usuário pode buscar hospitais por cidade, ver a lista ordenada pelos mais vazios e traçar rotas. Ficam de fora desta fase: cadastro de médicos, controle de estoque de medicamentos e gestão de leitos internos.

## Time e papéis
- **Nicolas Torres Santos** - Product Owner / Designer UI/UX
- **Ana Cristina Aguiar Magalhães** - Scrum Master / Desenvolvedora Front-end
- **Jean Carlos Rodrigues Mendes** - Developer Back-end
- **Luís Felipe de Freitas Bernardes Santos** - Developer Analista de Dados

## Como executar
1. **Backend (Python/Django):** Entre na pasta `sistema_epi`, rode `pip install -r requirements.txt`, depois `python manage.py migrate` e `python manage.py runserver`.
2. **Frontend (React):** Entre na pasta `epigestao_frontend`, rode `npm install` e `npm start`.
halloween
