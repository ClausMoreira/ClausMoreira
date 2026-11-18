### Olá, sou o Claus

Estudo Ciência da Computação na FIAP, em São Paulo, e gosto de usar IA em problemas de verdade, aqueles que fazem diferença no dia a dia de quem trabalha.

Minha primeira automação com IA surgiu fora da faculdade, em uma gráfica onde trabalhei. A coleta de dados do sistema era manual e custava muito tempo além de se repetir todos os dias. Com ajuda de IA, escrevi um script que já entregava os dados tratados e organizados em planilha, o que economizou um tempo significativo no processo.

### Em destaque: [Radar de Avaliações](https://github.com/ClausMoreira/radar-de-avaliacoes)

Quem vende em marketplace recebe milhares de avaliações em texto livre, e a nota em estrelas não conta o que precisa ser resolvido. O Radar lê essas avaliações, descobre o motivo de cada reclamação e aponta por onde começar.

- **Painel** com as três prioridades da loja: [abrir o app](https://radar-de-avaliacoes.streamlit.app)
- **Agente** que responde perguntas em português consultando os dados. Os números vêm das ferramentas, nunca do modelo, e uma conferência automática checa cada um deles
- **Automação no n8n**: cada avaliação nova é classificada e registrada; se for crítica, vira um alerta com rascunho de resposta que só sai com aprovação humana
- **API** com tela de teste: [experimentar](https://radar-de-avaliacoes.vercel.app)
- **Acerto medido** contra avaliações que rotulei à mão: 88,3% em validação às cegas e 76,7% só nas reclamações (o número mais honesto, porque elogio é fácil de acertar)

Os tropeços e as correções de rota estão no [APRENDIZADOS.md](https://github.com/ClausMoreira/radar-de-avaliacoes/blob/main/APRENDIZADOS.md).

**Stack:** Python · API do Gemini · Streamlit · n8n · Google Planilhas · v0 · Vercel

### Fora da tela

Nas horas vagas imprimo peças 3d e desenvolvo projetos com hardware embarcado :)

[LinkedIn](https://www.linkedin.com/in/claus-henrique-ferreira-moreira-092b34429/)
