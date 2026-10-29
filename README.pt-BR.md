[English](https://github.com/rodrigoteixeiraferreira/rodrigoteixeiraferreira/blob/main/README.md) · **Português** · [Español](https://github.com/rodrigoteixeiraferreira/rodrigoteixeiraferreira/blob/main/README.es.md)

# Rodrigo Teixeira Ferreira

**Engenheiro de Automação e IA** — n8n · Supabase · PostgreSQL · RAG

Construo agentes de IA em que a lógica de negócio vive no banco de dados, não no prompt.

Disponibilidade, precificação, transações atômicas e cálculo de saldo são funções SQL.
O modelo interpreta a intenção e escolhe a ferramenta. Três consequências: roda em
modelos baratos, não depende de um fornecedor específico, e não erra em contas que
nunca faz. Quando um modelo decide alguma coisa, a taxa de erro dele é medida por amostra,
e acima do limite ele para de decidir sozinho.

---

### Projetos

**[comparador-listas-fornecedores](https://github.com/rodrigoteixeiraferreira/comparador-listas-fornecedores)** — Comparador de listas de preço de fornecedores: estudo de caso e demo que roda
Entregue em outubro de 2026 a um supermercado de bairro. Lê listas de preço de fornecedores
em planilha, PDF e foto, identifica cada linha no cadastro da loja numa cascata em SQL e
mostra quem vende mais barato. Critério de aceite: zero falso positivo — 0 contradição nos
pares confirmados, erro da IA medido por amostra (1 em 145). A demo pública é reescrita do
zero, com dados fictícios, e se prova sozinha: 0 par errado em 5 mundos gerados, 51 de 51
listas estragadas seguradas no portão.
`PostgreSQL` · `Supabase` · `Python` · `Next.js` · `Claude Code`

**[agente-matriculas-ia](https://github.com/rodrigoteixeiraferreira/agente-matriculas-ia)** — Agente de IA para matrículas
Consulta cursos, verifica vagas e registra pré-inscrições por chat. As regras de negócio
são funções SQL versionadas: o modelo interpreta a intenção e escolhe a ferramenta, mas
nunca decide sobre vaga.
`FastAPI` · `Google Gemini` · `PostgreSQL` · `Docker` · `CI`

**[agente-hoteleiro-ia](https://github.com/rodrigoteixeiraferreira/agente-hoteleiro-ia)** — Agente de reservas para hotéis independentes
Disponibilidade real por sobreposição de datas, reserva atômica com `FOR UPDATE`,
entrada multimodal (áudio, imagem, PDF) e protocolo antifraude em comprovantes de
pagamento. O agente nunca confirma um pagamento — ele retém o quarto e uma pessoa
verifica.
Custo medido: US$ 0,032 por conversa completa de reserva, no modelo mais econômico da linha.
`n8n` · `Supabase` · `pgvector` · `Google Gemini` — [vídeo de demonstração](https://youtu.be/eq6xmbjIrdc)

**[agente-prevendas-telecom-n8n](https://github.com/rodrigoteixeiraferreira/agente-prevendas-telecom-n8n)** — Sistema multiagente de pré-vendas B2B
Um orquestrador roteando para três subagentes especializados — qualificação de leads,
guia de portabilidade e triagem por SLA — todos lendo de uma única base vetorial
central, de modo que não consigam se contradizer.
`n8n` · `Supabase` · `pgvector` · `RAG`

---

### Stack

`n8n` `Supabase` `PostgreSQL` `PL/pgSQL` `pgvector` `RAG` `Python` `FastAPI` `Next.js`
`Google Gemini` `Claude API` `APIs REST` `Docker` `Lovable` `Cursor` `Claude Code` `Git`

---

### Sobre

Baseado na Argentina — GMT-3, mesmo fuso do Brasil. Atuação 100% remota.
Português (nativo) · Espanhol (fluente) · Inglês (leitura técnica).

Todo repositório aqui é algo que eu consigo explicar e modificar. Nada é decorativo.

[LinkedIn](https://www.linkedin.com/in/rodrigo-teixeira-ferreira-2b00a31b6) · flechamedicina@gmail.com
