# <img src="imagens/manual.png" alt="" width="32" style="vertical-align: middle; margin-right: 8px;"> 2. Guia de Acessibilidade

## 2.1 Diretrizes e Normas Adotadas

As diretrizes de acessibilidade adotadas neste projeto são fundamentadas na WCAG (Web Content Accessibility Guidelines), desenvolvida pelo W3C, e na ABNT NBR 17225:2025, que estabelece requisitos de acessibilidade para conteúdos e aplicações Web no contexto brasileiro. Essas referências fornecem critérios e recomendações para o desenvolvimento e a avaliação de interfaces digitais mais inclusivas e acessíveis.

A WCAG organiza suas recomendações em quatro princípios fundamentais — Perceptível, Operável, Compreensível e Robusto — e define critérios de sucesso classificados em três níveis de conformidade: A, AA e AAA. A ABNT NBR 17225:2025 complementa essas diretrizes ao consolidar requisitos de acessibilidade aplicáveis ao contexto brasileiro e incorporar recomendações voltadas à implementação e avaliação de conteúdos e aplicações Web. Neste trabalho, serão priorizados os níveis de conformidade A e AA, por representarem os requisitos mínimos e recomendados mais amplamente adotados nas avaliações de acessibilidade digital.

---

## 2.2 Critérios de Sucesso Principais

Os Critérios de Sucesso da WCAG representam requisitos verificáveis utilizados para avaliar a acessibilidade de um sistema digital. Cada critério está associado a um dos quatro princípios fundamentais da WCAG and classificado em um dos níveis de conformidade: A, **AA ou AAA.

O nível A representa os requisitos mínimos de acessibilidade, o nível AA contempla boas práticas amplamente recomendadas e frequentemente exigidas por legislação, enquanto o nível AAA corresponde ao mais alto grau de acessibilidade, sendo aplicado quando tecnicamente viável.

---

### 1. Princípio Perceptível

O conteúdo deve ser apresentado de forma que todos os usuários consigam percebê-lo, independentemente de limitações visuais, auditivas ou cognitivas.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 1.1.1 Conteúdo Não Textual | Imagens, ícones, gráficos e outros elementos visuais devem possuir alternativas textuais equivalentes. | Pessoas cegas e usuários de leitores de tela. | A | 5.2.1 – 5.2.4 e 5.2.6 |
| 1.2.2 Legendas | Vídeos gravados devem possuir legendas sincronizadas para conteúdos falados. | Pessoas surdas ou com deficiência auditiva. | A | 5.14.2 |
| 1.2.4 Legendas para Conteúdo ao Vivo | Transmissões ao vivo devem disponibilizar legendas em tempo real. | Pessoas surdas. | AA | 5.14.9 |
| 1.2.5 Audiodescrição | Informações visuais relevantes devem ser descritas verbalmente. | Pessoas cegas ou com baixa visão. | AA | 5.14.4 |
| 1.3.1 Informação e Relações | Estruturas visuais devem ser representadas semanticamente no código. | Usuários de tecnologias assistivas. | A | 5.3.1, 5.4.1, 5.5.1, 5.6.1 |
| 1.4.1 Uso da Cor | A cor não deve ser o único meio para transmitir informação. | Pessoas com daltonismo. | A | 5.11.1 |
| 1.4.3 Contraste Mínimo | Textos devem possuir contraste adequado em relação ao fundo. | Pessoas com baixa visão e idosos. | AA | 5.11.3 |
| 1.4.10 Reflow | O conteúdo deve adaptar-se a diferentes tamanhos de tela sem exigir rolagem horizontal excessiva. | Usuários com ampliação de tela. | AA | 5.10.4 |
| 1.4.11 Contraste de Componentes | Botões, campos e elementos interativos devem possuir contraste adequado. | Pessoas com baixa visão. | AA | 5.11.4 e 5.11.5 |

---

### 2. Princípio Operável

Todos os componentes da interface devem poder ser utilizados pelos usuários, independentemente do dispositivo ou método de interação empregado.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 2.1.1 Teclado | Todas as funcionalidades devem ser acessíveis sem o uso do mouse. | Pessoas com deficiência motora e usuários de leitores de tela. | A | 5.1.12 e 5.1.13 |
| 2.1.2 Sem Armadilha de Teclado | O usuário deve conseguir entrar e sair de qualquer elemento usando apenas o teclado. | Usuários de teclado. | A | 5.1.6 |
| 2.2.1 Ajuste de Tempo | Limites de tempo devem poder ser ajustados ou ampliados. | Pessoas com deficiência cognitiva. | A | 5.16.2 |
| 2.2.2 Pausar, Parar ou Ocultar | Conteúdos em movimento devem poder ser interrompidos. | Pessoas com TDAH e deficiência cognitiva. | A | 5.15.1 |
| 2.3.1 Três Flashes ou Abaixo do Limite | O conteúdo não pode apresentar flashes que provoquem convulsões. | Pessoas com epilepsia fotossensível. | A | 5.15.4 |
| 2.4.1 Ignorar Blocos | Deve existir mecanismo para pular menus e conteúdos repetitivos. | Usuários de teclado e leitores de tela. | A | 5.7.12 |
| 2.4.2 Página com Título | Cada página deve possuir título claro e descritivo. | Todos os usuários. | A | 5.13.1 |
| 2.4.7 Foco Visível | O foco do teclado deve ser claramente identificável. | Usuários de teclado. | AA | 5.1.1 |
| 2.5.8 Tamanho Mínimo do Alvo | Elementos clicáveis devem possuir área mínima adequada para interação. | Pessoas com mobilidade reduzida. | AA | 5.8.7 |

---

### 3. Princípio Compreensível

As informações e o funcionamento da interface devem ser fáceis de entender e previsíveis para os usuários.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 3.1.1 Idioma da Página | O idioma principal da página deve ser identificado corretamente. | Usuários de leitores de tela. | A | 5.13.2 |
| 3.1.2 Idioma de Partes | Trechos em idiomas diferentes devem ser marcados adequadamente. | Usuários de tecnologias assistivas. | AA | 5.13.3 |
| 3.2.1 Foco Não Deve Alterar Contexto | Receber foco não deve provocar mudanças inesperadas. | Pessoas com deficiência cognitiva. | A | 5.8.9 |
| 3.2.2 Entrada Não Deve Alterar Contexto | O preenchimento de campos não deve gerar alterações automáticas inesperadas. | Pessoas com deficiência cognitiva. | A | 5.8.10 |
| 3.2.3 Navegação Consistente | Menus e mecanismos de navegação devem manter consistência entre páginas. | Pessoas com autismo e TDAH. | AA | 5.7.15 |
| 3.3.1 Identificação de Erros | Erros devem ser apresentados claramente ao usuário. | Todos os usuários. | A | 5.9.9 |
| 3.3.2 Rótulos e Instruções | Campos devem possuir instruções adequadas de preenchimento. | Pessoas com deficiência cognitiva. | A | 5.9.1 e 5.9.4 |
| 3.3.3 Sugestão de Correção | O sistema deve indicar como corrigir erros identificados. | Todos os usuários. | AA | 5.9.10 |
| 3.3.4 Prevenção de Erros | Operações importantes devem permitir confirmação ou revisão. | Todos os usuários. | AA | 5.9.12 |

---

### 4. Princípio Robusto

O conteúdo deve ser compatível com diferentes navegadores, dispositivos e tecnologias assistivas.

| Critério (WCAG) | Descrição | Beneficia | Nível | Seção equivalente na NBR 17225 |
| :--- | :--- | :--- | :--- | :--- |
| 4.1.2 Nome, Função e Valor | Componentes devem informar corretamente seu nome, função e estado. | Usuários de leitores de tela. | A | 5.13.10 e 5.13.12 |
| 4.1.3 Mensagens de Status | Mudanças dinâmicas devem ser anunciadas adequadamente. | Pessoas cegas e usuários de leitores de tela. | AA | 5.13.8 |

---

### Resumo dos Níveis de Conformidade

| Nível | Objetivo |
|---------|---------|
| A | Requisitos mínimos indispensáveis para acessibilidade. |
| AA | Nível recomendado para sistemas web e aplicações governamentais. |
| AAA | Nível máximo de acessibilidade, aplicado quando possível. |

Durante a avaliação prática deste projeto, os critérios dos níveis *A* e *AA* serão priorizados, uma vez que representam os requisitos mais amplamente adotados em avaliações de acessibilidade digital.

---

## <img src="imagens/checklist.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 2.3 Checklists de Verificação
<details>
<summary><strong> 1. Princípio Perceptível</strong></summary>
<h3>1.1 Alternativas em Texto</h3>

<label><input class="wcag-check" id="wcag-111-1" type="checkbox"> Todas as imagens possuem texto alternativo (alt).</label><a href="6_referencias.html#ref-wcag-32">[32]</a><br>
<label><input class="wcag-check" id="wcag-111-2" type="checkbox"> Ícones possuem descrição acessível.</label><a href="6_referencias.html#ref-wcag-33">[33]</a><br>
<label><input class="wcag-check" id="wcag-111-3" type="checkbox"> Gráficos possuem descrição textual.</label><a href="6_referencias.html#ref-wcag-34">[34]</a><br>
<label><input class="wcag-check" id="wcag-111-4" type="checkbox"> Botões com ícones possuem nome acessível.</label><a href="6_referencias.html#ref-wcag-35">[35]</a>

<h3>1.2 Mídias Baseadas em Tempo</h3>

<label><input class="wcag-check" id="wcag-121-1" type="checkbox"> Áudios possuem transcrição.</label><a href="6_referencias.html#ref-wcag-36">[36]</a><br>
<label><input class="wcag-check" id="wcag-122-1" type="checkbox"> Vídeos possuem legendas.</label><a href="6_referencias.html#ref-wcag-37">[37]</a><br>
<label><input class="wcag-check" id="wcag-125-1" type="checkbox"> Vídeos possuem audiodescrição.</label><a href="6_referencias.html#ref-wcag-38">[38]</a><br>
<label><input class="wcag-check" id="wcag-124-1" type="checkbox"> Conteúdos ao vivo possuem legendas.</label><a href="6_referencias.html#ref-wcag-39">[39]</a><br>
<label><input class="wcag-check" id="wcag-126-1" type="checkbox"> Vídeos possuem interpretação em Libras.</label><a href="6_referencias.html#ref-wcag-40">[40]</a>

<h3>1.3 Adaptável</h3>

<label><input class="wcag-check" id="wcag-131-1" type="checkbox"> Cabeçalhos utilizam estrutura H1-H6 corretamente.</label><a href="6_referencias.html#ref-wcag-41">[41]</a><br>
<label><input class="wcag-check" id="wcag-131-2" type="checkbox"> Tabelas possuem marcação semântica.</label><a href="6_referencias.html#ref-wcag-42">[42]</a><br>
<label><input class="wcag-check" id="wcag-131-3" type="checkbox"> Listas utilizam UL/OL/LI.</label><a href="6_referencias.html#ref-wcag-43">[43]</a><br>
<label><input class="wcag-check" id="wcag-132-1" type="checkbox"> A ordem de leitura é lógica.</label><a href="6_referencias.html#ref-wcag-44">[44]</a><br>
<label><input class="wcag-check" id="wcag-133-1" type="checkbox"> Instruções não dependem apenas de cor.</label><a href="6_referencias.html#ref-wcag-45">[45]</a>

<h3>1.4 Distinguível</h3>

<label><input class="wcag-check" id="wcag-141-1" type="checkbox"> A cor não é o único meio de transmitir informação.</label><a href="6_referencias.html#ref-wcag-46">[46]</a><br>
<label><input class="wcag-check" id="wcag-143-1" type="checkbox"> Contraste mínimo de 4,5:1 para texto normal.</label><a href="6_referencias.html#ref-wcag-47">[47]</a><br>
<label><input class="wcag-check" id="wcag-143-2" type="checkbox"> Contraste mínimo de 3:1 para texto grande.</label><a href="6_referencias.html#ref-wcag-48">[48]</a><br>
<label><input class="wcag-check" id="wcag-144-1" type="checkbox"> O texto pode ser ampliado em até 200%.</label><a href="6_referencias.html#ref-wcag-49">[49]</a><br>
<label><input class="wcag-check" id="wcag-1410-1" type="checkbox"> Não há necessidade de rolagem horizontal excessiva.</label><a href="6_referencias.html#ref-wcag-50">[50]</a><br>
<label><input class="wcag-check" id="wcag-1411-1" type="checkbox"> Botões e componentes possuem contraste adequado.</label><a href="6_referencias.html#ref-wcag-51">[51]</a><br>
<label><input class="wcag-check" id="wcag-1412-1" type="checkbox"> O conteúdo continua funcional com espaçamento ampliado.</label><a href="6_referencias.html#ref-wcag-52">[52]</a>

</details>

<br>

<details>
<summary><strong> 2. Princípio Operável</strong></summary>

<h3>2.1 Acessível por Teclado</h3>

<label><input class="wcag-check" id="wcag-211" type="checkbox"> Todas as funcionalidades funcionam via teclado.</label><a href="6_referencias.html#ref-wcag-53">[53]</a><br>
<label><input class="wcag-check" id="wcag-212" type="checkbox"> Não existem armadilhas de teclado.</label><a href="6_referencias.html#ref-wcag-54">[54]</a><br>
<label><input class="wcag-check" id="wcag-214" type="checkbox"> Atalhos podem ser personalizados ou desativados.</label><a href="6_referencias.html#ref-wcag-55">[55]</a>

<h3>2.2 Tempo Suficiente</h3>

<label><input class="wcag-check" id="wcag-221" type="checkbox"> O usuário pode aumentar limites de tempo.</label><a href="6_referencias.html#ref-wcag-56">[56]</a><br>
<label><input class="wcag-check" id="wcag-222" type="checkbox"> Conteúdos em movimento podem ser pausados.</label><a href="6_referencias.html#ref-wcag-57">[57]</a><br>
<label><input class="wcag-check" id="wcag-226" type="checkbox"> Existe aviso antes da expiração da sessão.</label> <a href="6_referencias.html#ref-wcag-58">[58]</a>

<h3>2.3 Convulsões e Reações Físicas</h3>
<label><input class="wcag-check" id="wcag-231" type="checkbox"> O conteúdo não pisca mais de três vezes por segundo.</label><a href="6_referencias.html#ref-wcag-59">[59]</a><br>
<label><input class="wcag-check" id="wcag-233" type="checkbox"> Animações podem ser desativadas.</label><a href="6_referencias.html#ref-wcag-60">[60]</a>

<h3>2.4 Navegável</h3>

<label><input class="wcag-check" id="wcag-241" type="checkbox"> Existe mecanismo para pular blocos repetitivos.</label><a href="6_referencias.html#ref-wcag-61">[61]</a><br>
<label><input class="wcag-check" id="wcag-242" type="checkbox"> Todas as páginas possuem título.</label><a href="6_referencias.html#ref-wcag-62">[62]</a><br>
<label><input class="wcag-check" id="wcag-243" type="checkbox"> A ordem de foco é lógica.</label><a href="6_referencias.html#ref-wcag-63">[63]</a><br>
<label><input class="wcag-check" id="wcag-244" type="checkbox"> Os links possuem propósito claro.</label><a href="6_referencias.html#ref-wcag-64">[64]</a><br>
<label><input class="wcag-check" id="wcag-247" type="checkbox"> O foco do teclado é visível.</label><a href="6_referencias.html#ref-wcag-65">[65]</a>

<h3>2.5 Modalidades de Entrada</h3>

<label><input class="wcag-check" id="wcag-251" type="checkbox"> Gestos complexos possuem alternativa simples.</label><a href="6_referencias.html#ref-wcag-66">[66]</a><br>
<label><input class="wcag-check" id="wcag-257" type="checkbox"> Operações de arrastar possuem alternativa.</label><a href="6_referencias.html#ref-wcag-67">[67]</a><br>
<label><input class="wcag-check" id="wcag-253" type="checkbox"> O nome acessível corresponde ao texto visível.</label><a href="6_referencias.html#ref-wcag-68">[68]</a><br>
<label><input class="wcag-check" id="wcag-258" type="checkbox"> Alvos possuem tamanho mínimo adequado.</label> <a href="6_referencias.html#ref-wcag-69">[69]</a>

</details>

<details>
<summary><strong> 3. Princípio Compreensível</strong></summary>

<h3>3.1 Legível</h3>

<label><input class="wcag-check" id="wcag-311" type="checkbox"> O idioma principal da página está definido.</label><a href="6_referencias.html#ref-wcag-70">[70]</a><br>
<label><input class="wcag-check" id="wcag-312" type="checkbox"> Trechos em outros idiomas estão identificados corretamente.</label><a href="6_referencias.html#ref-wcag-71">[71]</a><br>
<label><input class="wcag-check" id="wcag-313" type="checkbox"> Palavras incomuns possuem definição disponível.</label><a href="6_referencias.html#ref-wcag-72">[72]</a><br>
<label><input class="wcag-check" id="wcag-314" type="checkbox"> Abreviações e siglas possuem explicação.</label><a href="6_referencias.html#ref-wcag-73">[73]</a><br>
<label><input class="wcag-check" id="wcag-315" type="checkbox"> Existe versão simplificada para conteúdos complexos.</label><a href="6_referencias.html#ref-wcag-74">[74]</a>

<h3>3.2 Previsível</h3>

<label><input class="wcag-check" id="wcag-321" type="checkbox"> Receber foco não altera o contexto inesperadamente.</label><a href="6_referencias.html#ref-wcag-75">[75]</a><br>
<label><input class="wcag-check" id="wcag-322" type="checkbox"> Preencher campos não provoca mudanças automáticas inesperadas.</label><a href="6_referencias.html#ref-wcag-76">[76]</a><br>
<label><input class="wcag-check" id="wcag-323" type="checkbox"> A navegação é consistente entre páginas.</label><a href="6_referencias.html#ref-wcag-77">[77]</a><br>
<label><input class="wcag-check" id="wcag-324" type="checkbox"> Elementos equivalentes possuem identificação consistente.</label><a href="6_referencias.html#ref-wcag-78">[78]</a><br>
<label><input class="wcag-check" id="wcag-326" type="checkbox"> Os mecanismos de ajuda aparecem sempre na mesma posição.</label><a href="6_referencias.html#ref-wcag-79">[79]</a>

<h3>3.3 Assistência de Entrada</h3>

<label><input class="wcag-check" id="wcag-331" type="checkbox"> Erros são identificados claramente.</label><a href="6_referencias.html#ref-wcag-80">[80]</a><br>
<label><input class="wcag-check" id="wcag-332" type="checkbox"> Campos possuem rótulos e instruções adequadas.</label><a href="6_referencias.html#ref-wcag-81">[81]</a><br>
<label><input class="wcag-check" id="wcag-333" type="checkbox"> O sistema sugere correções para erros.</label><a href="6_referencias.html#ref-wcag-82">[82]</a><br>

<label><input class="wcag-check" id="wcag-334" type="checkbox"> Existe confirmação para ações críticas.</label><a href="6_referencias.html#ref-wcag-83">[83]</a><br>
<label><input class="wcag-check" id="wcag-335" type="checkbox"> Existe ajuda contextualizada ao usuário.</label><a href="6_referencias.html#ref-wcag-84">[84]</a><br>
<label><input class="wcag-check" id="wcag-336" type="checkbox"> O usuário pode revisar informações antes do envio final.</label><a href="6_referencias.html#ref-wcag-85">[85]</a><br>
<label><input class="wcag-check" id="wcag-337" type="checkbox"> Informações já fornecidas não precisam ser digitadas novamente.</label><a href="6_referencias.html#ref-wcag-86">[86]</a><br>
<label><input class="wcag-check" id="wcag-338" type="checkbox"> O login não depende de testes cognitivos complexos.</label><a href="6_referencias.html#ref-wcag-87">[87]</a>

</details>

<br>

<details>
<summary><strong> 4. Princípio Robusto</strong></summary>

<h3>4.1 Compatível</h3>

<label><input class="wcag-check" id="wcag-412" type="checkbox"> Componentes informam corretamente nome, função e estado.</label><a href="6_referencias.html#ref-wcag-88">[88]</a><br>
<label><input class="wcag-check" id="wcag-413" type="checkbox"> Mensagens de status são anunciadas para tecnologias assistivas.</label> <a href="6_referencias.html#ref-wcag-89">[89]</a>

<h3>Compatibilidade Geral</h3>

<label><input class="wcag-check" id="wcag-robusto-1" type="checkbox"> O sistema funciona adequadamente em diferentes navegadores.</label><a href="6_referencias.html#ref-wcag-90">[90]</a><br>
<label><input class="wcag-check" id="wcag-robusto-2" type="checkbox"> O sistema funciona adequadamente com leitores de tela.</label><a href="6_referencias.html#ref-wcag-91">[91]</a><br>
<label><input class="wcag-check" id="wcag-robusto-3" type="checkbox"> O sistema funciona adequadamente em dispositivos móveis.</label><a href="6_referencias.html#ref-wcag-92">[92]</a><br>
<label><input class="wcag-check" id="wcag-robusto-4" type="checkbox"> Mudanças dinâmicas são comunicadas corretamente ao usuário.</label><a href="6_referencias.html#ref-wcag-93">[93]</a>

</details>

<h2>Dashboard de Acessibilidade</h2>

<!-- Título do gráfico -->
<h3 style="text-align: center; margin-top: 30px;"> Gráfico grau de conformidade</h3>

<!-- Container com 3 gráficos circulares (um por nível) -->
<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: stretch; gap: 40px; margin: 20px 0;">
  
  <!-- Nível A -->
  <div style="display: flex; flex-direction: column; align-items: center; min-width: 180px; flex: 1 1 180px;">
    <h4 style="margin: 0 0 12px 0; text-align: center; font-size: 1.1em;">Nível A</h4>
    <div style="width: 150px; height: 150px; position: relative;">
      <canvas id="graficoNivelA" width="150" height="150"></canvas>
    </div>
    <div style="margin-top: 12px; font-weight: bold; text-align: center; font-size: 0.95em;">
      <span id="contador-A">0/0</span> – <span id="percentual-A">0%</span>
    </div>
  </div>

  <!-- Nível AA -->
  <div style="display: flex; flex-direction: column; align-items: center; min-width: 180px; flex: 1 1 180px;">
    <h4 style="margin: 0 0 12px 0; text-align: center; font-size: 1.1em;">Nível AA</h4>
    <div style="width: 150px; height: 150px; position: relative;">
      <canvas id="graficoNivelAA" width="150" height="150"></canvas>
    </div>
    <div style="margin-top: 12px; font-weight: bold; text-align: center; font-size: 0.95em;">
      <span id="contador-AA">0/0</span> – <span id="percentual-AA">0%</span>
    </div>
  </div>

  <!-- Nível AAA -->
  <div style="display: flex; flex-direction: column; align-items: center; min-width: 180px; flex: 1 1 180px;">
    <h4 style="margin: 0 0 12px 0; text-align: center; font-size: 1.1em;">Nível AAA</h4>
    <div style="width: 150px; height: 150px; position: relative;">
      <canvas id="graficoNivelAAA" width="150" height="150"></canvas>
    </div>
    <div style="margin-top: 12px; font-weight: bold; text-align: center; font-size: 0.95em;">
      <span id="contador-AAA">0/0</span> – <span id="percentual-AAA">0%</span>
    </div>
  </div>

</div>
<br>


<script>
  console.log("Chart:", typeof Chart);
</script>

<script>
  document.addEventListener("DOMContentLoaded", function () {

    // ---------- VERIFICA SE O CHART.JS FOI CARREGADO ----------
    if (typeof Chart === 'undefined') {
        console.error('Chart.js não carregado!');
        return;
    }

    // ---------- CHECKBOXES ----------
    document.querySelectorAll(".wcag-check").forEach((checkbox) => {
        const key = checkbox.id;
        checkbox.checked = localStorage.getItem(key) === "true";
        checkbox.addEventListener("change", () => {
            localStorage.setItem(key, checkbox.checked);
            atualizarDashboards();
        });
    });

    // ---------- DEFINIÇÕES DOS NÍVEIS ----------
    const niveis = {
        A: [
            "wcag-111-1","wcag-111-2","wcag-111-3","wcag-111-4",
            "wcag-121-1","wcag-122-1",
            "wcag-131-1","wcag-131-2","wcag-131-3",
            "wcag-133-1",
            "wcag-141-1",
            "wcag-211","wcag-212","wcag-214",
            "wcag-221","wcag-222",
            "wcag-231",
            "wcag-241","wcag-242",
            "wcag-311",
            "wcag-321","wcag-322",
            "wcag-326",
            "wcag-331","wcag-332",
            "wcag-412"
        ],
        AA: [
            "wcag-124-1","wcag-125-1",
            "wcag-143-1",
            "wcag-1410-1",
            "wcag-1411-1",
            "wcag-247",
            "wcag-258",
            "wcag-312",
            "wcag-323",
            "wcag-333",
            "wcag-334",
            "wcag-413"
        ],
        AAA: [
            "wcag-226","wcag-233",
            "wcag-126-1",
            "wcag-315",
            "wcag-335"
        ]
    };

    // ---------- FUNÇÃO AUXILIAR: PERCENTUAL ----------
    function percentual(ids) {
        const marcados = ids.filter(id => {
            const el = document.getElementById(id);
            return el && el.checked;
        }).length;
        const total = ids.length;
        return { marcados, total, percentual: Math.round((marcados / total) * 100) };
    }

    // ---------- VARIÁVEIS DOS GRÁFICOS ----------
    let graficoNivelA, graficoNivelAA, graficoNivelAAA;

    // ---------- FUNÇÃO PARA CRIAR UM GRÁFICO DOUGHNUT ----------
    function criarGraficoNivel(canvasId, nivelKey, cor) {
        const canvas = document.getElementById(canvasId);
        if (!canvas) {
            console.error(`Canvas ${canvasId} não encontrado!`);
            return null;
        }
        const ctx = canvas.getContext('2d');
        if (!ctx) {
            console.error(`Não foi possível obter contexto 2D para ${canvasId}`);
            return null;
        }

        const { marcados, total, percentual: pct } = percentual(niveis[nivelKey]);
        const naoMarcados = total - marcados;
         
        const contadorEl = document.getElementById(`contador-${nivelKey}`);
        const corTexto = contadorEl ? getComputedStyle(contadorEl).color : '#ffffff';

        try {
            return new Chart(ctx, {
                type: 'doughnut',
                data: {
                    labels: ['Conforme', 'Não conforme'],
                    datasets: [{
                        data: [marcados, naoMarcados],
                        backgroundColor: [cor, '#ecf0f1'],
                        borderWidth: 0
                    }]
                },
                options: {
                    cutout: '75%',
                    responsive: false,
                    plugins: {
                        legend: { display: false },
                        tooltip: { enabled: true }
                    }
                },
                plugins: [{
                    id: 'centralText',
                    beforeDraw: function(chart) {
                        const { width, height, ctx } = chart;
                        ctx.save();
                        const text = `${pct}%`;
                        const fontSize = Math.min(width, height) * 0.2;
                        ctx.font = `bold ${fontSize}px Arial`;
                        ctx.textAlign = 'center';
                        ctx.textBaseline = 'middle';
                        ctx.fillStyle = corTexto;
                        ctx.fillText(text, width / 2, height / 2);
                        ctx.restore();
                    }
                }]
            });
        } catch (e) {
            console.error(`Erro ao criar gráfico ${canvasId}:`, e);
            return null;
        }
    }

    // ---------- ATUALIZAR TODOS OS GRÁFICOS ----------
    function atualizarDashboards() {
        try {
            // 1. Destruir gráficos antigos
            if (graficoNivelA) { graficoNivelA.destroy(); graficoNivelA = null; }
            if (graficoNivelAA) { graficoNivelAA.destroy(); graficoNivelAA = null; }
            if (graficoNivelAAA) { graficoNivelAAA.destroy(); graficoNivelAAA = null; }

            // 2. Criar gráficos dos níveis
            graficoNivelA = criarGraficoNivel('graficoNivelA', 'A', '#27ae60');
            graficoNivelAA = criarGraficoNivel('graficoNivelAA', 'AA', '#2980b9');
            graficoNivelAAA = criarGraficoNivel('graficoNivelAAA', 'AAA', '#8e44ad');

            // 3. Atualizar contadores e percentuais
            ['A', 'AA', 'AAA'].forEach(nivel => {
                const { marcados, total, percentual: pct } = percentual(niveis[nivel]);
                const contadorEl = document.getElementById(`contador-${nivel}`);
                const percentualEl = document.getElementById(`percentual-${nivel}`);
                if (contadorEl) contadorEl.textContent = `${marcados}/${total}`;
                if (percentualEl) percentualEl.textContent = `${pct}%`;
            });

        } catch (e) {
            console.error('Erro ao atualizar dashboards:', e);
        }
    }

    // ---------- INICIALIZA ----------
    setTimeout(atualizarDashboards, 100);
  });
</script>

---
<div align="right">
  <small style="opacity: 0.5;">Ícone por <a href="https://www.flaticon.com/br/autores/freepik" target="_blank">Freepik</a></small>
</div>