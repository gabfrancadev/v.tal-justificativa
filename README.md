# 📝 Justificativa de Indicadores Operacionais — V.tal

Aplicação corporativa desenvolvida para a operação de **Fibra Óptica | Home Connect** da V.tal, criada para substituir a coleta manual de justificativas de indicadores operacionais por um fluxo digital padronizado. Utilizada por um setor inteiro, com acesso disponível para toda a operação.

> Por se tratar de um sistema interno corporativo, o pacote da aplicação e as listas do ambiente permanecem privados. Este repositório reúne a documentação funcional e as telas do sistema.

## 🛠️ Tecnologias

- **Power Apps** — construção da interface e navegação entre telas
- **Power Fx** — regras de validação, filtros, controle de estado e integração de dados
- **SharePoint** — armazenamento estruturado dos registros e permissões de acesso

## 🖥️ Telas do Sistema

### 1. Formulário de Justificativa (`Justificativa de Indicadores Operacionais`)
Padroniza o preenchimento com seleção de **Período de referência**, **Atividade**, **Indicador**, **Regional**, **Resultado realizado**, **Meta** e **Status da ação**, além de estruturar o plano em 5 etapas obrigatórias:
1. **Fato** — descrição objetiva do ocorrido
2. **Causa** — motivo e fatores que contribuíram para o resultado
3. **Ação** — medida definida para corrigir ou evitar o problema
4. **Responsável** — quem executará a ação
5. **Prazo** — data prevista para conclusão

[./assets/tela-formulario.webp]

### 2. Painel de Consulta (`Justificativas Recebidas`)
Centraliza os envios realizados com filtros por **Período** e **Regional**, visualização tabular dos indicadores e ações para **Novo envio**, **Atualizar**, **Visualizar**, **Editar** e **Excluir** registros.

[./assets/tela-recebidas.webp]
