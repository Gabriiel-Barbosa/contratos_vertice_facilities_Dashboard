# VÉRTICE FACILITIES

### Estudo de caso \| Estruturação de um controle de Gestão de Contratos em Excel

> **Case demonstrativo --- empresa, clientes, fornecedores, contratos,
> pessoas e oportunidades são fictícios.**\
> Os preços foram construídos como premissas plausíveis para uma
> prestadora de serviços de facilities com atuação na Bahia, calibradas
> por referências públicas de contratações brasileiras. Não são
> cotações, propostas comerciais nem preços oficiais aplicáveis a
> qualquer contratação.

------------------------------------------------------------------------

::: {align="center"}
# VÉRTICE

## FACILITIES & SERVIÇOS INTEGRADOS

**Gestão que conecta pessoas, operações e resultados.**
:::

------------------------------------------------------------------------

## 1. Visão geral do estudo de caso

A **Vértice Facilities Ltda.** é uma empresa fictícia sediada em
Salvador/BA, especializada na prestação de serviços terceirizados e
apoio à infraestrutura de organizações públicas e privadas.

A empresa atua em contratos de limpeza e conservação, portaria e
controle de acesso, vigilância patrimonial, jardinagem, manutenção
predial e serviços de apoio operacional.

Após ampliar sua carteira de clientes, a Vértice passou a administrar
contratos com diferentes modelos de cobrança, vigências, reajustes,
obrigações, níveis de serviço, unidades atendidas e condições
comerciais. As informações estão distribuídas entre arquivos Excel
individuais, PDFs, e-mails e controles mantidos por gestores de
contrato.

A diretoria identificou que não possui uma visão consolidada e confiável
para responder rapidamente a perguntas como:

-   Quanto a empresa possui em contratos ativos e qual é a receita
    mensal recorrente contratada?
-   Quais contratos vencem nos próximos 30, 60, 90 e 180 dias?
-   Quais contratos precisam de reajuste, repactuação ou renovação?
-   Qual é a margem estimada por contrato, cliente, serviço e unidade?
-   Quais contratos estão com risco de perda, baixa rentabilidade ou
    descumprimento?
-   Quais oportunidades de licitação, BID ou concorrência estão
    previstas?
-   Quais propostas foram ganhas, perdidas, desclassificadas ou ainda
    estão em análise?
-   Qual receita futura está no pipeline comercial e qual a
    probabilidade de conversão?
-   Quais contratos foram encerrados e por que a empresa perdeu aquela
    receita?
-   Quais obrigações documentais e operacionais estão pendentes?

A necessidade não é simplesmente criar uma planilha para guardar datas.
A empresa precisa de um **controle gerencial de contratos**, capaz de
reunir informações comerciais, financeiras e operacionais e apoiar
decisões de renovação, precificação, priorização de oportunidades e
alocação de recursos.

### Objetivo do projeto

Desenvolver, utilizando Microsoft Excel, um modelo integrado de controle
e acompanhamento do ciclo de vida contratual, desde a identificação de
uma oportunidade comercial até a execução, renovação ou encerramento do
contrato.

### Resultado esperado

Uma pasta de trabalho que permita à diretoria e aos gestores:

1.  Visualizar a carteira de contratos e sua evolução.
2.  Antecipar vencimentos, reajustes e decisões de renovação.
3.  Acompanhar receita contratada, custos estimados e margem de
    contribuição.
4.  Monitorar obrigações, ocorrências e desempenho dos contratos.
5.  Gerenciar oportunidades futuras, BID, RFP e licitações.
6.  Registrar contratos perdidos e analisar motivos de perda.
7.  Priorizar ações com base em risco, valor financeiro e prazo.

------------------------------------------------------------------------

## 2. Perfil da empresa fictícia

  ---------------------------------------------------------------------
  Informação                         Descrição
  ---------------------------------- ----------------------------------
  Razão social                       Vértice Facilities Ltda.

  Nome fantasia                      Vértice Facilities

  Sede                               Salvador --- Bahia

  Área de atuação                    Facilities e serviços
                                     terceirizados

  Abrangência                        Salvador, Região Metropolitana e
                                     interior da Bahia

  Porte para o case                  Empresa de médio porte

  Colaboradores operacionais         420

  Colaboradores administrativos      28

  Carteira de clientes               Organizações públicas e privadas

  Modelo comercial                   Contratos continuados, postos de
                                     serviço, escopo fechado e serviços
                                     sob demanda

  Principais clientes                Hospitais, centros empresariais,
                                     indústrias, instituições de ensino
                                     e órgãos públicos
  ---------------------------------------------------------------------

### Portfólio de serviços

  -----------------------------------------------------------------------
  Segmento                Descrição               Modelo comercial comum
  ----------------------- ----------------------- -----------------------
  Limpeza e conservação   Limpeza predial,        Postos, equipes ou área
                          higienização,           atendida
                          conservação e apoio     

  Portaria e controle de  Recepção, controle de   Postos 12x36 ou 44
  acesso                  entrada e orientação    horas semanais

  Vigilância patrimonial  Vigilância armada ou    Postos por jornada
                          desarmada               

  Jardinagem              Conservação de jardins  Equipe fixa ou visitas
                          e áreas externas        programadas

  Manutenção predial      Manutenção preventiva e Equipe residente,
                          corretiva               franquia de horas ou
                                                  chamado

  Apoio operacional       Serviços auxiliares e   Postos, equipes ou
                          suporte às instalações  demanda
  -----------------------------------------------------------------------

**Atenção:** vigilância patrimonial é uma atividade regulada e exige
contratação de empresa e profissionais habilitados, observância das
normas aplicáveis e documentação específica. O case não substitui
análise jurídica, trabalhista, tributária ou regulatória.

------------------------------------------------------------------------

## 3. Diagnóstico: cenário atual e limitações

A empresa utiliza planilhas independentes por área. O Comercial
acompanha oportunidades; o Financeiro controla faturamento e pagamentos;
Operações acompanha postos e ocorrências; e os gestores mantêm seus
próprios calendários de vencimentos.

### Principais problemas identificados

  -----------------------------------------------------------------------
  Dimensão                Situação atual          Consequência para a
                                                  gestão
  ----------------------- ----------------------- -----------------------
  Cadastro                Dados espalhados em     Duplicidade e
                          arquivos                divergência de
                                                  informações

  Vigência                Datas controladas       Risco de perder prazos
                          manualmente             de renovação

  Reajustes               Índices e datas sem     Reajustes não
                          calendário único        solicitados ou
                                                  aplicados fora do prazo

  Financeiro              Valor contratual        Dificuldade para
                          separado do custo       avaliar margem
                          operacional             

  Operação                Ocorrências em          Baixa visibilidade do
                          controles isolados      desempenho

  Comercial               Oportunidades sem funil Dificuldade para prever
                          padronizado             receita futura

  BID/licitações          Editais e prazos        Risco de perder prazos
                          acompanhados por e-mail e documentos

  Encerramentos           Motivos de perda não    Ausência de aprendizado
                          padronizados            comercial

  Gestão                  Relatórios preparados   Decisões tardias e
                          manualmente             esforço recorrente
  -----------------------------------------------------------------------

### Limitação central do Excel

O Excel será utilizado como ferramenta de organização, análise e
acompanhamento gerencial. Entretanto, **não deve ser tratado como um
sistema corporativo completo de gestão contratual**.

As principais limitações previstas são:

-   **Concorrência de edição:** múltiplos usuários alterando a mesma
    base podem gerar conflitos, especialmente sem ambiente colaborativo
    bem configurado.
-   **Governança e rastreabilidade:** o histórico de alterações,
    aprovações e evidências não tem a robustez de um sistema com trilha
    de auditoria.
-   **Controle de acesso:** proteger células ou abas não equivale a
    permissões granulares por usuário, contrato ou unidade.
-   **Automação de alertas:** alertas dependem de abertura do arquivo,
    rotinas auxiliares ou integrações disponíveis no ambiente
    corporativo.
-   **Documentos e anexos:** armazenar PDFs e evidências dentro da pasta
    de trabalho aumenta o tamanho e dificulta a manutenção. O
    recomendado é guardar links para repositório corporativo autorizado.
-   **Escalabilidade:** grandes volumes de registros, fórmulas complexas
    e múltiplas consultas podem reduzir o desempenho.
-   **Integração:** conexão com ERP, financeiro, folha, compras e
    sistemas de operação exige desenho técnico e governança.
-   **Segurança:** planilhas podem ser copiadas, encaminhadas ou
    alteradas fora do fluxo previsto.
-   **Processos críticos:** aprovações formais, assinatura eletrônica,
    gestão documental e obrigações legais devem permanecer nos sistemas
    e processos oficiais da empresa.

**Decisão de desenho:** o Excel será o MVP de controle e inteligência
gerencial. O arquivo não será o repositório oficial dos contratos
assinados, não substituirá o ERP nem será usado para aprovar
juridicamente propostas ou aditivos.

------------------------------------------------------------------------

## 4. Escopo funcional do controle

A pasta de trabalho deverá contemplar o ciclo de vida completo:

1.  **Prospecção:** identificação de clientes, oportunidades e possíveis
    concorrências.
2.  **Qualificação:** avaliação de aderência, capacidade, documentação,
    prazo e viabilidade.
3.  **BID/RFP/licitação:** controle de edital, visita técnica,
    esclarecimentos, proposta, sessão e resultado.
4.  **Negociação:** registro de preço ofertado, revisões, premissas e
    aprovações internas.
5.  **Contratação:** cadastro do instrumento, objeto, valor, vigência,
    responsáveis e documentos.
6.  **Mobilização:** planejamento de equipe, postos, insumos,
    equipamentos e início da operação.
7.  **Execução:** acompanhamento financeiro, operacional, obrigações e
    ocorrências.
8.  **Reajuste/repactuação:** controle de datas-base, índices,
    convenções coletivas e solicitações.
9.  **Renovação:** análise de desempenho, margem, riscos e interesse
    comercial.
10. **Encerramento:** baixa, motivo, transição, pendências e análise da
    receita perdida.

### Fora do escopo do Excel

-   Assinatura eletrônica de contratos.
-   Parecer jurídico automático.
-   Cálculo oficial de folha ou encargos trabalhistas.
-   Emissão fiscal e faturamento oficial.
-   Controle de ponto dos colaboradores.
-   Gestão de documentos sigilosos ou dados pessoais sensíveis.
-   Aprovação formal de despesas ou propostas.
-   Substituição de sistemas oficiais de compras públicas ou portais de
    licitação.

------------------------------------------------------------------------

## 5. Premissas comerciais e financeiras

Os valores abaixo foram construídos para simular contratos de serviços
continuados na Bahia. O preço real depende de convenção coletiva
vigente, salários, benefícios, adicionais, tributos, regime tributário,
produtividade, materiais, equipamentos, localidade, jornada, exigências
do contratante, riscos e composição da planilha de custos.

### Referências públicas utilizadas para calibragem

-   A Polícia Federal na Bahia publicou contrato de limpeza e
    conservação, lavagem de veículos e jardinagem com valor mensal de
    **R\$ 174.674,61**, em vigência de 2025 a 2030. É uma referência de
    contrato de escopo amplo, não um preço unitário universal. [Contrato
    nº 10/2025 ---
    PF/BA](https://www.gov.br/pf/pt-br/assuntos/licitacoes/2025/bahia/contratos/contrato-no-10-2025-sr-pf-ba.pdf/view).
-   O CEMADEN publicou, em 2025, valores mensais de vigilância desarmada
    12x36 entre aproximadamente **R\$ 12,9 mil e R\$ 14,1 mil por
    posto**, conforme turno e especificação. [Contrato 01/2025 ---
    CEMADEN](https://www.gov.br/cemaden/pt-br/acesso-a-informacao/licitacoes-e-contratos-1/contratos-1/contrato-01-2025).
-   Em 2026, outro contrato publicado pelo CEMADEN apresenta valores
    mensais de vigilância desarmada 12x36 de aproximadamente **R\$ 13,5
    mil a R\$ 17,2 mil**, conforme turno e especificação. [Contrato
    06/2026 ---
    CEMADEN](https://www.gov.br/cemaden/pt-br/acesso-a-informacao/licitacoes-e-contratos-1/contratos-1/contrato-06-2026).
-   Uma contratação divulgada para Salvador em 2026 apresenta itens de
    vigilância com valores estimados que variam conforme jornada, turno
    e modalidade. [Referência de contratação na
    Bahia](https://licitachei.iagenes.com.br/licitacao/3587905).

Essas referências servem apenas como **balizadores de ordem de
grandeza**. Não se deve comparar diretamente contratos com escopos,
jornadas, localidades, quantidades ou composições diferentes.

### Tabela de premissas para o case

  ---------------------------------------------------------------------
  Serviço        Unidade de            Faixa mensal   Premissa usada no
                 cobrança             demonstrativa                case
  -------------- -------------- ------------------- -------------------
  Auxiliar de    Posto/mês         R\$ 5.800--7.200           R\$ 6.450
  limpeza 44h                                       

  Encarregado de Posto/mês         R\$ 7.800--9.800           R\$ 8.900
  limpeza 44h                                       

  Portaria 12x36 Posto/mês        R\$ 9.500--12.500          R\$ 10.900

  Vigilância     Posto/mês       R\$ 12.500--16.500          R\$ 14.200
  desarmada                                         
  12x36                                             

  Vigilância     Posto/mês       R\$ 14.000--18.000          R\$ 16.300
  armada 12x36                                      

  Jardineiro 44h Posto/mês         R\$ 6.000--7.800           R\$ 6.900

  Oficial de     Posto/mês        R\$ 7.500--10.500           R\$ 8.900
  manutenção 44h                                    

  Supervisor     Posto/mês        R\$ 8.500--11.500           R\$ 9.800
  operacional                                       
  44h                                               
  ---------------------------------------------------------------------

**Importante:** as faixas de limpeza, portaria, jardinagem, manutenção e
supervisão são premissas de simulação do case, não preços oficiais
obtidos em pesquisa de mercado. Os valores de vigilância foram
aproximados com apoio das referências públicas acima. Para uma proposta
comercial real, seria indispensável elaborar planilha de custos e
formação de preços atualizada.

### Premissas de análise financeira

Para permitir análises gerenciais, o case utiliza:

-   Receita contratual mensal: valor mensal previsto no instrumento,
    antes de ajustes extraordinários.
-   Custo direto estimado: mão de obra, benefícios, encargos, materiais,
    equipamentos e demais custos atribuíveis ao contrato.
-   Margem de contribuição estimada: receita mensal menos custo direto
    estimado.
-   Margem percentual estimada: margem de contribuição dividida pela
    receita mensal.
-   Reajuste: percentual hipotético informado no cadastro, sujeito à
    cláusula contratual, índice aplicável, data-base e formalização.
-   Receita anualizada: valor mensal multiplicado por 12, apenas quando
    o contrato tiver recorrência mensal.
-   Valor total contratual: valor global informado no contrato ou
    estimativa de receita durante a vigência, conforme regra explicitada
    no registro.

Não confundir receita contratada com receita faturada, recebida ou
reconhecida contabilmente.

------------------------------------------------------------------------

## 6. Carteira de contratos vigentes

**Data-base do estudo: 01/11/2026.**\
Todos os clientes, números de contrato, valores e condições desta
carteira são fictícios. Os valores mensais foram definidos para compor
uma carteira de porte médio e permitir análises no Excel.

  ----------------------------------------------------------------------------------------------------------------------
  ID       Cliente         Serviço       Localidade   Início       Fim             Valor      Custo     Margem Status
           fictício        principal                                              mensal     direto     mensal 
                                                                                           estimado   estimada 
  -------- --------------- ------------- ------------ ------------ ------------ -------- ---------- ---------- ---------
  CT-001   Hospital Santa  Limpeza       Salvador     01/03/2025   28/02/2027        R\$ R\$ 77.850  R\$ 8.650 Vigente
           Aurora          hospitalar                                             86.500                       

  CT-002   Centro          Limpeza e     Salvador     01/06/2025   31/05/2027        R\$ R\$ 37.664  R\$ 5.136 Vigente
           Empresarial     conservação                                            42.800                       
           Atlântico                                                                                           

  CT-003   Indústria Baía  Portaria e    Camaçari     01/01/2026   31/12/2026        R\$ R\$ 28.449  R\$ 4.251 Vigente
           Norte           controle de                                            32.700                       
                           acesso                                                                              

  CT-004   Hospital Santa  Vigilância    Salvador     01/04/2025   31/03/2027        R\$ R\$ 51.120  R\$ 5.680 Vigente
           Aurora          desarmada                                              56.800                       

  CT-005   Condomínio      Jardinagem    Lauro de     01/08/2025   31/07/2027        R\$ R\$ 11.730  R\$ 2.070 Vigente
           Parque das                    Freitas                                  13.800                       
           Águas                                                                                               

  CT-006   Universidade    Limpeza e     Salvador     01/02/2026   31/01/2027        R\$ R\$ 61.560  R\$ 6.840 Vigente
           Metropolitana   conservação                                            68.400                       
           da Bahia                                                                                            

  CT-007   Centro          Portaria      Candeias     01/09/2025   31/08/2027        R\$ R\$ 19.402  R\$ 2.398 Vigente
           Logístico       12x36                                                  21.800                       
           Candeias                                                                                            

  CT-008   Rede Clínica    Limpeza e     Salvador     01/05/2026   30/04/2028        R\$ R\$ 33.088  R\$ 4.512 Vigente
           Vida Plena      apoio                                                  37.600                       

  CT-009   Shopping Costa  Limpeza e     Salvador     01/07/2025   30/06/2027        R\$ R\$ 66.305  R\$ 8.195 Vigente
           Azul            conservação                                            74.500                       

  CT-010   Fábrica         Manutenção    Simões Filho 01/11/2025   31/10/2027        R\$ R\$ 25.926  R\$ 3.874 Vigente
           Recôncavo       predial                                                29.800                       

  CT-011   Hospital        Limpeza       Santo        01/01/2026   31/12/2027        R\$ R\$ 83.904  R\$ 7.296 Vigente
           Regional do     hospitalar    Antônio de                               91.200                       
           Recôncavo                     Jesus                                                                 

  CT-012   Edifício        Portaria e    Salvador     01/06/2026   31/05/2028        R\$ R\$ 16.443  R\$ 2.457 Vigente
           Empresarial     recepção                                               18.900                       
           Farol                                                                                               

  CT-013   Polo Industrial Vigilância    Simões Filho 01/10/2025   30/09/2027        R\$ R\$ 38.340  R\$ 4.260 Vigente
           Aratu           desarmada                                              42.600                       

  CT-014   Colégio         Jardinagem e  Lauro de     01/02/2026   31/01/2027        R\$  R\$ 8.526  R\$ 1.274 Vigente
           Horizonte       conservação   Freitas                                   9.800                       

  CT-015   Centro de       Limpeza e     Camaçari     01/04/2026   31/03/2028        R\$ R\$ 43.830  R\$ 4.870 Vigente
           Distribuição    apoio                                                  48.700                       
           Litoral         operacional                                                                         

  CT-016   Hospital São    Vigilância    Salvador     01/09/2026   31/08/2027        R\$ R\$ 25.560  R\$ 2.840 Vigente
           Gabriel         desarmada                                              28.400                       
  ----------------------------------------------------------------------------------------------------------------------

### Fotografia consolidada da carteira vigente

Com base nos 16 contratos demonstrativos listados acima:

  Indicador                                  Valor calculado
  ---------------------------------------- -----------------
  Contratos vigentes                                      16
  Receita mensal contratada                      R\$ 704.300
  Receita anualizada                           R\$ 8.451.600
  Custo direto mensal estimado                   R\$ 629.697
  Margem de contribuição mensal estimada          R\$ 74.603
  Margem de contribuição estimada                     10,59%

Esses totais são cálculos sobre a carteira sintética apresentada. Não
representam faturamento, lucro líquido nem desempenho de uma empresa
real.

### Leitura gerencial da carteira

A diretoria deve conseguir visualizar:

-   Receita mensal contratada da carteira vigente.
-   Receita anualizada estimada.
-   Custo direto mensal estimado.
-   Margem de contribuição estimada, em reais e percentual.
-   Quantidade de contratos por segmento e localidade.
-   Concentração de receita por cliente.
-   Contratos com margem abaixo do limite definido pela diretoria.
-   Contratos com vencimento próximo.
-   Contratos sem reajuste ou com reajuste pendente.
-   Contratos com ocorrências ou obrigações críticas.

**Atenção:** a margem apresentada é uma estimativa didática. Não inclui
necessariamente despesas administrativas, comerciais, financeiras,
tributos sobre faturamento ou rateios corporativos. Portanto, não deve
ser chamada de lucro líquido.

------------------------------------------------------------------------

## 7. Contratos encerrados, perdidos ou não renovados

O histórico de contratos encerrados é essencial para entender a evolução
da carteira e evitar que a empresa avalie seu desempenho apenas pelos
contratos vigentes.

Nesta base, diferenciar:

-   **Encerrado:** contrato chegou ao fim da vigência ou teve
    encerramento formal.
-   **Não renovado:** cliente decidiu não prorrogar ou a empresa optou
    por não continuar.
-   **Perdido em concorrência:** a Vértice participou de uma disputa e
    não foi vencedora.
-   **Rescindido:** encerramento antecipado conforme condições
    contratuais.
-   **Descontinuado:** oportunidade ou serviço deixou de ser ofertado.

### Histórico demonstrativo

  -----------------------------------------------------------------------------------------------------------------
  ID       Cliente      Serviço      Período          Valor Data de        Motivo          Responsabilidade
           fictício                                  mensal encerramento   registrado      predominante
                                                    perdido                                
  -------- ------------ ------------ ------------ --------- -------------- --------------- ------------------------
  HX-001   Hospital Boa Limpeza      2023--2025         R\$ 31/12/2025     Concorrente     Comercial/preço
           Esperança    hospitalar                   62.000                apresentou      
                                                                           preço inferior  

  HX-002   Condomínio   Portaria     2024--2025         R\$ 30/11/2025     Cliente         Estratégica
           Solar do                                  18.500                internalizou a  
           Parque                                                          operação        

  HX-003   Centro       Limpeza      2024--2026         R\$ 31/03/2026     Insatisfação    Operacional
           Médico                                    31.800                com indicadores 
           Aliança                                                         de qualidade    

  HX-004   Indústria    Jardinagem   2023--2025         R\$ 31/08/2025     Redução de      Cliente/escopo
           Vale Verde                                11.200                escopo pelo     
                                                                           cliente         

  HX-005   Edifício     Manutenção   2024--2026         R\$ 30/06/2026     Margem          Estratégica/financeira
           Comercial    predial                      24.500                insuficiente;   
           Prisma                                                          empresa optou   
                                                                           por não renovar 

  HX-006   Hospital das Vigilância   2023--2025         R\$ 31/10/2025     Perda em nova   Comercial
           Palmeiras                                 39.500                concorrência    

  HX-007   Faculdade    Limpeza      2024--2025         R\$ 31/12/2025     Encerramento da Cliente/estrutura
           Novo Saber                                27.000                unidade         
                                                                           atendida        

  HX-008   Galpão       Portaria     2025--2026         R\$ 31/07/2026     Falhas de       Operacional
           Industrial                                16.400                cobertura de    
           União                                                           postos          
  -----------------------------------------------------------------------------------------------------------------

### Campos adicionais recomendados para a análise de perdas

-   Valor mensal perdido.
-   Valor anualizado perdido.
-   Receita total estimada não renovada.
-   Tempo de relacionamento.
-   Motivo primário e secundário da perda.
-   Concorrente vencedor, quando conhecido.
-   Preço da Vértice e preço vencedor, quando disponível.
-   Nota de desempenho operacional.
-   Margem estimada antes do encerramento.
-   Responsável comercial.
-   Plano de ação para evitar recorrência.

**Indicador importante:** receita mensal perdida no período, segmentada
por motivo. Não somar valores mensais e valores globais sem identificar
a unidade de medida.

------------------------------------------------------------------------

## 8. Contratos futuros e renovações previstas

Esta visão não representa contratos já assinados. São contratos vigentes
com eventos futuros de renovação ou oportunidades de prorrogação a serem
avaliadas.

  ------------------------------------------------------------------------------------------------
  ID       Cliente         Contrato   Vencimento      Valor Data-limite   Situação da Próxima ação
                           atual                     mensal interna para  renovação   
                                                      atual decisão                   
  -------- --------------- ---------- ------------ -------- ------------- ----------- ------------
  RN-001   Indústria Baía  CT-003     31/12/2026        R\$ 01/12/2026    Em          Revisar
           Norte                                     32.700               avaliação   margem e
                                                                                      capacidade

  RN-002   Colégio         CT-014     31/01/2027        R\$ 02/01/2027    Em          Consultar
           Horizonte                                  9.800               avaliação   interesse do
                                                                                      cliente

  RN-003   Universidade    CT-006     31/01/2027        R\$ 02/01/2027    Em          Preparar
           Metropolitana                             68.400               avaliação   proposta de
                                                                                      renovação

  RN-004   Hospital Santa  CT-001     28/02/2027        R\$ 30/12/2026    Potencial   Analisar
           Aurora                                    86.500                           reajuste e
                                                                                      desempenho

  RN-005   Hospital Santa  CT-004     31/03/2027        R\$ 30/01/2027    Potencial   Avaliar
           Aurora                                    56.800                           condições
                                                                                      comerciais

  RN-006   Centro          CT-002     31/05/2027        R\$ 31/03/2027    Potencial   Iniciar
           Empresarial                               42.800                           tratativa
           Atlântico                                                                  com cliente
  ------------------------------------------------------------------------------------------------

### Regras de acompanhamento

-   180 dias antes do vencimento: incluir na agenda estratégica.
-   120 dias antes: iniciar análise de desempenho, margem e riscos.
-   90 dias antes: definir recomendação de renovar, renegociar ou
    encerrar.
-   60 dias antes: formalizar proposta ou plano de transição, conforme o
    caso.
-   30 dias antes: acompanhar decisão e pendências críticas.

Esses prazos são regras internas hipotéticas do case. A antecedência
real deve respeitar o contrato, a legislação aplicável e os
procedimentos do cliente.

### Status possíveis

`Não iniciado` · `Em análise` · `Em negociação` · `Proposta enviada` ·
`Renovado` · `Não renovado` · `Encerramento planejado`

------------------------------------------------------------------------

## 9. Pipeline de oportunidades, BID, RFP e licitações

A empresa precisa acompanhar oportunidades que ainda não se converteram
em contratos. Essa base deve permitir que a diretoria enxergue a receita
potencial, o estágio comercial, as datas críticas e a probabilidade de
conversão.

### Oportunidades futuras e em andamento

  -------------------------------------------------------------------------------------------------------------------------------------------
  ID       Oportunidade      Cliente/órgão   Serviço           Valor Valor anual Abertura     Prazo de       Probabilidade Etapa
           fictícia          fictício                         mensal estimado    prevista     proposta                     
                                                            estimado                                                       
  -------- ----------------- --------------- ------------ ---------- ----------- ------------ ------------ --------------- ------------------
  OP-001   Limpeza de        Rede Hospitalar Limpeza             R\$ R\$         15/11/2026   30/11/2026               35% Mapeamento
           complexo          São Lucas       hospitalar      115.000 1.380.000                                             
           hospitalar                                                                                                      

  OP-002   Vigilância de     Grupo           Vigilância   R\$ 68.000 R\$ 816.000 20/11/2026   05/12/2026               25% Pré-qualificação
           unidades          Empresarial                                                                                   
           administrativas   Costa                                                                                         

  OP-003   Facilities de     Logística       Limpeza,     R\$ 92.000 R\$         01/12/2026   15/12/2026               40% Levantamento de
           centro logístico  Nordeste S.A.   portaria e              1.104.000                                             escopo
                                             manutenção                                                                    

  OP-004   Conservação de    Parque          Jardinagem   R\$ 18.000 R\$ 216.000 10/12/2026   20/12/2026               50% Cotação
           áreas externas    Industrial                                                                                    
                             Recôncavo                                                                                     

  OP-005   Portaria e        Torre           Portaria     R\$ 27.000 R\$ 324.000 15/01/2027   30/01/2027               30% Prospecção
           recepção          Empresarial                                                                                   
           corporativa       Bahia                                                                                         

  OP-006   Manutenção        Hospital        Manutenção   R\$ 46.000 R\$ 552.000 20/01/2027   10/02/2027               20% Mapeamento
           predial           Regional do                                                                                   
           continuada        Litoral                                                                                       

  OP-007   Limpeza e         Instituto       Limpeza      R\$ 73.000 R\$ 876.000 01/02/2027   20/02/2027               45% Visita técnica
           conservação de    Superior do                                                                                   
           campus            Recôncavo                                                                                     

  OP-008   Vigilância        Complexo        Vigilância   R\$ 81.000 R\$ 972.000 15/02/2027   05/03/2027               25% Pré-qualificação
           patrimonial de    Industrial                                                                                    
           indústria         Aratu                                                                                         
  -------------------------------------------------------------------------------------------------------------------------------------------

**Nota:** os nomes, datas e oportunidades são inteiramente fictícios. As
datas futuras representam o calendário simulado do estudo, não editais
publicados ou concorrências reais.

### Etapas padronizadas do funil

1.  Prospecção identificada.
2.  Oportunidade qualificada.
3.  Edital/RFP/BID publicado ou recebido.
4.  Análise de aderência.
5.  Visita técnica e esclarecimentos.
6.  Formação de preço.
7.  Aprovação interna.
8.  Proposta enviada.
9.  Disputa/negociação.
10. Em julgamento.
11. Ganha.
12. Perdida.
13. Desclassificada.
14. Cancelada ou suspensa.

### Campos obrigatórios por BID ou licitação

  Campo                  Finalidade
  ---------------------- ---------------------------------------------
  ID da oportunidade     Identificador único
  Cliente/órgão          Contratante potencial
  Modalidade             BID privado, RFP, pregão, concorrência etc.
  Número do processo     Identificação oficial, quando houver
  Objeto                 Descrição resumida do serviço
  Local de execução      Município e unidades
  Valor estimado         Referência do cliente ou edital
  Valor proposto         Preço submetido pela Vértice
  Custo estimado         Custo de execução calculado
  Margem prevista        Resultado estimado da proposta
  Data de publicação     Início do acompanhamento
  Visita técnica         Data e obrigatoriedade
  Esclarecimentos        Prazo para questionamentos
  Entrega da proposta    Data e hora-limite
  Sessão/disputa         Data e hora
  Validade da proposta   Prazo de validade
  Garantias              Exigências financeiras, se houver
  Documentos             Checklist de habilitação
  Responsável            Dono da oportunidade
  Concorrentes           Empresas identificadas, quando público
  Resultado              Ganha, perdida, desclassificada etc.
  Motivo da perda        Classificação para análise posterior

### Checklist de BID

-   [ ] Escopo e quantitativos revisados.
-   [ ] Visita técnica avaliada ou realizada.
-   [ ] Convenção coletiva e salários de referência conferidos.
-   [ ] Planilha de custos e formação de preços revisada.
-   [ ] Tributos e regime tributário validados pelo Financeiro.
-   [ ] Capacidade operacional confirmada.
-   [ ] Disponibilidade de supervisão e mobilização confirmada.
-   [ ] Documentação de habilitação conferida.
-   [ ] Riscos contratuais encaminhados para análise jurídica.
-   [ ] Margem mínima aprovada.
-   [ ] Proposta revisada e aprovada.
-   [ ] Protocolo de envio registrado.
-   [ ] Resultado e feedback registrados.

------------------------------------------------------------------------

## 10. Controle de reajustes, repactuações e aditivos

Contratos de serviços continuados podem ter mecanismos distintos de
atualização de preços. O controle não deve aplicar um índice
automaticamente sem verificar a cláusula contratual e o enquadramento
jurídico.

### Base demonstrativa de eventos

  ------------------------------------------------------------------------------------------------------------------------
  ID       Contrato   Evento                 Data-base    Índice/premissa     Percentual    Valor       Valor Status
                                                                                simulado   mensal   projetado 
                                                                                            atual             
  -------- ---------- ---------------------- ------------ ----------------- ------------ -------- ----------- ------------
  AJ-001   CT-001     Reajuste/repactuação a 01/03/2026   Conforme contrato         5,0%      R\$  R\$ 90.825 Em análise
                      avaliar                             e custos                         86.500             

  AJ-002   CT-002     Reajuste a avaliar     01/06/2026   Índice contratual         4,5%      R\$  R\$ 44.726 Pendente
                                                          hipotético                       42.800             

  AJ-003   CT-004     Repactuação a avaliar  01/04/2026   Variação de               6,0%      R\$  R\$ 60.208 Em análise
                                                          custos de mão de                 56.800             
                                                          obra                                                

  AJ-004   CT-009     Reajuste a avaliar     01/07/2026   Índice contratual         4,2%      R\$  R\$ 77.629 Pendente
                                                          hipotético                       74.500             

  AJ-005   CT-010     Aditivo de escopo      01/12/2026   Inclusão de               8,0%      R\$  R\$ 32.184 Em
                                                          atividade                        29.800             negociação
  ------------------------------------------------------------------------------------------------------------------------

Os percentuais são exemplos de simulação, não índices oficiais nem
direitos automaticamente aplicáveis.

### Regras para o controle

-   Registrar o tipo de evento: reajuste, repactuação, revisão,
    reequilíbrio, prorrogação ou alteração de escopo.
-   Registrar a cláusula contratual e a data-base.
-   Diferenciar índice de preço de variação comprovada de custos.
-   Guardar o valor anterior e o novo valor.
-   Registrar data de solicitação, aprovação e formalização.
-   Não considerar o novo valor como vigente antes da formalização
    exigida.
-   Manter link para o documento comprobatório no repositório oficial.

------------------------------------------------------------------------

## 11. Obrigações, desempenho e riscos contratuais

O controle deve permitir que cada contrato tenha obrigações e
indicadores próprios, de acordo com o escopo e o instrumento assinado.

### Exemplos de obrigações

  -----------------------------------------------------------------------
  Tipo              Exemplo           Frequência        Evidência
                                                        esperada
  ----------------- ----------------- ----------------- -----------------
  Operacional       Cobertura         Diária            Escala e
                    integral dos                        relatório
                    postos                              operacional
                    contratados                         

  Qualidade         Cumprimento do    Diária/semanal    Inspeção e
                    checklist de                        registro
                    limpeza                             

  Segurança         Documentação e    Conforme validade Documentos
                    habilitação                         oficiais
                    exigidas                            

  Financeira        Envio de          Mensal            Protocolo de
                    medição/fatura no                   envio
                    prazo                               

  Trabalhista       Comprovações      Mensal            Documentos
                    previstas no                        validados
                    contrato                            

  Manutenção        Execução do plano Mensal            Ordem de serviço
                    preventivo                          

  Gestão            Reunião de        Mensal            Ata e plano de
                    acompanhamento                      ação
  -----------------------------------------------------------------------

### Matriz de risco sugerida

  -----------------------------------------------------------------------
  Risco             Probabilidade     Impacto           Tratamento
                                                        sugerido
  ----------------- ----------------- ----------------- -----------------
  Vencimento sem    Média             Alto              Alertas em
  decisão de                                            180/120/90 dias
  renovação                                             

  Margem abaixo do  Média             Alto              Revisão de custos
  limite                                                e escopo

  Falta de          Média             Alto              Plano de
  cobertura de                                          contingência
  posto                                                 

  Reajuste não      Média             Alto              Calendário de
  solicitado                                            datas-base

  Descumprimento de Média             Alto              Plano de ação e
  SLA                                                   monitoramento

  Dependência de    Baixa/Média       Alto              Monitorar
  cliente relevante                                     concentração de
                                                        receita

  Documentação      Média             Alto              Checklist e
  vencida                                               responsáveis

  Proposta com      Média             Alto              Validação de
  preço inexequível                                     custos e alçada
  -----------------------------------------------------------------------

A classificação de risco deve ser parametrizada pela empresa. Não deve
ser tratada como parecer jurídico ou avaliação automática definitiva.

------------------------------------------------------------------------

## 12. Indicadores gerenciais propostos

### Indicadores de carteira

  -----------------------------------------------------------------------
  Indicador               Fórmula/conceito        Decisão apoiada
  ----------------------- ----------------------- -----------------------
  Contratos vigentes      Contagem de contratos   Dimensão da carteira
                          ativos na data-base     

  Receita mensal          Soma dos valores        Visão de receita
  contratada              mensais dos contratos   recorrente contratada
                          vigentes                

  Receita anualizada      Receita mensal          Comparação de porte da
                          contratada × 12         carteira

  Margem estimada         Receita mensal menos    Identificação de
                          custo direto estimado   contratos críticos

  Margem percentual       Margem estimada /       Comparação de
                          receita mensal          rentabilidade

  Concentração por        Receita do cliente /    Risco de dependência
  cliente                 receita total           

  Contratos por segmento  Contagem por tipo de    Mix da carteira
                          serviço                 
  -----------------------------------------------------------------------

### Indicadores de vigência e risco

  -----------------------------------------------------------------------
  Indicador               Fórmula/conceito        Decisão apoiada
  ----------------------- ----------------------- -----------------------
  Vencimentos em 30 dias  Contratos com fim entre Ação imediata
                          hoje e hoje + 30        

  Vencimentos em 90 dias  Contratos com fim entre Planejamento de
                          hoje e hoje + 90        renovação

  Vencimentos em 180 dias Contratos com fim entre Planejamento de médio
                          hoje e hoje + 180       prazo

  Reajustes pendentes     Eventos sem conclusão   Recuperação de receita
                                                  elegível

  Contratos com margem    Margem percentual       Renegociação ou plano
  crítica                 abaixo do limite        de eficiência

  Obrigações vencidas     Obrigações com prazo    Redução de exposição
                          ultrapassado e não      
                          concluídas              
  -----------------------------------------------------------------------

### Indicadores comerciais

  -----------------------------------------------------------------------
  Indicador               Fórmula/conceito        Decisão apoiada
  ----------------------- ----------------------- -----------------------
  Oportunidades abertas   Contagem de             Tamanho do pipeline
                          oportunidades não       
                          encerradas              

  Pipeline nominal        Soma do valor anual     Potencial comercial
                          estimado das            
                          oportunidades abertas   

  Pipeline ponderado      Valor anual estimado ×  Previsão comercial
                          probabilidade           ponderada

  Taxa de conversão       Oportunidades ganhas /  Eficiência comercial
                          oportunidades           
                          concluídas              

  Taxa de sucesso em BID  BIDs ganhos / BIDs com  Competitividade
                          resultado               

  Valor de propostas      Soma dos valores das    Receita potencial não
  perdidas                oportunidades perdidas  capturada

  Motivos de perda        Contagem e valor por    Melhoria comercial
                          motivo                  
  -----------------------------------------------------------------------

**Cuidado com o pipeline ponderado:** probabilidade é uma estimativa
comercial, não receita garantida. O valor deve ser apresentado como
potencial ponderado, separado da carteira contratada.

### Indicadores de renovação e retenção

-   Percentual de contratos renovados.
-   Valor mensal retido por renovação.
-   Valor mensal perdido por não renovação.
-   Taxa de renovação por cliente e segmento.
-   Antecedência média da decisão de renovação.
-   Motivos de não renovação.
-   Contratos renovados com alteração de preço ou escopo.

------------------------------------------------------------------------

## 13. Arquitetura sugerida da pasta de trabalho Excel

A pasta deve ser organizada em tabelas estruturadas, evitando bases com
células mescladas, linhas em branco no meio dos dados ou totais
digitados manualmente.

### Abas recomendadas

  -----------------------------------------------------------------------
  Aba                         Finalidade            Conteúdo principal
  --------------------------- --------------------- ---------------------
  `00_Painel_Gerencial`       Visão executiva       KPIs, gráficos,
                                                    alertas e filtros

  `01_Contratos`              Cadastro mestre       Um registro por
                                                    contrato

  `02_Itens_Contrato`         Composição do escopo  Serviços, postos,
                                                    quantidades e preços

  `03_Clientes`               Cadastro de clientes  Dados cadastrais e
                                                    classificação

  `04_Fornecedores`           Apoio à cadeia de     Fornecedores críticos
                              suprimentos           e categorias

  `05_Financeiro`             Acompanhamento mensal Receita prevista,
                                                    faturada, custo e
                                                    margem

  `06_Reajustes_Aditivos`     Eventos contratuais   Datas-base,
                                                    solicitações e
                                                    formalizações

  `07_Obrigacoes_SLA`         Controle operacional  Obrigações, prazos,
                                                    evidências e status

  `08_Ocorrencias_Riscos`     Registro de desvios   Ocorrências, riscos e
                                                    planos de ação

  `09_Renovacoes`             Agenda de renovações  Vencimentos e
                                                    decisões

  `10_Oportunidades_BID`      Pipeline comercial    Editais, RFPs, BIDs e
                                                    propostas

  `11_Contratos_Encerrados`   Histórico             Contratos perdidos,
                                                    encerrados e motivos

  `12_Listas_Apoio`           Parâmetros            Status, segmentos,
                                                    motivos e
                                                    classificações

  `13_LeiaMe`                 Orientações           Regras de
                                                    preenchimento e
                                                    governança
  -----------------------------------------------------------------------

### Estrutura mínima da tabela `01_Contratos`

`ID_Contrato` · `Cliente_ID` · `Numero_Contrato` · `Objeto` · `Segmento`
· `Unidade` · `Municipio` · `Data_Assinatura` · `Inicio_Vigencia` ·
`Fim_Vigencia` · `Valor_Mensal` · `Valor_Global` ·
`Custo_Direto_Estimado` · `Gestor_Contrato` · `Responsavel_Comercial` ·
`Indice_Reajuste` · `Data_Base` · `Status_Contrato` · `Link_Documento` ·
`Observacoes`

### Estrutura mínima da tabela `10_Oportunidades_BID`

`ID_Oportunidade` · `Cliente_ID` · `Nome_Oportunidade` · `Modalidade` ·
`Numero_Processo` · `Objeto` · `Municipio` · `Valor_Estimado_Mensal` ·
`Valor_Proposto_Mensal` · `Custo_Estimado_Mensal` · `Margem_Prevista` ·
`Probabilidade` · `Data_Publicacao` · `Data_Visita` ·
`Prazo_Esclarecimentos` · `Prazo_Proposta` · `Data_Sessao` ·
`Responsavel` · `Etapa` · `Resultado` · `Motivo_Perda` · `Link_Edital`

Corrigir o nome do campo `Motivo_Perda` para `Motivo_Perda` na
implementação.

### Relacionamentos lógicos

-   Um cliente pode possuir vários contratos.
-   Um contrato pode possuir vários itens de serviço.
-   Um contrato pode possuir vários eventos de reajuste e aditivo.
-   Um contrato pode possuir várias obrigações, SLAs e ocorrências.
-   Uma oportunidade pode resultar em um contrato.
-   Um contrato encerrado deve manter seu histórico, sem ser apagado da
    base.

Use IDs únicos como chaves. Não utilize o nome do cliente como chave de
relacionamento.

------------------------------------------------------------------------

## 14. Regras de negócio e validações

1.  Cada contrato deve possuir um identificador único.
2.  A data final não pode ser anterior à data inicial.
3.  Contratos encerrados não devem ser excluídos; devem mudar de status
    e permanecer no histórico.
4.  Contratos futuros não devem compor a receita vigente antes do início
    efetivo.
5.  Contratos vencidos não devem continuar classificados como vigentes,
    salvo prorrogação formal registrada.
6.  Aditivos devem manter histórico do valor anterior e do novo valor.
7.  Reajustes projetados não devem alterar automaticamente a receita
    contratada.
8.  Oportunidades comerciais não devem compor a carteira contratada.
9.  Pipeline nominal e pipeline ponderado devem ser apresentados
    separadamente.
10. Propostas perdidas devem exigir motivo de perda.
11. Contratos com margem negativa ou abaixo do limite devem gerar
    sinalização.
12. Obrigações vencidas devem aparecer em lista de atenção.
13. Links para documentos devem apontar para repositório corporativo
    autorizado.
14. Valores devem possuir unidade de medida e periodicidade explícitas.
15. O arquivo deve exibir claramente a data-base de atualização.

### Exemplo de classificação automática de vigência

Considerando `Fim_Vigencia` e a data de referência:

-   `A vencer — até 30 dias`
-   `A vencer — 31 a 90 dias`
-   `A vencer — 91 a 180 dias`
-   `Vigente — acima de 180 dias`
-   `Vencido`
-   `Futuro — ainda não iniciado`

A classificação deve considerar também a data de início e o status
formal do contrato, para não classificar incorretamente contratos
suspensos, rescindidos ou prorrogados.

------------------------------------------------------------------------

## 15. Proposta de painel executivo

O painel inicial deve responder rapidamente às perguntas da diretoria.

### Faixa superior --- indicadores principais

-   Contratos vigentes.
-   Receita mensal contratada.
-   Margem de contribuição estimada.
-   Contratos a vencer em 90 dias.
-   Reajustes pendentes.
-   Pipeline ponderado.

### Área central --- visão da carteira

-   Receita por segmento.
-   Receita por cliente.
-   Contratos por status.
-   Evolução mensal da receita contratada.
-   Margem estimada por contrato.

### Área de atenção --- agenda gerencial

-   Próximos vencimentos.
-   Contratos com margem abaixo da meta.
-   Obrigações vencidas.
-   Reajustes e aditivos pendentes.
-   BIDs com prazo de entrega próximo.
-   Oportunidades sem atualização recente.

### Filtros recomendados

-   Período.
-   Cliente.
-   Segmento.
-   Município.
-   Gestor responsável.
-   Status do contrato.
-   Tipo de oportunidade.

**Princípio de desenho:** o painel não deve ser apenas um conjunto de
gráficos. Cada indicador precisa permitir localizar os contratos e
oportunidades que exigem uma ação gerencial.

------------------------------------------------------------------------

## 16. Rotina de gestão sugerida

  ------------------------------------------------------------------------
  Frequência             Rotina                 Responsável sugerido
  ---------------------- ---------------------- --------------------------
  Diária                 Verificar prazos       Comercial/gestores
                         críticos de BID e      
                         obrigações             

  Semanal                Atualizar              Comercial
                         oportunidades e        
                         renovações             

  Semanal                Revisar ocorrências    Operações
                         operacionais críticas  

  Mensal                 Atualizar receita,     Financeiro/Controladoria
                         custos e margem        
                         estimada               

  Mensal                 Revisar contratos com  Gestão de contratos
                         vencimento em          
                         180/120/90 dias        

  Mensal                 Analisar contratos com Diretoria/Operações
                         margem crítica         

  Trimestral             Revisar concentração   Diretoria
                         de clientes e          
                         segmentos              

  Trimestral             Avaliar taxa de        Comercial
                         conversão e motivos de 
                         perda                  

  Anual                  Revisar premissas,     Diretoria
                         indicadores e          
                         governança             
  ------------------------------------------------------------------------

### Papéis e responsabilidades

-   **Diretoria:** define limites de margem, prioridades e alçadas de
    decisão.
-   **Gestão de contratos:** mantém cadastro, vigências, eventos e
    obrigações.
-   **Comercial:** mantém oportunidades, BIDs, propostas e resultados.
-   **Operações:** atualiza capacidade, ocorrências, SLAs e mobilização.
-   **Financeiro/Controladoria:** valida receita, custos, reajustes e
    premissas financeiras.
-   **Jurídico:** analisa cláusulas, riscos, aditivos, rescisões e
    conformidade, quando aplicável.

------------------------------------------------------------------------

## 17. Plano de implantação do controle

### Etapa 1 --- Diagnóstico e desenho

-   Definir responsáveis e usuários.
-   Validar campos e conceitos.
-   Estabelecer regras de status.
-   Definir indicadores e limites de atenção.

### Etapa 2 --- Saneamento e carga inicial

-   Reunir contratos vigentes.
-   Padronizar clientes e serviços.
-   Conferir valores e datas.
-   Separar contratos encerrados.
-   Cadastrar oportunidades em andamento.

### Etapa 3 --- Construção do Excel

-   Criar tabelas estruturadas.
-   Configurar validações e listas.
-   Desenvolver fórmulas e consultas.
-   Construir painel gerencial.
-   Criar alertas visuais e filtros.

### Etapa 4 --- Validação

-   Conferir amostras contra contratos originais.
-   Validar cálculos com Financeiro.
-   Testar datas e classificações.
-   Verificar duplicidades e registros incompletos.
-   Testar o painel com gestores.

### Etapa 5 --- Implantação e governança

-   Definir proprietário do arquivo.
-   Estabelecer rotina de atualização.
-   Controlar versões.
-   Documentar regras.
-   Definir critérios para migração futura a uma solução corporativa.

### Critérios de aceite

-   100% dos contratos vigentes cadastrados e conferidos na amostra
    definida.
-   Todos os contratos com início, fim, valor e responsável preenchidos
    ou justificados.
-   Contratos a vencer identificados corretamente.
-   Oportunidades comerciais separadas da carteira contratada.
-   Reajustes e aditivos com histórico.
-   Painel reconciliado com a base.
-   Usuários-chave treinados.
-   Responsável pela atualização formalmente definido.

------------------------------------------------------------------------

## 18. Entregáveis do projeto

1.  Pasta de trabalho Excel com bases estruturadas.
2.  Painel executivo de gestão de contratos.
3.  Cadastro mestre de contratos e itens.
4.  Controle de reajustes, aditivos e renovações.
5.  Histórico de contratos encerrados e perdidos.
6.  Pipeline de oportunidades, BID, RFP e licitações.
7.  Controle de obrigações, SLAs, ocorrências e riscos.
8.  Dicionário de dados e regras de preenchimento.
9.  Manual de atualização e governança.
10. Relatório de validação e recomendações para evolução.

------------------------------------------------------------------------

## 19. Como demonstrar esse case no portfólio

O projeto deve ser apresentado como uma iniciativa de gestão, não como
uma demonstração de fórmulas do Excel.

### Título sugerido

**Gestão de Contratos \| Controle, previsibilidade e inteligência para
decisões**

### Resumo para a página do projeto

Estruturação de um modelo gerencial em Excel para uma empresa de
facilities com contratos distribuídos entre diferentes clientes,
serviços e localidades. A proposta integra carteira vigente,
vencimentos, reajustes, custos estimados, histórico de perdas e pipeline
de BID, permitindo ampliar a visibilidade sobre compromissos contratuais
e oportunidades futuras.

### Evidências visuais recomendadas

1.  Painel executivo com visão da carteira.
2.  Calendário de vencimentos e renovações.
3.  Análise de receita e margem estimada por contrato.
4.  Funil de oportunidades e BIDs.
5.  Histórico de contratos perdidos e motivos.
6.  Matriz de riscos e obrigações.

### Competências demonstradas

-   Gestão de contratos.
-   Planejamento e controle.
-   Gestão financeira e análise de custos.
-   Gestão de riscos.
-   Gestão comercial e pipeline.
-   Estruturação de indicadores.
-   Melhoria de processos.
-   Modelagem de informações.
-   Excel e Power Query.

### Como descrever sua participação

Se você desenvolver o case individualmente, pode utilizar:

> Concepção e estruturação de um modelo de gestão contratual,
> contemplando organização da carteira, controle de vigências, análise
> financeira, acompanhamento de reajustes, gestão de oportunidades
> comerciais e indicadores executivos. O projeto foi desenhado para
> apoiar a tomada de decisão e reduzir a fragmentação das informações
> utilizadas pela gestão.

Deixe claro que se trata de um **estudo de caso demonstrativo**,
desenvolvido com empresa e dados fictícios. Não apresente os resultados
simulados como experiência profissional real.

------------------------------------------------------------------------

## 20. Dicionário de dados: campos complementares

Para que o projeto tenha profundidade e permita evolução, recomenda-se
incluir os seguintes campos nas tabelas:

### Cadastro de clientes

-   Cliente_ID
-   Razão social fictícia
-   Nome fantasia
-   Segmento econômico
-   Município/UF
-   Tipo de cliente (público/privado)
-   Responsável comercial
-   Status do relacionamento
-   Classificação de relevância

### Itens de contrato

-   Item_ID
-   ID_Contrato
-   Código do serviço
-   Descrição
-   Unidade de medida
-   Quantidade
-   Preço unitário
-   Valor mensal
-   Custo unitário estimado
-   Custo mensal estimado
-   Local de execução
-   Data de início e fim do item

### Financeiro mensal

-   Competência
-   ID_Contrato
-   Receita prevista
-   Receita faturada
-   Receita recebida
-   Custo de mão de obra
-   Benefícios e encargos
-   Materiais e insumos
-   Equipamentos
-   Outros custos diretos
-   Margem estimada
-   Observação de divergência

### Obrigações e SLA

-   Obrigacao_ID
-   ID_Contrato
-   Descrição
-   Tipo
-   Frequência
-   Responsável
-   Prazo
-   Status
-   Data de conclusão
-   Link da evidência
-   Criticidade

### Ocorrências e riscos

-   Ocorrencia_ID
-   ID_Contrato
-   Data
-   Categoria
-   Descrição
-   Impacto
-   Probabilidade
-   Severidade
-   Responsável
-   Plano de ação
-   Prazo
-   Status
-   Data de encerramento

------------------------------------------------------------------------

## 21. Perguntas que a solução deverá responder

Ao final, a Vértice deverá conseguir responder, com base nos registros
atualizados:

1.  Qual é o valor mensal da carteira vigente?
2.  Quanto da receita está concentrada nos cinco maiores clientes?
3.  Quais contratos possuem margem estimada abaixo da meta?
4.  Quais contratos vencem nos próximos 30, 60, 90 e 180 dias?
5.  Quais renovações precisam de decisão imediata?
6.  Qual é o valor financeiro associado aos reajustes em análise?
7.  Quais contratos tiveram maior número de ocorrências?
8.  Quais clientes não renovaram e quais foram os motivos?
9.  Quanto de receita mensal foi perdido nos últimos 12 meses?
10. Qual é o valor nominal e ponderado do pipeline comercial?
11. Quais BIDs exigem ação nos próximos sete dias?
12. Quais propostas possuem margem prevista abaixo do limite?
13. Quais segmentos concentram maior receita e margem?
14. Qual é a taxa de conversão das oportunidades concluídas?
15. Quais contratos exigem plano de ação da diretoria?

------------------------------------------------------------------------

## 22. Referências e ressalvas

As referências públicas abaixo foram utilizadas para contextualizar a
ordem de grandeza de alguns serviços. Elas não validam todos os preços
simulados nem substituem pesquisa de mercado, planilha de custos,
convenções coletivas ou análise tributária.

-   [Polícia Federal --- Contrato nº 10/2025, limpeza, conservação,
    lavagem de veículos e jardinagem na
    Bahia](https://www.gov.br/pf/pt-br/assuntos/licitacoes/2025/bahia/contratos/contrato-no-10-2025-sr-pf-ba.pdf/view).
-   [CEMADEN --- Contrato 01/2025, vigilância
    patrimonial](https://www.gov.br/cemaden/pt-br/acesso-a-informacao/licitacoes-e-contratos-1/contratos-1/contrato-01-2025).
-   [CEMADEN --- Contrato 06/2026, vigilância
    patrimonial](https://www.gov.br/cemaden/pt-br/acesso-a-informacao/licitacoes-e-contratos-1/contratos-1/contrato-06-2026).
-   [Referência de contratação de vigilância na Bahia em
    2026](https://licitachei.iagenes.com.br/licitacao/3587905).

**Ressalva metodológica:** os valores de contratos da Vértice, clientes,
histórico, oportunidades, probabilidades, custos e margens são dados
sintéticos construídos para o estudo de caso. Os preços de serviços
diferentes dos itens de vigilância são premissas demonstrativas. Mesmo
para vigilância, os valores públicos citados possuem escopos e condições
próprias e não devem ser transplantados diretamente para uma proposta.

**Data-base do cenário:** 01 de novembro de 2026.\
**Natureza:** estudo de caso fictício para demonstração de competências
em gestão, planejamento, controle contratual e Excel.
