# Sistema Integrado de Gestão - Associação Comunitária Renascer (MVP)

Aplicação web desenvolvida para a Associação Comunitária Renascer (Osasco/SP), focada na digitalização do atendimento de balcão e no controle equitativo da distribuição de donativos alimentares, em consonância com o ODS 2 (Fome Zero).

## Tecnologias Empregadas
- **Linguagem & Backend:** Python 3.12 com FastAPI e Pydantic
- **Mapeamento Objeto-Relacional:** SQLAlchemy 2.0
- **Banco de Dados:** PostgreSQL 16 (hospedado via Supabase)
- **Frontend:** Aplicação Web Responsiva (PWA)

## Funcionalidades Principais
- **RF01:** Consulta e validação cadastral de famílias beneficiárias por CPF ou nome.
- **RF02:** Registro de entrega de mantimentos com trava temporal impeditiva contra duplicidade mensal.
- **RF03:** Baixa atômica de saldo no inventário de donativos em estoque.
- **RNF04:** Acessibilidade completa segundo diretrizes WCAG 2.1 (Nível AA).
