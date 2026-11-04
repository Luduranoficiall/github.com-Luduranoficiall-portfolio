# Portfólio — Lucas Duran (luduranoficiall)

Índice de todos os projetos e jogos publicados, separados por tipo. Cada item aqui tem repositório próprio (este repositório não tem código de projeto nenhum, só a lista) e, quando existe, demo ao vivo.

Site principal, com página própria de cada projeto: https://www.luduranoficiall.com/projetos

## Site

### EXTRAORDINÁRIA.AI — site corporativo com chatbot e dashboard de leads

Site corporativo + API para empresa de transformação com IA: landing pública, formulário de contato com notificação de leads, chatbot integrado e dashboard restrito ao CEO com analytics e auditoria.

[Ver online](https://extraordinaria-ai.vercel.app)

### Luduranoficiall.com — site institucional com IA e captação via WhatsApp

Site institucional em Next.js com chat de IA (Google Gemini) integrado, catálogo de serviços e preços, e captação direta pelo WhatsApp em todo o site.

[Ver online](https://www.luduranoficiall.com)

### Site Premium para Escritório de Advocacia

Site institucional para escritório de advocacia (demonstração de portfólio) com painel admin, área do cliente e chatbot de triagem, autenticação real com JWT, banco de dados persistente e 39 testes automatizados.

## Aplicativo

### App de agendamento com fila de espera para barbearia/salão/clínica

App de agendamento (Android, iOS e web) com horário disponível em tempo real, fila de espera automática quando lota, e lembrete pro cliente perto do horário. Pensado pra barbearia, salão e clínica.

[Ver online](https://luduran-agendamento-demo.vercel.app)

### App de Clima com assistente de IA

Previsão do tempo nativa Android: localização em tempo real, busca de qualquer cidade, previsão horária e de 7 dias, 3 idiomas, e um assistente de IA que dá conselho prático a partir da previsão real.

### App de pedido direto sem taxa de marketplace

App de pedido/delivery (Android, iOS e web) pra restaurante pequeno parar de pagar comissão de marketplace. Cliente monta o carrinho e envia direto, dono acompanha status em tempo real num painel.

[Ver online](https://luduran-pedido-direto-demo.vercel.app)

### App de Quiz com ranking local

Quiz de múltipla escolha nativo Android: 6 categorias, cronômetro, ajudas (50/50, tempo extra, pular), combo de sequência e ranking local, tudo 100% offline.

### Cartão de fidelidade digital pra comércio local

Cartão fidelidade digital (Android, iOS e web) sem papel pra perder. Cliente acompanha os carimbos pelo próprio WhatsApp, dono soma carimbo e confirma resgate num painel simples.

[Ver online](https://luduran-fidelidade-demo.vercel.app)

### Rota: delivery com cliente, loja e entregador ao vivo

App de delivery em C# puro (Blazor WebAssembly), três telas conversando ao vivo: o cliente pede e acompanha o entregador no mapa, a loja aceita e prepara, o entregador segue a rota mais curta pelas ruas (A*). Taxa por distância real, etapas do pedido com regra de quem pode mudar cada uma, 34 testes automatizados.

[Ver online](https://rota-delivery.vercel.app)

## Automação & IA

### Aegis — camada de governança para agentes Claude em Go

Resiliência e governança sobre o SDK oficial do Claude em Go: circuit breaker por ferramenta, gate de confirmação para ação irreversível, contrato de saída estruturada validado por schema, sessão persistente. 27 testes automatizados sem rede e sem chave de API.

### Assistente virtual para captação e triagem de um alojamento esportivo

Assistente virtual que atende 24 horas, qualifica famílias interessadas numa vaga de alojamento esportivo de base e entrega o lead pronto pra decisão humana, sem nunca inventar informação que o clube ainda não confirmou.

[Ver online](https://alojamento-base-forte.vercel.app)

### Atendimento automático via WhatsApp para cabanas de temporada

Sistema de atendimento por WhatsApp para uma rede de cabanas de aluguel por temporada: responde diária, disponibilidade e estrutura na hora, e organiza os contatos que viram reserva num painel de operação.

[Ver online](https://cabanas-agent-o37u3uainq-uc.a.run.app/)

### Classificador de Cores — Rede Neural em C# Puro

Rede neural feedforward escrita do zero em C# (sem ML.NET, sem TensorFlow), rodando inteiramente no navegador via Blazor WebAssembly, com backprop verificado por gradient checking.

[Ver online](https://classificador-cores-rede-neural.vercel.app)

### Funil de diagnóstico grátis

Ferramenta de captação de lead: 5 perguntas sim/não sobre a estrutura do negócio, pontuação e recomendação automáticas, CTA direto pro WhatsApp. Java puro, sem framework, HttpServer nativo do JDK.

### Funil de reativação de clientes

Sequência automática de reativação para cliente inativo: lembrete, oferta especial e última chance, cada uma liberada só depois do intervalo certo, com link de WhatsApp pronto e parada automática assim que o cliente responde. Go puro, sem framework.

## Sistema

### Balcão: caixa de loja (PDV) que vende sem internet, em C#

PDV desktop em C# com Avalonia e SQLite: continua vendendo com a internet fora e sincroniza quando ela volta (fila com chave de idempotência, sem venda duplicada), desconto rateado centavo a centavo, fechamento de caixa às cegas e atalhos de teclado pra operador, 37 testes automatizados incluindo a tela.

### Biblioteca de Filmes em C#

Catálogo de filmes em console, C# puro (.NET 8): cadastro, busca por título/gênero/diretor/ano, controle de assistido, avaliação pessoal e ranking por nota, 30 testes automatizados.

### Caixa Eletrônico (ATM) em C#

Simulação de caixa eletrônico em console, C# puro (.NET 8): autenticação por cartão + PIN com hash PBKDF2, saque com limite por transação e por dia, extrato, troca de PIN e telefone, 39 testes automatizados.

### Caixa Forte: gateway de pagamentos em C#

Gateway de pagamentos feito em C# (.NET 8 + Blazor WebAssembly): Pix com QR Code no padrão do Banco Central, cartão com antifraude por regras que explica cada ponto, idempotência contra cobrança em dobro, webhooks assinados com HMAC e nova tentativa automática, estorno, razão em partidas dobradas e conciliação com o extrato. 88 testes automatizados.

[Ver online](https://www.luduranoficiall.com/demos/caixa-forte)

### Comporta: API de alto volume em C#

Simulador feito em C# (.NET 8 + Blazor WebAssembly) das técnicas que seguram uma API sob muito acesso: janela fixa, janela deslizante por registro e por contadores e balde de fichas comparados com o mesmo tráfego, cache LRU em O(1) com validade e junção de buscas simultâneas, escrita agrupada, teste de carga por eventos discretos com Poisson e Zipf mostrando percentis, e medição real cronometrada no navegador.

[Ver online](https://www.luduranoficiall.com/demos/comporta)

### Conselho: consenso Raft em C#

Implementação do Raft em C# (.NET 8 + Blazor WebAssembly) com visualização ao vivo: eleição com tempo sorteado e voto só pra log atualizado, replicação com recuo do líder, confirmação só de entradas do próprio termo, queda e volta de servidor, rede partida, perda de mensagens e teste de caos que confere as garantias de segurança a cada passo.

[Ver online](https://www.luduranoficiall.com/demos/conselho)

### Correnteza: corretor de mensagens estilo Kafka em C#

Corretor de mensagens feito do zero em C# (.NET 8 + Blazor WebAssembly) no modelo do Kafka: tópicos com partições e offsets estáveis, partição por hash da chave, produtor idempotente, grupos de consumo com duas estratégias de divisão, sinal de vida e rebalanceamento, replay, retenção, compactação por chave e três serviços encadeados que processam tudo uma vez.

[Ver online](https://www.luduranoficiall.com/demos/correnteza)

### E-commerce com Clean Architecture e DDD

API de produtos e pedidos em Clean Architecture (4 camadas) e DDD: agregados com invariante real, MediatR + FluentValidation, EF Core + SQLite, 62 testes automatizados sem nenhuma ressalva de ambiente.

### E-commerce Web com Pagamento Assíncrono e Painel Admin em Tempo Real

Loja completa em ASP.NET Core MVC: autenticação real, carrinho persistido, checkout com cupom, pagamento assíncrono em background, concorrência otimista no estoque e painel admin com SignalR. 87 testes automatizados.

### Escala: simulador de autoescala na nuvem em C#

Simulador feito em C# (.NET 8 + Blazor WebAssembly) que compara políticas de escala num dia de tráfego minuto a minuto: fila M/M/1 por servidor, regra do autoescalador do Kubernetes, tempo de aquecimento, janela de estabilidade e agenda pro pico anunciado, com custo, minutos lentos e erros por política, mais Dockerfile e configuração de Kubernetes com as mesmas regras.

[Ver online](https://www.luduranoficiall.com/demos/escala)

### Feira: marketplace com saga entre serviços, em C#

Marketplace feito em C# (.NET 8 + Blazor WebAssembly): várias lojas no mesmo site, busca com índice invertido que entende erro de digitação, carrinho com frete por loja, cupom rateado no centavo, checkout em saga com compensação entre quatro serviços que só conversam por mensagem, comissão por categoria e repasse ao vendedor.

[Ver online](https://www.luduranoficiall.com/demos/feira)

### Fluxo: finanças pessoais em Blazor WebAssembly

Portal de finanças em C# que roda inteiro no navegador: importa extrato OFX e CSV de banco brasileiro sem duplicar, categoriza com regras que aprendem com a correção da pessoa, acompanha limite de gasto e metas, gráficos em SVG próprio, 74 testes automatizados.

[Ver online](https://fluxo-financas-swart.vercel.app)

### Inquilino: plataforma SaaS multiempresa em C#

Plataforma SaaS feita em C# (.NET 8 + Blazor WebAssembly): várias empresas isoladas no mesmo sistema por um repositório que filtra tudo pela sessão, papéis de acesso, planos com limite, chave de API guardada como hash com limite por minuto, cobrança mensal com teste grátis, proporcional na troca de plano e régua de inadimplência.

[Ver online](https://www.luduranoficiall.com/demos/inquilino)

### JavaTitan Engine — motor financeiro com criptografia ponta a ponta

Motor de cálculo financeiro em Java puro: API HTTP nativa, processamento assíncrono, JWT HS256, mTLS e payload cifrado com AES-GCM.

### Lista de Tarefas em C#

CRUD completo de tarefas em C# puro (.NET 8, sem framework web), arquitetura em camadas, exceções de domínio e 16 testes automatizados cobrindo a lógica real.

### Lyra — linguagem interpretada com compilador e VM em C#

Linguagem de programação do zero em C# puro: lexer, parser recursivo-descendente, compilador para bytecode e uma VM stack-based que executa esse bytecode. Suporta função recursiva, closures sobre global, curto-circuito real, 37 testes automatizados.

### Microsserviços com CQRS e RabbitMQ

Dois microsserviços em .NET 8 com escrita e leitura separadas (CQRS), comunicação por eventos via RabbitMQ/MassTransit, EF Core + PostgreSQL e 29 testes automatizados.

### NexusDB — motor de banco de dados LSM-tree em C#

Motor de banco de dados key-value embarcado, C# puro (.NET 8, zero dependências), estruturado como LSM-tree: write-ahead log com checksum, memtable concorrente, SSTables com bloom filter e compaction real. 26 testes automatizados, incluindo recuperação de crash de verdade.

### OmniQuote Core — microsserviços C# e Java integrados

Arquitetura de microsserviços poliglota: gateway em C# .NET 8 orquestrando um motor de cálculo financeiro em Java 17, com Strategy Pattern e JWT.

### Orbital — motor de jobs em background em C#

Motor de processamento de jobs em background em C# puro: fila com prioridade e backpressure real, retry com backoff exponencial e jitter, dead-letter queue e shutdown gracioso em duas fases. 18 testes automatizados.

### Painel de Métricas em Tempo Real (SignalR + Redis + gRPC)

API de alta performance: ingestão via gRPC, transmissão em tempo real via SignalR agrupada por loja, e backplane Redis pra escalar entre múltiplas instâncias sem perder mensagem.

### Plataforma de Agendamentos

API .NET 8 pra prestador de serviço (barbearia, salão, clínica): choque de horário nunca é checagem em memória, é estrutural do banco (chave primária no par prestador+instante), cálculo proativo de horários livres por dia, 31 testes automatizados.

### Quadro: Kanban em tempo real com Blazor e SignalR

Quadro de tarefas em C# onde várias pessoas mexem ao mesmo tempo sem perder nada: ordem dos cartões por índice fracionário, conflito de edição resolvido por junção em três vias, histórico de operações sem buraco e presença ao vivo, 41 testes automatizados incluindo SignalR de ponta a ponta.

### Rastro: estoque com event sourcing e CQRS em C#

Controle de estoque feito em C# (.NET 8 + Blazor WebAssembly) com event sourcing e CQRS: armazém de eventos só de acréscimo com concorrência otimista, snapshots, conversão de eventos de versão antiga na leitura, projeções com checkpoint que mostram o próprio atraso e se reconstroem do zero, viagem no tempo, custo médio ponderado e kardex.

[Ver online](https://www.luduranoficiall.com/demos/rastro)

### Roda: rede social com feed ranqueado em C#

Rede social feita em C# (.NET 8 + Blazor WebAssembly): seguir e bloquear, feed por relevância com decaimento no tempo e afinidade, entrega híbrida (empurrar pra perfil comum, puxar pra perfil grande), assuntos do momento, sugestão por amigos em comum, limite contra spam, filtro de palavras que pega disfarce sem falso positivo e fila de moderação.

[Ver online](https://www.luduranoficiall.com/demos/roda)

### Sinal: central de notificações multicanal em C#

Central de notificações feita em C# (.NET 8 + Blazor WebAssembly): modelos com variável, valor padrão e bloco condicional validados com a posição do erro, fila por prioridade com limite por minuto em cada canal, nova tentativa com espera crescente e canal reserva, horário de silêncio, limite de promoções por dia, resumo diário e contagem de SMS com custo.

[Ver online](https://www.luduranoficiall.com/demos/sinal)

### Tela: streaming de vídeo adaptativo em C#

Streaming de vídeo feito em C# (.NET 8 + Blazor WebAssembly): corte em pedaços e playlists HLS em cinco qualidades, player simulado com buffer comparando escolha pela velocidade, pelo buffer (BBA) e híbrida com desistência de download lento, e continuar assistindo entre aparelhos.

[Ver online](https://www.luduranoficiall.com/demos/tela)

### Template white-label de app sob medida

Esqueleto reutilizável de app (Android, iOS e web) com reducer testado, config de marca única e guia de rebrand embutido. Ferramenta interna pra sair um app novo pra cliente mais rápido, não é produto de cliente.

[Ver online](https://luduran-app-base-demo.vercel.app)

### Vitrine: sistema de recomendação em C#

Sistema de recomendação feito em C# (.NET 8 + Blazor WebAssembly): filtragem colaborativa item a item por cosseno, conteúdo por TF-IDF, híbrido com reordenação MMR pra variedade, explicação de cada sugestão, cliente e produto novos resolvidos e avaliação offline com acerto, NDCG, cobertura e variedade.

[Ver online](https://www.luduranoficiall.com/demos/vitrine)

### Votação Eletrônica com Cadeia de Auditoria

API de votação em .NET 8: voto anônimo separado do comprovante de participação, cada voto encadeia o hash do anterior (adulteração é detectável antes da apuração), identidade do eleitor pseudonimizada com HMAC-SHA256, SignalR pro total ao vivo, 44 testes automatizados.

## Jogo

### Campo Minado

Campo Minado clássico: descubra as células seguras sem detonar mina, primeiro clique nunca é mina. Lógica em Python de verdade, testada com pytest, rodando o mesmo arquivo no navegador via Pyodide.

[Ver online](https://campo-minado-silk.vercel.app)

### Cartas da Masmorra

Rogue-lite de cartas minimalista, estilo Reigns: arraste a carta ou use o teclado pra decidir entre a escolha segura e a arriscada. Joga direto no navegador, sem download, no celular ou no desktop.

[Ver online](https://cartas-da-masmorra.vercel.app)

### Cobra Desvio

Jogo da cobrinha clássico em tempo real: desvie das paredes e do próprio rabo, coma pra crescer. Jogo e interface 100% em Lua, rodando no navegador via fengari, sem música nem timing de batida.

[Ver online](https://cobra-desvio.vercel.app)

### Depósito Lotado

Sokoban clássico: empurre as caixas até os alvos, com desfazer e 4 fases. Jogo e interface 100% em Lua, rodando no navegador via fengari, sem nenhuma linha de JavaScript própria.

[Ver online](https://deposito-lotado.vercel.app)

### Mala Arrumada

Puzzle cozy de encaixe: arraste cada item pra dentro da mala, girando quando precisar, até tudo caber sem sobrepor. Joga direto no navegador, sem download, no celular ou no desktop.

[Ver online](https://mala-arrumada.vercel.app)

### Mario Runner — projeto de estudo em JavaScript puro

Jogo estilo corredor infinito (tema Mario), HTML/CSS/JS puro, sem framework. Projeto de estudo/hobby, não é entrega de cliente — fica separado dos projetos de serviço por isso.

[Ver online](https://luduran-mario-game.vercel.app)
