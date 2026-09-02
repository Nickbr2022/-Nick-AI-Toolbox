# Curadoria: 7 projetos open source de IA

Avaliação feita em 1º de setembro de 2026 com base nos repositórios oficiais, documentação disponível, atividade recente, utilidade para Nick e sobreposição com as ferramentas já catalogadas.

## Incorporados

### 1. DeepTutor

- Oficial: https://github.com/HKUDS/DeepTutor
- Uso recomendado: aprendizagem personalizada, leitura guiada, perguntas, quizzes e bases de conhecimento.
- Aplicação prática: estudos de IA, gemologia, Pine Script e apoio aos materiais escolares do Joaquim.
- Situação observada: projeto ativo, licença Apache 2.0, Python 3.11+ e interface Next.js.
- Cuidado: é uma plataforma completa; exige configuração e recursos maiores do que uma skill simples.

### 2. AI Hedge Fund

- Oficial: https://github.com/virattt/ai-hedge-fund
- Uso recomendado: laboratório educacional de análise de mercado com múltiplos agentes.
- Aplicação prática: referência para evoluir Radar B3, análises de BTC/cripto e comparação de teses.
- Cuidado: não deve operar dinheiro real nem ser tratado como recomendação financeira sem validação, backtest, controles de risco e revisão humana.

### 3. Open WebUI

- Oficial: https://github.com/open-webui/open-webui
- Uso recomendado: interface própria para modelos locais e APIs compatíveis com OpenAI, memória, RAG, ferramentas e automações.
- Aplicação prática: possível central privada de IA para joias, trading e documentos.
- Situação: já constava no Nick AI Toolbox; foi mantido sem duplicação.
- Cuidado: implantação e segurança exigem Docker/servidor, atualizações e gestão de credenciais.

## Não incorporados agora

### OpenViking

- Oficial: https://github.com/volcengine/OpenViking
- Motivo: camada de contexto para agentes com valor principalmente de infraestrutura; sobrepõe recursos já disponíveis em Open WebUI, DeepTutor e outras ferramentas do Toolbox.

### Headroom

- Oficial atual: https://github.com/headroomlabs-ai/headroom
- Motivo: otimização e compressão de contexto útil para desenvolvedores, mas sem ganho direto suficiente nos fluxos atuais de Nick.

### Khoj

- Oficial: https://github.com/khoj-ai/khoj
- Motivo: bom “segundo cérebro” autohospedado, porém sobreposto ao Open WebUI e ao DeepTutor. Adicionar agora aumentaria manutenção sem ampliar muito a capacidade prática.

### Letta

- Endereço mostrado: https://github.com/letta-ai/letta
- Motivo: o próprio README informa que esse repositório passou a ser uma página de apresentação e que o código atual está em `letta-ai/letta-code`. Portanto, incorporar o endereço antigo criaria uma referência enganosa.
- Reavaliar somente se houver um projeto específico de agentes persistentes que justifique adotar a base atual.

## Decisão

Foram adicionados à lista de prioridades apenas DeepTutor e AI Hedge Fund. Open WebUI foi mantido, pois já estava corretamente registrado. Nenhum fork integral foi criado: o Toolbox permanece leve, organizado e ligado às fontes oficiais para receber atualizações dos mantenedores.
