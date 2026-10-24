## **Requisitos Funcionais Detalhados para Testes Manuais**


## RF01 - Painel Inicial e Dashboard

**Descrição:** O sistema deve disponibilizar painéis para visualização resumida das principais informações operacionais, financeiras e gerenciais da academia.

**Funcionalidades esperadas:**

- Exibir indicadores e informações resumidas da academia.
- Exibir informações relacionadas a clientes, matrículas, finanças, presenças, agenda e retenção.
- Disponibilizar uma Página Inicial com informações consolidadas.
- Disponibilizar um Dashboard adicional com indicadores operacionais e financeiros.
- Permitir acesso às funcionalidades relacionadas à inteligência do sistema.
- Permitir navegação para funcionalidades relacionadas aos indicadores apresentados.

---

## RF02 - Controle de Check-in e Presenças

**Descrição:** O sistema deve permitir consultar e gerenciar informações referentes à entrada e presença dos clientes na academia.

**Funcionalidades esperadas:**

- Consultar check-ins realizados.
- Pesquisar check-ins por cliente.
- Consultar check-ins de acordo com a unidade.
- Filtrar registros pelas situações:
  - Todos;
  - Presentes agora;
  - Não compareceram;
  - Check-in pendente.
- Disponibilizar ação para realização de check-in manual.
- Disponibilizar ação para registro de entrada.
- Consultar presenças por intervalo de datas.
- Disponibilizar atalhos de período para Hoje, Esta semana e Este mês.


---

## RF03 - Gestão de Clientes

**Descrição:** O sistema deve permitir o gerenciamento das informações dos clientes da academia.

**Funcionalidades esperadas:**

- Listar os clientes cadastrados.
- Permitir pesquisa por código, nome, status, situação, plano e personal.
- Permitir paginação da listagem.
- Disponibilizar formulário para cadastro de clientes.
- Manter informações de identificação e documentos pessoais.
- Manter informações de contato e endereço.
- Manter informações relacionadas à biometria e aplicativo.
- Manter dados do responsável quando aplicável.
- Permitir visualizar os detalhes de um cliente.
- Apresentar informações consolidadas sobre perfil, matrícula, presenças, desempenho e situação financeira.
- Disponibilizar ações de alteração e exclusão.


---

## RF04 - Gestão de Matrículas

**Descrição:** O sistema deve permitir consultar e administrar as matrículas dos clientes.

**Funcionalidades esperadas:**

- Listar e pesquisar matrículas.
- Realizar pesquisa por data.
- Disponibilizar cadastro de matrícula.
- Relacionar matrícula a cliente e modalidade/plano.
- Manter data inicial e data final.
- Permitir os estados Ativo, Inativo e Finalizado.
- Identificar se uma matrícula é renovada.
- Manter moeda e tipo de pagamento.
- Manter taxa de matrícula.
- Manter dia de vencimento.
- Manter valor da parcela, desconto e valor total.
- Permitir visualizar os detalhes.
- Disponibilizar edição, cancelamento e exclusão.

---

## RF05 - Gestão de Avaliações Físicas

**Descrição:** O sistema deve permitir consultar, agendar e administrar avaliações físicas dos clientes.

**Funcionalidades esperadas:**

- Listar avaliações.
- Pesquisar por código, nome e status.
- Diferenciar avaliações pendentes e realizadas.
- Disponibilizar cadastro ou agendamento.
- Relacionar a avaliação a aluno e personal/avaliador.
- Registrar data e hora.
- Permitir visualizar uma avaliação existente.
- Disponibilizar informações de IMC, circunferências, dobras subcutâneas e composição corporal.
- Permitir impressão.
- Disponibilizar comparação entre avaliações.
- Disponibilizar alteração e exclusão.

---

## RF06 - Gestão de Contas a Receber

**Descrição:** O sistema deve permitir consultar e administrar os valores a receber da academia.

**Funcionalidades esperadas:**

- Listar contas a receber.
- Pesquisar utilizando código, nome, tipo de data, período e status.
- Consultar títulos Pendentes, Recebidos, Vencidos e Cancelados.
- Disponibilizar cadastro de conta.
- Relacionar a conta a um cliente.
- Registrar título, valor, moeda e vencimento.
- Registrar funcionário responsável pelo recebimento.
- Registrar valor e data de recebimento.
- Registrar tipo e local de pagamento.
- Permitir visualizar detalhes.
- Disponibilizar ações de exclusão e cancelamento.

---

## RF07 - Gestão de Contas a Pagar

**Descrição:** O sistema deve permitir consultar e administrar as despesas e contas a pagar da academia.

**Funcionalidades esperadas:**

- Listar e pesquisar contas a pagar.
- Disponibilizar cadastro de conta.
- Diferenciar despesas variáveis e fixas.
- Diferenciar contas/despesas de pagamentos de colaboradores.
- Relacionar contas a fornecedores ou colaboradores.
- Registrar tipo e número de documento.
- Registrar categoria financeira.
- Registrar data de emissão.
- Registrar valor e vencimento.
- Registrar local de pagamento.
- Registrar observações.
- Permitir consultar detalhes.
- Disponibilizar exclusão.

---

## RF08 - Gestão de Fichas de Treino

**Descrição:** O sistema deve permitir consultar e administrar fichas de treino dos alunos.

**Funcionalidades esperadas:**

- Listar e pesquisar fichas de treino.
- Disponibilizar criação de nova ficha.
- Permitir criação a partir de modelo existente.
- Relacionar ficha ao aluno e personal.
- Definir data inicial e final.
- Relacionar ficha a um objetivo.
- Registrar observações.
- Utilizar exercícios cadastrados na composição das fichas.

---

## RF09 - Biblioteca de Exercícios

**Descrição:** O sistema deve permitir administrar os exercícios utilizados nas fichas de treino.

**Funcionalidades esperadas:**

- Listar exercícios.
- Organizar exercícios por grupos musculares.
- Disponibilizar cadastro.
- Registrar nome.
- Permitir associação de imagem.
- Permitir associação de vídeo.
- Informar formatos e limites aceitos.
- Permitir visualizar exercícios existentes.
- Disponibilizar exclusão.

A interface informa suporte a imagens **JPG/PNG de até 5 MB** e vídeos **MP4/MOV de até 50 MB**.

---

## RF10 - Classificações e Objetivos de Treinamento

**Descrição:** O sistema deve permitir administrar informações auxiliares utilizadas na organização dos treinamentos.

**Funcionalidades esperadas:**

- Administrar grupos musculares.
- Classificar grupos entre Inferiores, Superiores e Aeróbio.
- Permitir associação de imagem ao grupo.
- Administrar objetivos de treino.
- Manter nome e descrição dos objetivos.
- Administrar categorias de exercícios Crossfit.
- Utilizar essas classificações nas funcionalidades de treinamento.
