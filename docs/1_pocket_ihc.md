# 1. Pocket IHC

Este capítulo apresenta o "Pocket IHC", um guia rápido focado nos conceitos essenciais de usabilidade e design de interface. Aqui, sintetizamos as teorias que serviram como base para todas as decisões práticas tomadas ao longo do nosso projeto.

---

## <img src="imagens/topics.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 1.1 Tópicos da Disciplina
> <img src="imagens/star.png" alt="" width="18" style="vertical-align: middle; margin-right: 4px;"> **Conceito Chave:** A capacidade de aprender (*learnability*) e de operar (*operability*) de um sistema devem estar intimamente ligadas: o usuário precisa conseguir entender a lógica de funcionamento da interface para ser capaz de utilizá-la de forma autônoma e fluida, reduzindo a sobrecarga cognitiva sobre a sua memória de curto prazo.

* **Perspectiva de Construção vs. Uso:** Tradicionalmente, equipes de desenvolvimento constroem sistemas "de dentro para fora" (focando primeiro nos dados, estruturando a lógica interna e finalizando na interface). A Engenharia de IHC exige inverter esse modelo para uma abordagem "de fora para dentro", projetando a solução inteira a partir da percepção, das dores e do contexto real do usuário final.
* **Donald A. Norman & Engenharia Cognitiva:** Norman postula que para transpor os abismos de interação (os Golfos de Execução e de Avaliação), o designer precisa construir uma "Imagem do Sistema" consistente e inteligível. Isso garante que o modelo mental desenvolvido pelo usuário ao mexer na tela reflita fielmente o modelo de design projetado.
* **Cognição Humana e Memória de Trabalho:** O cérebro humano possui limites severos em sua memória de curto prazo. Sistemas interativos eficazes devem apoiar essa limitação priorizando o reconhecimento em vez da recordação, mantendo objetos, ações e opções visíveis para que o usuário não precise decorar caminhos complexos.
* **Princípios de Gestalt (Organização Visual):** Leis da psicologia visual que determinam como nossa mente agrupa e interpreta elementos automaticamente na tela:
  * **Proximidade:** Elementos espacialmente próximos são percebidos como parte de um mesmo grupo ou função.
  * **Similaridade:** Itens que compartilham a mesma cor, forma ou tamanho tendem a ser associados à mesma utilidade.
  * **Fechamento (Fecho):** A mente tende a preencher lacunas e completar formas abertas ou simétricas para extrair significado rapidamente.

### As 10 Heurísticas de Usabilidade de Nielsen
Diretrizes essenciais para inspeção de interfaces:

1. **Visibilidade do estado do sistema:** Manter o usuário informado por meio de feedbacks em tempo razoável.
2. **Correspondência com o mundo real:** Utilizar palavras, frases e conceitos familiares ao jargão do usuário, evitando termos técnicos de programação.
3. **Controle e liberdade do usuário:** Permitir desfazer, refazer e cancelar ações facilmente através de saídas de emergência claras.
4. **Consistência e padrões:** Não confundir o usuário modificando o nome ou o comportamento de elementos idênticos em telas diferentes.
5. **Prevenção de erros:** Projetar a interface de forma a evitar que o erro aconteça antes mesmo que o usuário realize a ação.
6. **Reconhecimento em vez de recordação:** Deixar instruções e opções de navegação visíveis para diminuir a carga cognitiva.
7. **Flexibilidade e eficiência de uso:** Fornecer atalhos e aceleradores para usuários avançados sem penalizar os iniciantes.
8. **Estética e design minimalista:** Eliminar informações irrelevantes ou redundantes que disputem a atenção visual direta.
9. **Ajuda aos usuários para reconhecer, diagnosticar e recuperar-se de erros:** Mensagens de erro claras, sem códigos de máquina, sugerindo uma solução imediata.
10. **Ajuda e documentação:** Informações de suporte fáceis de buscar e estritamente focadas nas tarefas práticas do usuário.

---

## <img src="imagens/concept.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 1.2 Outros Conceitos
Este módulo aborda as ferramentas essenciais de modelagem de requisitos e engenharia de serviços voltadas ao mapeamento de ecossistemas complexos:

* **Conceito de UX (User Experience):** É a percepção e o conjunto de sentimentos, reações e respostas que uma pessoa desenvolve ao interagir com um produto, sistema ou serviço. Longe de se limitar apenas à estética visual ou à beleza das telas, o design de UX busca entender profundamente o contexto, as dores e as limitações do usuário final para garantir que a jornada inteira seja útil, fácil de usar, eficiente e psicologicamente satisfatória.
* **Personas & Lean Canvas:** A modelagem inicial do ecossistema exige a criação de Personas — perfis arquetípicos baseados em comportamentos reais de usuários que guiam as decisões de design de interface. Em paralelo, o Lean Canvas estrutura e valida o modelo de negócio ágil, mapeando o problema, a solução e a proposta de valor única de forma rápida.
* **Mapa de Jornada do Usuário:** Desenvolvido imediatamente após a consolidação da persona para especificar a sequência temporal do serviço. Subdivide-se em duas abordagens fundamentais:
  * **Jornada Centrada na Experiência (UX):** Focada no mapeamento holístico dos sentimentos, expectativas, oscilações emocionais (altos e baixos), dores e frustrações do usuário ao longo do tempo.
  * **Jornada Centrada no Produto:** Focada estritamente nos pontos de contato operacionais e mecânicos do usuário com as telas, cliques e fluxos funcionais do software.
* **Service Blueprint (A Planta Baixa do Serviço):** Ferramenta cujo nome se origina das antigas cópias heliográficas de engenharia ("impressão azul"). Funciona como uma planta baixa operacional que desenha toda a jornada de entrega do serviço, enxergando o cliente como o ativo mais precioso da empresa. É estruturada horizontalmente por camadas rígidas:
  * **Evidências Físicas:** Elementos tangíveis e visuais com os quais o cliente interage ao iniciar a jornada (ex: as interfaces de entrada e navegação ao acessar a Amazon ou o Mercado Livre).
  * **Linha de Interação:** Divisão entre o cliente e a organização. Tudo acima da linha representa a jornada visível; tudo abaixo/atrás dela representa as engrenagens internas da empresa.
  * **Ações de Linha de Frente (Frontstage):** Interações humanas diretas e visíveis. Se o ponto de contato for um e-mail, por exemplo, mapeia os comandos operacionais passados para que os atendentes leiam e respondam o chamado corretamente.
  * **Ações de Bastidores (Backstage):** Atividades internas e invisíveis que dão sustentação direta à linha de frente.
  * **Sistemas de Suporte (Última Linha):** Softwares, processos internos, banco de dados e infraestrutura de hardware que alimentam as camadas superiores.
* **Gestão de Custos nos Pontos de Contato (Touchpoints):** Rastreia os momentos em que o cliente aciona a empresa. O "Caminho Personalizado" (atendimento humano) possui altíssimo custo operacional e baixa escalabilidade. Chatbots apresentam custo intermediário de tecnologia, enquanto as centrais de ajuda e FAQs são consideradas "sem custo" recorrente, promovendo autonomia ao cliente leigo sem inflacionar a operação.
* **Dinâmicas de Escopo (Divergência vs. Convergência):** Ao discutir o escopo, o time deve realizar um movimento de Divergência (abrir o escopo para levantar problemas, coletar dados qualitativos e mapear dores) seguido obrigatoriamente por uma condução para Convergir (afunilar e priorizar). Sem a convergência, os problemas levantados nunca são resolvidos. Essa priorização é amparada pela Tabela de Impacto x Esforço, equilibrando o ganho de UX com a complexidade técnica e linhas de código da engenharia.
* **Mitigação do Usuário no Escuro:** Para tarefas longas (como a suspensão de um processo para retomar da no dia seguinte), o sistema deve fornecer evidências físicas constantes de status (rastreabilidade, protocolos digitais de recebimento e notificações) para mitigar a ansiedade de stakeholders e usuários finais.
* **Pirâmide da Satisfação e Mapas de Sistema:** Modelos conceituais utilizados para mensurar como o serviço é percebido pelo usuário que o recebe, focando na percepção real do valor entregue (amplamente aplicados em cenários críticos de saúde e bem-estar).

---

## <img src="imagens/steps.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 1.3 Próximos Passos
Orientações práticas para o andamento dos estudos, leituras obrigatórias e execução das próximas atividades da disciplina:

* **Finalizar o pocket e apresentar o repositório:** o grupo 6 deve continuar a contribuir e finalizar o repositório seguindo o planejamento acordado durante as aulas de IHC.

---
<div align="right">
  <small style="opacity: 0.5;">Ícone por <a href="https://www.flaticon.com/br/autores/freepik" target="_blank">Freepik</a></small>
</div>