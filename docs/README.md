<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/c5cb6d17-eaa2-43d7-bf69-c830704f0dec" 
    alt="LIRAa Digital"
    width="200"
  />
</p>

# LIRAa Digital | Campina Grande

## Visão Geral do Projeto

O **LIRAa Digital** é uma plataforma inovadora e interativa desenvolvida para a Vigilância Ambiental de Campina Grande - PB. Seu principal objetivo é democratizar o acesso e facilitar a análise dos dados do **LIRAa (Levantamento Rápido de Índices para *Aedes aegypti*)**, o principal vetor de arboviroses como Dengue, Zika e Chikungunya. A ferramenta centraliza informações cruciais, permitindo a rápida identificação de áreas de risco e subsidiando a tomada de decisões estratégicas para o controle vetorial no município, otimizando as ações de saúde pública.

## O que é o LIRAa?

O LIRAa (Levantamento Rápido de Índices para *Aedes aegypti*) é uma metodologia padronizada criada pelo Ministério da Saúde do Brasil. Ela visa fornecer, de forma ágil, econômica e com segurança estatística, um panorama da infestação larvária do *Aedes aegypti* e *Aedes albopictus* nos municípios. Sua aplicação permite identificar bairros ou áreas específicas com maior risco de transmissão de doenças, direcionando as ações de controle de forma mais eficaz.

### Metodologia de Levantamento

A metodologia do LIRAa baseia-se na **amostragem por conglomerados**. Funciona assim:

1. **Estratifícação:** A área urbana do município é dividida em estratos (setores censitários ou agrupamentos de quarteirões) que apresentam características socioambientais homogêneas.
2. **Sorteio de Imóveis:** Em cada estrato, um percentual de imóveis (geralmente entre 10% e 20%) é sorteado aleatoriamente para inspeção.
3. **Inspeção Domiciliar:** Agentes de saúde visitam os imóveis sorteados para identificar e coletar larvas e pupas em recipientes que acumulam água, que são potenciais criadouros do mosquito.
4. **Análise e Cálculo de Índices:** As larvas coletadas são encaminhadas para identificação e, com base nesses dados, são calculados os índices de infestação.

**Ciclos de Avaliação:** Para um monitoramento contínuo e eficaz da situação epidemiológica, são realizados, em média, **quatro ciclos de avaliação por ano**. Essa periodicidade permite acompanhar a sazonalidade da infestação, avaliar a eficácia das ações de controle e adaptar as estratégias conforme a necessidade.

### Principais Índices Monitorados e suas Fórmulas

O portal LIRAa Digital exibe e analisa os seguintes indicadores-chave, que são cruciais para compreender a situação da infestação do mosquito:

1. **Infestação Predial (IIP)**:
    * **O que mede:** Representa a dispersão do mosquito. Indica o percentual de imóveis visitados que apresentaram a presença de larvas do *Aedes aegypti* (ou *Aedes albopictus*).
    * **Fórmula:**
        $$ \text{IIP} = \frac{\text{Número de imóveis com larvas positivas}}{\text{Número total de imóveis inspecionados}} \times 100 $$
    * **Significado:** Um IIP elevado sugere que o mosquito está amplamente distribuído na área, aumentando o risco de contato entre o vetor e a população.

2. **Índice de Breteau (IB)**:
    * **O que mede:** Indica a densidade da infestação. Relaciona o número de recipientes com larvas positivas com o número total de imóveis inspecionados, padronizado para cada 100 imóveis.
    * **Fórmula:**
        $$ \text{IB} = \frac{\text{Número de depósitos (recipientes) positivos}}{\text{Número total de imóveis inspecionados}} \times 100 $$
    * **Significado:** Um IB alto aponta para uma grande quantidade de criadouros ativos, o que pode levar a um aumento rápido da população de mosquitos.

3. **Aedes Albopictus (Presença Vetorial)**:
    * **O que mede:** Monitoramento específico da presença do *Aedes albopictus*, uma espécie de mosquito que também pode transmitir arboviroses, embora com menor relevância epidemiológica que o *Aedes aegypti* no contexto urbano brasileiro. O foco é identificar sua presença e os tipos de criadouros predominantes.
    * **Cálculo Simplificado:** O portal pode mostrar a contagem de focos (recipientes positivos) ou a frequência de sua ocorrência por área.
    * **Significado:** Embora menos comum em áreas urbanas densas, o *Aedes albopictus* tem potencial de transmissão e sua vigilância é importante, especialmente em áreas periurbanas e rurais.

### Classificação de Risco (Conforme Ministério da Saúde)

Com base nos valores dos índices de Infestação Predial (IIP) e Breteau (IB), os bairros e estratos são classificados em três níveis de risco para a transmissão de arboviroses, orientando as ações de controle:

* **Satisfatório (Verde) 🟢:**
    * **Índices:** IIP e IB **inferiores a 1,0**.
    * **Situação:** Baixo risco. Indica que a presença do vetor está controlada.
    * **Ações Recomendadas:** Manutenção da vigilância, educação em saúde contínua e atividades preventivas regulares.
* **Alerta (Amarelo) 🟡:**
    * **Índices:** IIP e IB **entre 1,0 e 3,9**.
    * **Situação:** Médio risco. Demonstra uma circulação significativa do vetor.
    * **Ações Recomendadas:** Intensificação imediata das ações de controle, como mutirões de limpeza, eliminação de focos, visitas domiciliares focadas e inspeções detalhadas.
* **Risco (Vermelho) 🔴:**
    * **Índices:** IIP e IB **iguais ou superiores a 4,0**.
    * **Situação:** Crítica. Alto risco de surto ou epidemia.
    * **Ações Recomendadas:** Ações emergenciais integradas e em larga escala, incluindo bloqueio de transmissão, aplicação de larvicidas e inseticidas (como o popular "Fumacê"), e mobilização comunitária massiva.

## Funcionalidades do Portal LIRAa Digital

O portal foi projetado para ser intuitivo e oferecer uma análise completa dos dados:

* **Dashboard Interativo:** Visão geral rápida dos índices de infestação por ano e ciclo de levantamento.
* **Mapa Dinâmico:** Visualização georreferenciada da situação de Campina Grande por bairros, com coloração intuitiva que indica o nível de risco (Verde, Amarelo, Vermelho).
* **Filtros Avançados:** Permite selecionar o ano base, o ciclo de levantamento e o tipo de indicador (IIP, Breteau, Albopictus) para uma análise específica.
* **Busca por Bairro:** Encontre rapidamente informações detalhadas sobre um bairro específico e sua situação epidemiológica.
* **Análise de Dados Detalhada:** Cards e gráficos que apresentam de forma clara os resultados, as classificações de risco e as tendências históricas.
* **Responsividade:** Otimizado para acesso em dispositivos móveis (smartphones, tablets) e desktops, garantindo uma experiência de usuário consistente.
* **Configurações de Mapa:** Opções para alterar o estilo do mapa base (padrão, híbrido, satélite) e a opacidade das camadas de dados.
* **Modo Tela Cheia:** Expanda o mapa para preencher toda a tela, facilitando a visualização e análise espacial.

## Tecnologias Utilizadas

O LIRAa Digital foi construído com um conjunto de tecnologias modernas para garantir robustez, interatividade e uma excelente experiência de usuário:

* **Front-end:**
    * **HTML5:** Estrutura semântica do conteúdo.
    * **CSS3:** Estilização visual, com a utilização de **Bootstrap 5.3** para um design responsivo e componentes pré-estilizados.
    * **JavaScript:** Lógica de interatividade, manipulação de dados e dinamismo da aplicação.
* **Bibliotecas Específicas:**
    * **Leaflet.js:** Uma das bibliotecas mais populares para a criação de mapas interativos e responsivos na web.
    * **Chart.js:** Utilizada para gerar gráficos dinâmicos e visualmente atraentes, facilitando a interpretação dos dados temporais e de distribuição.
    * **Chartjs-plugin-datalabels:** Plugin para exibir rótulos de dados diretamente nos gráficos.
    * **XLSX (SheetJS):** Biblioteca essencial para a leitura e processamento dos arquivos de dados no formato Excel (`.xlsx`), que alimentam o portal.
    * **Bootstrap Icons:** Um conjunto de ícones modernos para enriquecer a interface do usuário.

## Desenvolvimento

O LIRAa Digital é fruto de uma colaboração estratégica e multidisciplinar:

* **Desenvolvido por:** **GAT 5 do PET Saúde Digital da UFCG (Universidade Federal de Campina Grande)**.
* **Em Parceria com:** **Secretaria de Saúde de Campina Grande**.

Essa iniciativa conjunta visa fortalecer a vigilância em saúde e o controle de arboviroses em Campina Grande, utilizando a tecnologia como ferramenta para a gestão e disseminação de informações vitais.

## Colaboradores e Apoios

Conheça as instituições por trás deste projeto:

* **PET Saúde Digital UFCG**: [Instagram](https://www.instagram.com/pet_saude_digital_ufcg/)
* **GAT 5**: [Instagram](https://www.instagram.com/arboviroses_cg/)
* **Secretaria de Saúde de Campina Grande**: [Website](https://saude.campinagrande.pb.gov.br/)


Se você deseja explorar o código ou contribuir, siga os passos abaixo para configurar o ambiente local:

1. **Clone o repositório:**
