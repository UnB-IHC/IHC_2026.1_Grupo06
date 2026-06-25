# <img src="imagens/manual.png" alt="" width="32" style="vertical-align: middle; margin-right: 8px;"> 2. Guia de Acessibilidade

Este guia reúne os principais parâmetros e regulamentações de acessibilidade digital adotados no cenário nacional e internacional. O objetivo é estabelecer uma base sólida de critérios de verificação para garantir que interfaces atendam a todos os perfis de usuários.

---

## <img src="imagens/norm.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 2.1 Diretrizes e Normas Adotadas
> <img src="imagens/law.png" alt="" width="18" style="vertical-align: middle; margin-right: 4px;"> **Foco em Acessibilidade:** Detalhe aqui como os padrões eMAG (Governo Eletrônico) e WCAG (W3C) conversam entre si e quais níveis de conformidade (A, AA, AAA) são o alvo desta análise.

Escreva o conteúdo dos subtópicos da norma aqui...

---

## <img src="imagens/criteria.png" alt="" width="22" style="vertical-align: middle; margin-right: 6px;"> 2.2 Critérios de Sucesso Principais
Os Critérios de Sucesso da WCAG representam requisitos verificáveis utilizados para avaliar a acessibilidade de um sistema digital. Cada critério está associado a um dos quatro princípios fundamentais da WCAG e classificado em um dos níveis de conformidade: *A, **AA* ou *AAA*.

O nível *A* representa os requisitos mínimos de acessibilidade, o nível *AA* contempla boas práticas amplamente recomendadas e frequentemente exigidas por legislação, enquanto o nível *AAA* corresponde ao mais alto grau de acessibilidade, sendo aplicado quando tecnicamente viável.

---

### 1. Princípio Perceptível

O conteúdo deve ser apresentado de forma que todos os usuários consigam percebê-lo, independentemente de limitações visuais, auditivas ou cognitivas.

| Critério | Descrição | Beneficia | Nível |
|-----------|-----------|-----------|---------|
| 1.1.1 Conteúdo Não Textual | Imagens, ícones, gráficos e outros elementos visuais devem possuir alternativas textuais equivalentes. | Pessoas cegas e usuários de leitores de tela. | A |
| 1.2.2 Legendas | Vídeos gravados devem possuir legendas sincronizadas para conteúdos falados. | Pessoas surdas ou com deficiência auditiva. | A |
| 1.2.4 Legendas para Conteúdo ao Vivo | Transmissões ao vivo devem disponibilizar legendas em tempo real. | Pessoas surdas. | AA |
| 1.2.5 Audiodescrição | Informações visuais relevantes devem ser descritas verbalmente. | Pessoas cegas ou com baixa visão. | AA |
| 1.3.1 Informação e Relações | Estruturas visuais devem ser representadas semanticamente no código. | Usuários de tecnologias assistivas. | A |
| 1.4.1 Uso da Cor | A cor não deve ser o único meio para transmitir informação. | Pessoas com daltonismo. | A |
| 1.4.3 Contraste Mínimo | Textos devem possuir contraste adequado em relação ao fundo. | Pessoas com baixa visão e idosos. | AA |
| 1.4.10 Reflow | O conteúdo deve adaptar-se a diferentes tamanhos de tela sem exigir rolagem horizontal excessiva. | Usuários com ampliação de tela. | AA |
| 1.4.11 Contraste de Componentes | Botões, campos e elementos interativos devem possuir contraste adequado. | Pessoas com baixa visão. | AA |

---

### 2. Princípio Operável

Todos os componentes da interface devem poder ser utilizados pelos usuários, independentemente do dispositivo ou método de interação empregado.

| Critério | Descrição | Beneficia | Nível |
|-----------|-----------|-----------|---------|
| 2.1.1 Teclado | Todas as funcionalidades devem ser acessíveis sem o uso do mouse. | Pessoas com deficiência motora e usuários de leitores de tela. | A |
| 2.1.2 Sem Armadilha de Teclado | O usuário deve conseguir entrar e sair de qualquer elemento usando apenas o teclado. | Usuários de teclado. | A |
| 2.2.1 Ajuste de Tempo | Limites de tempo devem poder ser ajustados ou ampliados. | Pessoas com deficiência cognitiva. | A |
| 2.2.2 Pausar, Parar ou Ocultar | Conteúdos em movimento devem poder ser interrompidos. | Pessoas com TDAH e deficiência cognitiva. | A |
| 2.3.1 Três Flashes ou Abaixo do Limite | O conteúdo não pode apresentar flashes que provoquem convulsões. | Pessoas com epilepsia fotossensível. | A |
| 2.4.1 Ignorar Blocos | Deve existir mecanismo para pular menus e conteúdos repetitivos. | Usuários de teclado e leitores de tela. | A |
| 2.4.2 Página com Título | Cada página deve possuir título claro e descritivo. | Todos os usuários. | A |
| 2.4.7 Foco Visível | O foco do teclado deve ser claramente identificável. | Usuários de teclado. | AA |
| 2.5.8 Tamanho Mínimo do Alvo | Elementos clicáveis devem possuir área mínima adequada para interação. | Pessoas com mobilidade reduzida. | AA |

---

### 3. Princípio Compreensível
As informações e o funcionamento da interface devem ser fáceis de entender e previsíveis para os usuários.

| Critério | Descrição | Beneficia | Nível |
|-----------|-----------|-----------|---------|
| 3.1.1 Idioma da Página | O idioma principal da página deve ser identificado corretamente. | Usuários de leitores de tela. | A |
| 3.1.2 Idioma de Partes | Trechos em idiomas diferentes devem ser marcados adequadamente. | Usuários de tecnologias assistivas. | AA |
| 3.2.1 Foco Não Deve Alterar Contexto | Receber foco não deve provocar mudanças inesperadas. | Pessoas com deficiência cognitiva. | A |
| 3.2.2 Entrada Não Deve Alterar Contexto | O preenchimento de campos não deve gerar alterações automáticas inesperadas. | Pessoas com deficiência cognitiva. | A |
| 3.2.3 Navegação Consistente | Menus e mecanismos de navegação devem manter consistência entre páginas. | Pessoas com autismo e TDAH. | AA |
| 3.3.1 Identificação de Erros | Erros devem ser apresentados claramente ao usuário. | Todos os usuários. | A |
| 3.3.2 Rótulos e Instruções | Campos devem possuir instruções adequadas de preenchimento. | Pessoas com deficiência cognitiva. | A |
| 3.3.3 Sugestão de Correção | O sistema deve indicar como corrigir erros identificados. | Todos os usuários. | AA |
| 3.3.4 Prevenção de Erros | Operações importantes devem permitir confirmação ou revisão. | Todos os usuários. | AA |

---

### 4. Princípio Robusto

O conteúdo deve ser compatível com diferentes navegadores, dispositivos e tecnologias assistivas.

| Critério | Descrição | Beneficia | Nível |
|-----------|-----------|-----------|---------|
| 4.1.2 Nome, Função e Valor | Componentes devem informar corretamente seu nome, função e estado. | Usuários de leitores de tela. | A |
| 4.1.3 Mensagens de Status | Mudanças dinâmicas devem ser anunciadas adequadamente. | Pessoas cegas e usuários de leitores de tela. | AA |

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

<label><input class="wcag-check" id="wcag-111-1" type="checkbox"> Todas as imagens possuem texto alternativo (alt).</label><br>
<label><input class="wcag-check" id="wcag-111-2" type="checkbox"> Ícones possuem descrição acessível.</label><br>
<label><input class="wcag-check" id="wcag-111-3" type="checkbox"> Gráficos possuem descrição textual.</label><br>
<label><input class="wcag-check" id="wcag-111-4" type="checkbox"> Botões com ícones possuem nome acessível.</label>

<h3>1.2 Mídias Baseadas em Tempo</h3>

<label><input class="wcag-check" id="wcag-121-1" type="checkbox"> Áudios possuem transcrição.</label><br>
<label><input class="wcag-check" id="wcag-122-1" type="checkbox"> Vídeos possuem legendas.</label><br>
<label><input class="wcag-check" id="wcag-125-1" type="checkbox"> Vídeos possuem audiodescrição.</label><br>
<label><input class="wcag-check" id="wcag-124-1" type="checkbox"> Conteúdos ao vivo possuem legendas.</label><br>
<label><input class="wcag-check" id="wcag-126-1" type="checkbox"> Vídeos possuem interpretação em Libras.</label>

<h3>1.3 Adaptável</h3>

<label><input class="wcag-check" id="wcag-131-1" type="checkbox"> Cabeçalhos utilizam estrutura H1-H6 corretamente.</label><br>
<label><input class="wcag-check" id="wcag-131-2" type="checkbox"> Tabelas possuem marcação semântica.</label><br>
<label><input class="wcag-check" id="wcag-131-3" type="checkbox"> Listas utilizam UL/OL/LI.</label><br>
<label><input class="wcag-check" id="wcag-132-1" type="checkbox"> A ordem de leitura é lógica.</label><br>
<label><input class="wcag-check" id="wcag-133-1" type="checkbox"> Instruções não dependem apenas de cor.</label>

<h3>1.4 Distinguível</h3>

<label><input class="wcag-check" id="wcag-141-1" type="checkbox"> A cor não é o único meio de transmitir informação.</label><br>
<label><input class="wcag-check" id="wcag-143-1" type="checkbox"> Contraste mínimo de 4,5:1 para texto normal.</label><br>
<label><input class="wcag-check" id="wcag-143-2" type="checkbox"> Contraste mínimo de 3:1 para texto grande.</label><br>
<label><input class="wcag-check" id="wcag-144-1" type="checkbox"> O texto pode ser ampliado em até 200%.</label><br>
<label><input class="wcag-check" id="wcag-1410-1" type="checkbox"> Não há necessidade de rolagem horizontal excessiva.</label><br>
<label><input class="wcag-check" id="wcag-1411-1" type="checkbox"> Botões e componentes possuem contraste adequado.</label><br>
<label><input class="wcag-check" id="wcag-1412-1" type="checkbox"> O conteúdo continua funcional com espaçamento ampliado.</label>

</details>

<br>

<details>
<summary><strong> 2. Princípio Operável</strong></summary>

<h3>2.1 Acessível por Teclado</h3>

<label><input class="wcag-check" id="wcag-211" type="checkbox"> Todas as funcionalidades funcionam via teclado.</label><br>
<label><input class="wcag-check" id="wcag-212" type="checkbox"> Não existem armadilhas de teclado.</label><br>
<label><input class="wcag-check" id="wcag-214" type="checkbox"> Atalhos podem ser personalizados ou desativados.</label>

<h3>2.2 Tempo Suficiente</h3>

<label><input class="wcag-check" id="wcag-221" type="checkbox"> O usuário pode aumentar limites de tempo.</label><br>
<label><input class="wcag-check" id="wcag-222" type="checkbox"> Conteúdos em movimento podem ser pausados.</label><br>
<label><input class="wcag-check" id="wcag-226" type="checkbox"> Existe aviso antes da expiração da sessão.</label>

<h3>2.3 Convulsões e Reações Físicas</h3>
<label><input class="wcag-check" id="wcag-231" type="checkbox"> O conteúdo não pisca mais de três vezes por segundo.</label><br>
<label><input class="wcag-check" id="wcag-233" type="checkbox"> Animações podem ser desativadas.</label>

<h3>2.4 Navegável</h3>

<label><input class="wcag-check" id="wcag-241" type="checkbox"> Existe mecanismo para pular blocos repetitivos.</label><br>
<label><input class="wcag-check" id="wcag-242" type="checkbox"> Todas as páginas possuem título.</label><br>
<label><input class="wcag-check" id="wcag-243" type="checkbox"> A ordem de foco é lógica.</label><br>
<label><input class="wcag-check" id="wcag-244" type="checkbox"> Os links possuem propósito claro.</label><br>
<label><input class="wcag-check" id="wcag-247" type="checkbox"> O foco do teclado é visível.</label>

<h3>2.5 Modalidades de Entrada</h3>

<label><input class="wcag-check" id="wcag-251" type="checkbox"> Gestos complexos possuem alternativa simples.</label><br>
<label><input class="wcag-check" id="wcag-257" type="checkbox"> Operações de arrastar possuem alternativa.</label><br>
<label><input class="wcag-check" id="wcag-253" type="checkbox"> O nome acessível corresponde ao texto visível.</label><br>
<label><input class="wcag-check" id="wcag-258" type="checkbox"> Alvos possuem tamanho mínimo adequado.</label>

</details>

<details>
<summary><strong> 3. Princípio Compreensível</strong></summary>

<h3>3.1 Legível</h3>

<label><input class="wcag-check" id="wcag-311" type="checkbox"> O idioma principal da página está definido.</label><br>
<label><input class="wcag-check" id="wcag-312" type="checkbox"> Trechos em outros idiomas estão identificados corretamente.</label><br>
<label><input class="wcag-check" id="wcag-313" type="checkbox"> Palavras incomuns possuem definição disponível.</label><br>
<label><input class="wcag-check" id="wcag-314" type="checkbox"> Abreviações e siglas possuem explicação.</label><br>
<label><input class="wcag-check" id="wcag-315" type="checkbox"> Existe versão simplificada para conteúdos complexos.</label>

<h3>3.2 Previsível</h3>

<label><input class="wcag-check" id="wcag-321" type="checkbox"> Receber foco não altera o contexto inesperadamente.</label><br>
<label><input class="wcag-check" id="wcag-322" type="checkbox"> Preencher campos não provoca mudanças automáticas inesperadas.</label><br>
<label><input class="wcag-check" id="wcag-323" type="checkbox"> A navegação é consistente entre páginas.</label><br>
<label><input class="wcag-check" id="wcag-324" type="checkbox"> Elementos equivalentes possuem identificação consistente.</label><br>
<label><input class="wcag-check" id="wcag-326" type="checkbox"> Os mecanismos de ajuda aparecem sempre na mesma posição.</label>

<h3>3.3 Assistência de Entrada</h3>

<label><input class="wcag-check" id="wcag-331" type="checkbox"> Erros são identificados claramente.</label><br>
<label><input class="wcag-check" id="wcag-332" type="checkbox"> Campos possuem rótulos e instruções adequadas.</label><br>
<label><input class="wcag-check" id="wcag-333" type="checkbox"> O sistema sugere correções para erros.</label><br>

<label><input class="wcag-check" id="wcag-334" type="checkbox"> Existe confirmação para ações críticas.</label><br>
<label><input class="wcag-check" id="wcag-335" type="checkbox"> Existe ajuda contextualizada ao usuário.</label><br>
<label><input class="wcag-check" id="wcag-336" type="checkbox"> O usuário pode revisar informações antes do envio final.</label><br>
<label><input class="wcag-check" id="wcag-337" type="checkbox"> Informações já fornecidas não precisam ser digitadas novamente.</label><br>
<label><input class="wcag-check" id="wcag-338" type="checkbox"> O login não depende de testes cognitivos complexos.</label>

</details>

<br>

<details>
<summary><strong> 4. Princípio Robusto</strong></summary>

<h3>4.1 Compatível</h3>

<label><input class="wcag-check" id="wcag-412" type="checkbox"> Componentes informam corretamente nome, função e estado.</label><br>
<label><input class="wcag-check" id="wcag-413" type="checkbox"> Mensagens de status são anunciadas para tecnologias assistivas.</label>

<h3>Compatibilidade Geral</h3>

<label><input class="wcag-check" id="wcag-robusto-1" type="checkbox"> O sistema funciona adequadamente em diferentes navegadores.</label><br>
<label><input class="wcag-check" id="wcag-robusto-2" type="checkbox"> O sistema funciona adequadamente com leitores de tela.</label><br>
<label><input class="wcag-check" id="wcag-robusto-3" type="checkbox"> O sistema funciona adequadamente em dispositivos móveis.</label><br>
<label><input class="wcag-check" id="wcag-robusto-4" type="checkbox"> Mudanças dinâmicas são comunicadas corretamente ao usuário.</label>

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