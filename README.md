# Cloud & Infra Advisor - Consultoria em Transformação Digital

**Acesse o Aplicativo Online (GitHub Pages):** [Clique aqui para abrir o App](https://gsleao.github.io/consultoria/)

## Especialistas Responsáveis (Autores)
* Gustavo Leão da Silva (gsleao)
* **Unidade Curricular:** Exploração Digital e Fundamentos Tecnológicos (Objetos de Conhecimento 05 e 06)

## 1.0 Problema Empresarial e Objetivo do Aplicativo
Este aplicativo resolve a dificuldade que as PMEs enfrentam ao manter servidores locais sem redundância, arriscando-se à perda de dados, problemas de conectividade e custos operacionais elevados, oferecendo um diagnóstico automatizado e um roteiro seguro para migração em nuvem.

## 2. Os 4 Pilares de Boas Práticas Aplicados no Diagnóstico
* **Infraestrutura e Migração para a Nuvem:** Recomendações sobre modelos ideais (SaaS, PaaS ou IaaS), aplicação da regra de backup 3-2-1 automatizado e monitoramento de custos (FinOps)
* **Sistemas Empresariais (ERP/CRM) e Fluxo de Dados:** Alinhamento para eliminação de planilhas isoladas e centralização de dados.
* **IA Generativa e Automação No-Code:** Identificação de gargalos operacionais e uso de ferramentas eficientes com supervisão humana.
* **Governança, Ética e Segurança Digital (LGPD):** Diretrizes de segurança, controle de acesso e tratamento de dados sensíveis sob o princípio de *Privacy by Design*.

## 3. IAs Generativas e Ferramentas Utilizadas

| Ferramenta / IA | Como foi utilizada no projeto |
| :--- | :--- |
| **Claude / Lovable** | Estruturação das regras de negócio, lógica de pontuação do diagnóstico e geração do código em ficheiro único. |
| **TailwindCSS & Chart.js (CDN)** | Estilização executiva responsiva e geração do gráfico dinâmico de prontidão para a nuvem. |
| **GitHub & GitHub Pages** | Versionamento de código e publicação imediata em nuvem estática (PaaS/CDN). |

## 4. Diário de Construção: Como Construímos e Refinamos o App
1. **Concepção e Engenharia de Prompt:** Utilização de um prompt estruturado para gerar a arquitetura *Single-File* com formulário, motor de cálculo e dashboard gráfico.
2. **Ajustes e Refinamentos Técnicos:** Validação de scripts externos via CDN e garantia de responsividade e exportação correta em PDF via `window.print()`.
3. **Principal Aprendizado:** Compreensão prática de como a consultoria em nuvem pode ser automatizada e disponibilizada rapidamente na web sem dependências complexas de servidores.
