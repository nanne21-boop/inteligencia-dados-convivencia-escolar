# Plataforma Digital de Inteligência em Desenvolvimento Humano e Convivência Escolar
> **Status do Projeto:** Diagnóstico e Modelo Conceitual Aprovado (Extensão Universitária - UAM)

## 📌 Sobre o Projeto
Este repositório apresenta a documentação técnica e o modelo conceitual de um ecossistema analítico de dados voltado para a governança educacional e conformidade com a **LGPD (Lei Geral de Proteção de Dados)**. Desenvolvido como projeto de Extensão Universitária na **Universidade Anhembi Morumbi (UAM)** para o curso de **Big Data e Inteligência Analítica**, o projeto foi modelado a partir de uma imersão prática e diagnóstico territorial realizado no **Colégio Nicolau Kerpen**, no território do Rio Pequeno.

---

## 🚨 O Problema Central & Justificativa
O diagnóstico identificou uma severa sobrecarga na coordenação pedagógica frente à crescente demanda por suporte em desenvolvimento socioemocional e inclusão discente. Esse cenário é agravado por determinantes sociais:
*   **Trabalho e Renda:** Rotinas exaustivas dos responsáveis que geram dificuldades logísticas para manter terapias externas (fonoaudiologia/psicopedagogia) de forma constante.
*   **Acesso a Serviços:** Gargalos no sistema público de saúde e alto custo de consultórios particulares.

A ação justifica-se pela urgência em mitigar a sobrecarga da gestão, centralizando dados fragmentados para dar previsibilidade ao monitoramento de demandas socioemocionais.

---

## 📊 Arquitetura do Protótipo (Painel de Indicadores)
Atendendo às diretrizes de modelagem de dados e inteligência de gestão, o projeto estruturou o esqueleto técnico e funcional de um **Painel de Indicadores de Acolhimento**.

### 1. Protótipo Estrutural da Matriz de Dados
O painel opera conceitualmente como um banco de dados relacional alimentado quinzenalmente por meio de um checklist digital composto pelos seguintes campos:
*   `ID_Aluno:` Chave primária gerada de forma anônima e criptografada (ex: ALUNO_001), assegurando conformidade estrita com a **LGPD**.
*   `Módulo Fonoaudiologia:` Status qualitativo de evolução [Evolução Estável / Demanda de Encaminhamento].
*   `Módulo Psicopedagogia:` Frequência de suporte institucional [Regular / Ausente].
*   `Módulo Oficina Teatro:` Índice de Socialização e Expressão [Mapeado em escala de 1 a 5].
*   `Módulo Convivência Escolar:` Alertas preventivos de isolamento discente ou vulnerabilidade socioemocional.

### 2. Conjunto Mínimo de Indicadores (KPIs)
*   `IEA (Índice de Engajamento no Acolhimento):` Percentual de famílias que mantêm a constância e aderência às orientações pedagógicas em casa.
*   `TFM (Taxa de Frequência Multidisciplinar):` Monitoramento de assiduidade dos alunos prioritários nas redes internas de suporte.
*   `ICEQ (Índice de Clima Escolar Qualitativo):` Alinhamento estatístico baseado nos alertas preventivos coletados.

### 3. Rotina de Uso e Devolutiva à Comunidade
*   **Responsabilidade:** Governança e manutenção sob os cuidados diretos da coordenação pedagógica.
*   **Periodicidade:** Atualizações quinzenais automáticas no banco de dados analítico.
*   **Devolutiva:** Apresentação de relatórios e infográficos visuais agregados (sem qualquer exposição de dados individuais) durante as reuniões bimestrais de pais e mestres, engajando a comunidade.

---

## 🔬 Limites do Recorte & Moderação de Hipóteses
Em conformidade com as boas práticas de Big Data e integridade metodológica:
*   **Escopo:** O estudo delimita-se a um recorte territorial local específico, fundamentado na observação participante de um número restrito de cenários e participantes no Colégio Nicolau Kerpen.
*   **Moderação:** Os impactos esperados na melhoria da convivência e na redução de práticas de conflito (como o bullying) são registrados estritamente sob o caráter de **hipóteses e percepções qualitativas** a serem validadas quantitativamente no longo prazo, evitando afirmações causais absolutas de efeito imediato.

---

## 🎯 Conexão com as ODS
Alinhado diretamente ao **ODS 4 (Educação de Qualidade)** e à **Meta 4.a**, focando no desenho de infraestruturas escolares seguras, inclusivas e não violentas por meio da governança ética de dados.

---
*Projeto de impacto social desenvolvido por **Elaine de Brito Melo** como atividade extensionista de graduação.*
