# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href="https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Cannoli Dashboard
### Dashboard Analítico – Projeto Interdisciplinar · 4º Semestre · 2026
 
**FECAP – Fundação Escola de Comércio Álvares Penteado**
Curso de Ciência da Computação · Grupo: Brunettes
 
[![Acesse o Dashboard](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://eric-bittu-projeto5-srcmain-61rs5p.streamlit.app/)
 
</div>
---
 
## 📌 Sobre o Projeto
 
A **Cannoli** é uma startup foodtech que oferece CRM, automação de engajamento, cardápio digital e delivery próprio para restaurantes parceiros. O problema central identificado foi a **falta de visibilidade sobre o retorno das campanhas contratadas** — os restaurantes pagavam pelo serviço sem conseguir comprovar se as campanhas geravam resultado real.
 
O **Cannoli Insight Hub** é um dashboard analítico desenvolvido para resolver esse problema, centralizando dados de pedidos, campanhas e clientes em uma ferramenta de fácil interpretação, com dois perfis de acesso distintos.
 
---
 
## 🎯 Objetivos
 
**Geral:** Desenvolver um dashboard web que comprove, com dados, o impacto das campanhas da Cannoli no faturamento e na recorrência dos restaurantes parceiros.
 
**Específicos:**
- Centralizar e tratar dados de pedidos, campanhas e clientes
- Criar painéis diferenciados para Admin Cannoli e Empresa Parceira
- Implementar alertas automáticos para quedas de indicadores
- Aplicar segmentação de clientes e análise comparativa por período
---
 
## 💻 Tecnologias Utilizadas
 
| Categoria | Tecnologia |
|-----------|-----------|
| Linguagem | Python |
| Interface web | Streamlit |
| Visualização | Plotly |
| Tratamento de dados | Pandas |
| Banco de dados | MySQL |
| Versionamento | Git e GitHub |
| IDE | Visual Studio Code |
 
---
 
## ⚙️ Funcionalidades
 
- Dois perfis de acesso: **Cannoli Admin** (visão geral) e **Empresa Parceira** (visão individual)
- KPIs principais: faturamento, ticket médio, taxa de recorrência e taxa de conversão
- Comparativo de pedidos orgânicos versus pedidos gerados por campanhas
- Filtros por período, canal de venda e tipo de campanha
- Alertas automáticos quando indicadores caem acima do limiar configurado
- Segmentação de clientes por perfil de consumo
- Exportação de dados em CSV
---
 
## 🌐 Acesso
 
O dashboard está disponível online:
 
🔗 **[https://eric-bittu-projeto5-srcmain-61rs5p.streamlit.app/](https://eric-bittu-projeto5-srcmain-61rs5p.streamlit.app/)**
 
---
 
## 🚀 Como Rodar Localmente
 
```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
 
# 2. Entre na pasta
cd seu-repositorio
 
# 3. Instale as dependências
python -m pip install streamlit pandas plotly mysql-connector-python
 
# 4. Inicie o dashboard
python -m streamlit run src/main.py
```
 
---

## 👥 Time
 
| Nome | GitHub |
|------|--------|
| Bruno Eduardo da Silva Pinho | [@Smug303](https://github.com/Smug303) |
| Eric Victor Bittu Silva | [@eric-bittu](https://github.com/eric-bittu) |
| Rafael Marques | [@Rafael-M-Marques](https://github.com/Rafael-M-Marques) |
| Vivian Kaori Umaki | [@vivikari](https://github.com/vivikari) |
| Yanko Lee | [@Yanko-dev](https://github.com/Yanko-dev) |
 
---
 
## 📚 Professores Orientadores
 
- [Eduardo Savino Gomes](https://www.linkedin.com/in/eduardo-savino/)
- [Lucy Mari Tabuti](https://www.linkedin.com/in/lucymari/)
- [Maurício Lopes da Cunha](https://www.linkedin.com/in/maureen-leung-5630492a/)
- [Rodnil da Silva Moreira Lisboa](https://www.linkedin.com/in/professorrodnil/)

---

## 📁 Estrutura de Arquivos

```bash
dashboard-cannoli/
│
├── 📁 documentos/
│   ├── 📁 entrega-1/
│   │   ├── 📄 Engenharia de Software e Arquitetura de Sistemas.pdf
│   │   ├── 📄 Análise Inferencial de Dados.pdf
│   │   ├── 📄 Contabilidade e Finanças.pdf
│   │   └── 📄 Ciência de Dados.pdf
│   ├── 📁 entrega-2/
│   │   ├── 📄 Engenharia de Software e Arquitetura de Sistemas.pdf
│   │   ├── 📄 Contabilidade e Finanças.pdf
│   │   └── 📄 Ciência de Dados.pdf
├── 📁 src/
│   ├── 📁 backend/
│   └── 📁 frontend/
│
└── 📄 README.md
```