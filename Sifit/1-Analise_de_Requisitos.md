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

---

## RF11 - Gestão de Turmas e SifitBox

**Descrição:** O sistema deve permitir administrar turmas, horários e aulas utilizadas pela academia.

**Funcionalidades esperadas:**

- Listar e pesquisar turmas.
- Cadastrar turmas.
- Relacionar turma a plano.
- Definir horário inicial e final.
- Definir dias da semana.
- Identificar possibilidade de aula experimental.
- Definir existência de personal.
- Definir duração da turma.
- Administrar modalidades e turmas recorrentes do SifitBox.
- Definir quantidade de vagas.
- Consultar aulas por período.
- Disponibilizar geração de aulas do SifitBox.

---

## RF12 - Gestão de Caixas

**Descrição:** O sistema deve permitir consultar e administrar os caixas financeiros da academia.

**Funcionalidades esperadas:**

- Listar caixas.
- Pesquisar por período e status.
- Disponibilizar ação para abertura de caixa.
- Permitir visualizar caixa existente.
- Apresentar informações para fechamento.
- Informar usuário, período e local.
- Permitir buscar contas relacionadas ao fechamento.
- Disponibilizar impressão.

---

## RF13 - Gestão de Despesas Fixas

**Descrição:** O sistema deve permitir administrar despesas recorrentes da academia.

**Funcionalidades esperadas:**

- Listar e pesquisar despesas fixas.
- Disponibilizar cadastro.
- Registrar nome, valor e status.
- Definir recorrência.
- Permitir recorrências de 1 dia, 7 dias, 1 mês, 3 meses, 6 meses e 1 ano.
- Permitir visualizar despesas.
- Disponibilizar exclusão.

---

## RF14 - Integração Financeira com Pagar.me

**Descrição:** O sistema deve disponibilizar funcionalidades relacionadas à integração de pagamentos por meio da plataforma Pagar.me.

**Funcionalidades esperadas:**

- Apresentar informações de recebimentos, saldo e recebíveis.
- Consultar transações e assinaturas.
- Consultar previsão de recebimentos.
- Disponibilizar acesso a extratos.
- Disponibilizar criação de cobrança.
- Disponibilizar criação de link de pagamento.
- Disponibilizar configurações da integração.
- Disponibilizar solicitação de saque.


---

## RF15 - Relatórios

**Descrição:** O sistema deve permitir a consulta e geração de relatórios referentes às diferentes áreas da academia.

**Funcionalidades esperadas:**

- Permitir selecionar o tipo de relatório.
- Definir período.
- Adaptar filtros conforme o tipo selecionado.
- Disponibilizar relatórios de:
  - Avaliações;
  - Clientes;
  - Colaboradores;
  - Matrículas;
  - Contas a Receber;
  - Contas a Pagar;
  - Caixas.
- Permitir filtros específicos conforme o relatório.
- Disponibilizar formatos normal e detalhado quando aplicável.
- Disponibilizar ação para geração.

---

## RF16 - Gestão de Prospecção Comercial

**Descrição:** O sistema deve permitir administrar potenciais clientes por meio de um funil de prospecção.

**Funcionalidades esperadas:**

- Listar e pesquisar leads.
- Filtrar por estágio.
- Disponibilizar cadastro de lead.
- Manter nome, e-mail e telefone.
- Definir estágio.
- Utilizar os estágios:
  - Novo Contato;
  - Interessado;
  - Fez Aula Experimental;
  - Proposta;
  - Fechado.
- Permitir visualizar leads.
- Disponibilizar exclusão.

---

## RF17 - Gestão de Planos e Modelos de Contrato

**Descrição:** O sistema deve permitir administrar planos comerciais e modelos utilizados em contratos.

**Funcionalidades esperadas:**

- Listar e pesquisar planos.
- Disponibilizar cadastro.
- Relacionar plano a grupo.
- Definir tipo de cobrança.
- Permitir Mensalidade recorrente, Diária e Período fixo.
- Definir parcelas.
- Definir valor mensal e valor de matrícula.
- Definir utilização de personal.
- Definir quantidade de dependentes.
- Associar benefícios.
- Disponibilizar integração com Pagar.me.
- Administrar modelos de contrato.
- Permitir edição formatada.
- Permitir pré-visualização.
- Definir status do modelo.

---

## RF18 - Gestão de Tipos de Pagamento e Bandeiras

**Descrição:** O sistema deve permitir configurar os meios de pagamento utilizados pela academia.

**Funcionalidades esperadas:**

- Administrar tipos de pagamento.
- Definir nome e status.
- Diferenciar débito e crédito.
- Definir utilização de bandeira.
- Definir pagamento pelo sistema.
- Administrar bandeiras.
- Configurar taxa adicional e taxa de débito.
- Configurar parcelas.
- Configurar multiplicação da taxa adicional por mês.


---

## RF19 - Gestão de Colaboradores

**Descrição:** O sistema deve permitir administrar os colaboradores da academia.

**Funcionalidades esperadas:**

- Listar e pesquisar colaboradores.
- Disponibilizar cadastro.
- Manter dados pessoais, documentos e informações profissionais.
- Manter contato e endereço.
- Manter informações de biometria.
- Relacionar colaborador a funções.
- Disponibilizar configurações de acesso.
- Permitir os perfis observados:
  - Admin;
  - Normal;
  - Sem login.
- Disponibilizar visualização e exclusão.


---

## RF20 - Gestão de Funções e Permissões

**Descrição:** O sistema deve permitir administrar funções de colaboradores e controlar permissões de acesso.

**Funcionalidades esperadas:**

- Listar e pesquisar funções.
- Disponibilizar cadastro.
- Definir tipo de funcionário.
- Identificar funções relacionadas a Personal e Avaliador.
- Disponibilizar matriz de permissões.
- Permitir definir permissões por módulo e ação.
- Relacionar funções aos colaboradores.


---

## RF21 - Gestão de Fornecedores e Tipos de Documentos

**Descrição:** O sistema deve permitir administrar fornecedores e tipos de documentos utilizados nos processos da academia.

**Funcionalidades esperadas:**

- Listar e pesquisar fornecedores.
- Disponibilizar cadastro.
- Diferenciar pessoa física e jurídica.
- Manter informações cadastrais, contato e endereço.
- Administrar tipos de documentos.
- Definir aplicação do documento.
- Permitir aplicação relacionada a Conta/Fornecedor e Colaborador.
- Disponibilizar os documentos nas funcionalidades relacionadas.

---

## RF22 - Gestão de Atividades, Pontuação e Produtos

**Descrição:** O sistema deve permitir administrar programas de pontuação e atividades destinadas aos clientes.

**Funcionalidades esperadas:**

- Administrar atividades.
- Definir pontuação e descrição.
- Criar programas de pontuação.
- Definir período do programa.
- Associar atividades e participantes.
- Consultar ranking.
- Consultar pontos.
- Administrar pedidos de tarefa.
- Relacionar produtos a programas.
- Administrar produtos para Venda ou Pontuação/resgate.
- Manter preço ou valor correspondente.

---

## RF23 - Gestão de Enquetes

**Descrição:** O sistema deve permitir criar e administrar enquetes destinadas aos usuários.

**Funcionalidades esperadas:**

- Listar e pesquisar enquetes.
- Criar nova enquete.
- Registrar pergunta.
- Registrar alternativas.
- Permitir adicionar respostas.
- Definir status.
- Permitir visualização.
- Disponibilizar exclusão.

---

## RF24 - Gestão de Anamnese

**Descrição:** O sistema deve permitir administrar e aplicar fichas de anamnese aos clientes.

**Funcionalidades esperadas:**

- Consultar fichas.
- Iniciar aplicação para um aluno.
- Administrar modelos.
- Pré-visualizar modelos.
- Criar modelos compostos por perguntas.
- Permitir ordenação das perguntas.
- Definir perguntas obrigatórias ou opcionais.
- Administrar categorias.
- Definir nome, status, ícone e cor.
- Administrar perguntas.
- Definir número/ordem da pergunta.
- Definir tipo de resposta.
- Disponibilizar os tipos:
  - Sim e Não;
  - Sim, Não e Não Sei;
  - Se Sim, qual?.



---

## RF25 - Inteligência e Automação

**Descrição:** O sistema deve disponibilizar funcionalidades de inteligência e automação relacionadas aos dados da academia.

**Funcionalidades esperadas:**

- Apresentar automações disponíveis.
- Diferenciar automações ativas e indisponíveis/futuras.
- Disponibilizar configuração.
- Disponibilizar execução manual.
- Disponibilizar consulta de resultados.
- Permitir consulta pelos períodos:
  - Hoje;
  - Últimos 7 dias;
  - Últimos 30 dias;
  - Últimos 90 dias.
- Informar ausência de resultados ou execuções.


---

## RF26 - Configurações Gerais e Aplicativo

**Descrição:** O sistema deve permitir administrar configurações gerais da academia e funcionalidades destinadas ao aplicativo utilizado pelos alunos.

**Funcionalidades esperadas:**

- Disponibilizar configurações gerais da academia.
- Configurar controle de presença por Biometria, Check-in ou Ambos.
- Configurar critérios de ausência.
- Configurar multa e juros por atraso.
- Configurar comportamento relacionado à anamnese.
- Configurar dispositivos biométricos.
- Configurar parâmetros de avaliação.
- Configurar mensagens de aniversário.
- Configurar pagamento online e integrações.
- Configurar elementos visuais.
- Administrar modelos de ficha de treino.
- Disponibilizar área administrativa do aplicativo.
- Consultar notificações, postagens e denúncias.
- Permitir composição e pré-visualização de notificações.
- Disponibilizar envio de avisos aos alunos.


---

## RF27 - Autenticação do Usuário

**Descrição:** O sistema deve disponibilizar uma página de acesso que permita a identificação do usuário para utilização das funcionalidades restritas do SiFit.

**Funcionalidades esperadas:**

- Disponibilizar uma página pública de autenticação.
- Apresentar campo **Login** para identificação do usuário.
- Apresentar campo **Senha** para inserção da credencial de acesso.
- Apresentar a senha utilizando campo protegido, sem exibir diretamente os caracteres digitados.
- Disponibilizar a opção **Manter conectado**.
- Disponibilizar a ação **Entrar** para tentativa de acesso ao sistema.
- Disponibilizar acesso à funcionalidade **Esqueci minha senha**.
- Permitir que o mecanismo de autenticação utilize uma conta previamente existente.
- Encaminhar usuários autenticados às áreas restritas do sistema, comportamento a ser confirmado em teste posterior.
- Impedir ou rejeitar autenticação com credenciais inválidas, comportamento a ser confirmado em teste posterior.
- Apresentar tratamento adequado quando os campos necessários não forem informados, comportamento a ser confirmado em teste posterior.


