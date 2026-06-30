# 4. Caracterização dos avaliadores e do objeto de estudo

<p style="text-align: justify; margin-bottom: 18px;">
Esta página documenta o ecossistema real do teste, apresentando a interface escolhida, as personas envolvidas e as tarefas específicas que foram monitoradas.
</p>

<p style="text-align: justify; margin-bottom: 18px;">
Para compreender a fundo o cenário em que as avaliações de usabilidade e acessibilidade foram aplicadas, esta seção foi estruturada e dividida em três pilares fundamentais.
</p>

---

## <img src="imagens/website.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 4.1 O site avaliado

<img src="imagens/info.png" alt="" width="18" style="vertical-align: middle; margin-right: 4px;"> **Contexto do Sistema:**

<p style="text-align: justify; margin-bottom: 18px;">
O site oficial do Hospital Militar de Área de Brasília (HMAB) é um portal institucional e de prestação de serviços de saúde voltado exclusivamente para os militares do Exército Brasileiro (ativos, da reserva e reformados) e seus dependentes legais na Região Mandatária da 11ª Região Militar.
</p>

<p style="text-align: justify; margin-bottom: 18px;">
A plataforma serve como o principal canal digital de comunicação e autoatendimento para os beneficiários do FUSEX (Fundo de Saúde do Exército) e do SAMMED. Por meio dele, os usuários podem realizar o agendamento online de consultas e exames, consultar escalas médicas, acessar resultados de laudos laboratoriais e obter informações atualizadas sobre guias de encaminhamento externo, além de acompanhar avisos institucionais da direção do hospital. É uma ferramenta essencial para centralizar o suporte à saúde militar na capital federal, otimizando o fluxo de atendimento e promovendo a transparência administrativa da organização de saúde.
</p>

---

<div style="text-align: center; margin-top: 15px;">
  <p><strong>Acesse o site oficial:</strong></p>

  <a href="https://hmab.eb.mil.br/" target="_blank">
    <img src="imagens/HMAB2-logo.png" alt="Logo HMAB" width="120" style="display: block; margin: 0 auto 8px auto;">
    Portal HMAB
  </a>
</div>

---

## <img src="imagens/profile.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 4.2 Perfil dos Avaliadores (Especialistas)

<img src="imagens/info.png" alt="" width="18" style="vertical-align: middle; margin-right: 4px;"> **Contexto do Usuário Técnico:**

<p style="text-align: justify; margin-bottom: 18px;">
A avaliação por especialistas (Inspeção de Usabilidade e Acessibilidade) foi conduzida pelos próprios membros do grupo desenvolvedor, atuando sob o papel metodológico de avaliadores de interface.
</p>

<p style="text-align: justify; margin-bottom: 18px;">
O perfil do corpo técnico de avaliadores é qualificado pelas seguintes competências:
</p>

<ul>
<li style="margin-bottom: 12px; text-align: justify;">
<strong>Formação Acadêmica:</strong> Discentes do curso de graduação em Engenharia de Software da Universidade de Brasília (UnB), possuindo domínio sobre o ciclo de vida de desenvolvimento de sistemas e arquitetura de software.
</li>

<li style="margin-bottom: 12px; text-align: justify;">
<strong>Domínio em IHC e UX:</strong> Capacitação teórica e prática nos conceitos fundamentais de Interação Humano-Computador (IHC), Design de Experiência do Usuário (UX) e critérios de usabilidade. O grupo possui formação voltada para a identificação de barreiras de interface, fluxogramas de navegação e design centrado no usuário.
</li>

<li style="margin-bottom: 12px; text-align: justify;">
<strong>Conhecimento em Acessibilidade Digital:</strong> Alinhamento técnico com as diretrizes internacionais de acessibilidade na Web, detendo conhecimento aprofundado sobre os critérios de sucesso e os quatro princípios fundamentais (Perceptível, Operável, Compreensível e Robusto) da norma <strong>WCAG (Web Content Accessibility Guidelines)</strong>.
</li>
</ul>

<p style="text-align: justify; margin-bottom: 18px;">
Essa combinação de competências técnicas em Engenharia de Software com os conceitos de IHC qualifica o grupo como avaliadores aptos a identificar desconformidades severas na interface do portal HMAB, garantindo o rigor analítico necessário para o mapeamento dos problemas através do checklist estruturado.
</p>

---

## <img src="imagens/scenario.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 4.3 Perfil e Qualificação do Usuário

<img src="imagens/info.png" alt="" width="18" style="vertical-align: middle; margin-right: 4px;"> **Contexto do Usuário:**

<p style="text-align: justify; margin-bottom: 18px;">
Para a realização do teste empírico de usabilidade, contou-se com a participação de uma usuária real do ecossistema do Hospital Militar de Área de Brasília (HMAB), cuja caracterização sociodemográfica e tecnológica reflete uma parcela significativa e vulnerável da população atendida pela instituição.
</p>

<ul>
<li style="margin-bottom: 12px; text-align: justify;">
<strong>Dados Demográficos e Contexto de Uso:</strong> A participante é uma idosa de 75 anos de idade, paciente ativa do hospital e dependente do plano de saúde do Exército Brasileiro (FUSEX).
</li>

<li style="margin-bottom: 12px; text-align: justify;">
<strong>Letramento Digital e Familiaridade Tecnológica:</strong> A usuária apresenta baixo letramento digital e baixa familiaridade com sistemas computacionais cotidianos. Não possui computador de mesa ou notebook, sendo o <em>smartphone</em> o seu único ponto de contato e meio de acesso à internet. Devido às complexidades da interface do portal, a participante não possui autonomia plena para navegar no sistema, necessitando recorrer recorrentemente ao auxílio de terceiros (especificamente de suas netas) para gerenciar suas demandas de saúde na plataforma.
</li>

<li style="margin-bottom: 12px; text-align: justify;">
<strong>Limitações de Acessibilidade Fisiológica:</strong> Do ponto de vista físico e sensorial, a usuária manifesta limitações visuais típicas do envelhecimento natural (presbiopia/baixa visão). Durante a interação, observou-se a necessidade do uso de óculos de grau combinada com a aproximação física severa do aparelho ao rosto.
</li>
</ul>

<p style="text-align: justify; margin-bottom: 18px;">
Como barreira imediata de IHC, a participante depende criticamente da aplicação constante de zoom manual e mecânico (gesto de pinça na tela) para conseguir realizar a leitura de textos e rótulos, uma vez que a interface original do HMAB apresenta fontes diminutas e elementos gráficos de tamanho reduzido, penalizando a experiência de uso deste perfil populacional.
</p>

---

<div align="right">
  <small style="opacity: 0.5;">
    Ícone por <a href="https://www.flaticon.com/br/autores/freepik" target="_blank">Freepik</a>
  </small>
</div>