# Portfólio — Lucas Duran (luduranoficiall)

Índice de todos os projetos e jogos publicados, separados por tipo. Cada item aqui tem repositório próprio (este repositório não tem código de projeto nenhum, só a lista) e, quando existe, demo ao vivo.

Site principal, com página própria de cada projeto: https://www.luduranoficiall.com/projetos

## Site

### EXTRAORDINÁRIA.AI — site corporativo com chatbot e dashboard de leads

Site corporativo + API para empresa de transformação com IA: landing pública, formulário de contato com notificação de leads, chatbot integrado e dashboard restrito ao CEO com analytics e auditoria.

[Ver online](https://extraordinaria-ai.vercel.app) · [Código](https://github.com/Luduranoficiall/EXTRAORDINARIA-CorporateWebsite)

### Luduranoficiall.com — site institucional com IA e captação via WhatsApp

Site institucional em Next.js com chat de IA (Google Gemini) integrado, catálogo de serviços e preços, e captação direta pelo WhatsApp em todo o site.

[Ver online](https://www.luduranoficiall.com) · [Código](https://github.com/Luduranoficiall/Luduranoficiallcom)

### Site Premium para Escritório de Advocacia

Site institucional para escritório de advocacia (demonstração de portfólio) com painel admin, área do cliente e chatbot de triagem, autenticação real com JWT, banco de dados persistente e 39 testes automatizados.

[Código](https://github.com/Luduranoficiall/Site-Advocacia)

## Aplicativo

### App de agendamento com fila de espera para barbearia/salão/clínica

App de agendamento (Android, iOS e web) com horário disponível em tempo real, fila de espera automática quando lota, e lembrete pro cliente perto do horário. Pensado pra barbearia, salão e clínica.

[Ver online](https://luduran-agendamento-demo.vercel.app) · [Código](https://github.com/Luduranoficiall/agendamento-app)

### App de Clima com assistente de IA

Previsão do tempo nativa Android: localização em tempo real, busca de qualquer cidade, previsão horária e de 7 dias, 3 idiomas, e um assistente de IA que dá conselho prático a partir da previsão real.

[Código](https://github.com/Luduranoficiall/App-de-Clima-do-tempo)

### App de pedido direto sem taxa de marketplace

App de pedido/delivery (Android, iOS e web) pra restaurante pequeno parar de pagar comissão de marketplace. Cliente monta o carrinho e envia direto, dono acompanha status em tempo real num painel.

[Ver online](https://luduran-pedido-direto-demo.vercel.app) · [Código](https://github.com/Luduranoficiall/pedido-direto-app)

### App de Quiz com ranking local

Quiz de múltipla escolha nativo Android: 6 categorias, cronômetro, ajudas (50/50, tempo extra, pular), combo de sequência e ranking local, tudo 100% offline.

[Código](https://github.com/Luduranoficiall/App-de-Quiz)

### Cartão de fidelidade digital pra comércio local

Cartão fidelidade digital (Android, iOS e web) sem papel pra perder. Cliente acompanha os carimbos pelo próprio WhatsApp, dono soma carimbo e confirma resgate num painel simples.

[Ver online](https://luduran-fidelidade-demo.vercel.app) · [Código](https://github.com/Luduranoficiall/fidelidade-digital-app)

## Automação & IA

### Aegis — camada de governança para agentes Claude em Go

Resiliência e governança sobre o SDK oficial do Claude em Go: circuit breaker por ferramenta, gate de confirmação para ação irreversível, contrato de saída estruturada validado por schema, sessão persistente. 27 testes automatizados sem rede e sem chave de API.

[Código](https://github.com/Luduranoficiall/aegis-agent)

### Assistente virtual para captação e triagem de um alojamento esportivo

Assistente virtual que atende 24 horas, qualifica famílias interessadas numa vaga de alojamento esportivo de base e entrega o lead pronto pra decisão humana, sem nunca inventar informação que o clube ainda não confirmou.

[Ver online](https://alojamento-base-forte.vercel.app) · [Código](https://github.com/Luduranoficiall/alojamento-base-forte)

### Atendimento automático via WhatsApp para cabanas de temporada

Sistema de atendimento por WhatsApp para uma rede de cabanas de aluguel por temporada: responde diária, disponibilidade e estrutura na hora, e organiza os contatos que viram reserva num painel de operação.

[Ver online](https://cabanas-agent-o37u3uainq-uc.a.run.app/) · [Código](https://github.com/Luduranoficiall/luduran-cabanas)

### Classificador de Cores — Rede Neural em C# Puro

Rede neural feedforward escrita do zero em C# (sem ML.NET, sem TensorFlow), rodando inteiramente no navegador via Blazor WebAssembly, com backprop verificado por gradient checking.

[Ver online](https://classificador-cores-rede-neural.vercel.app) · [Código](https://github.com/Luduranoficiall/intelig-ncia-artificial-que-reconhece-cores)

### Funil de diagnóstico grátis

Ferramenta de captação de lead: 5 perguntas sim/não sobre a estrutura do negócio, pontuação e recomendação automáticas, CTA direto pro WhatsApp. Java puro, sem framework, HttpServer nativo do JDK.

[Código](https://github.com/Luduranoficiall/funil-diagnostico-gratis)

### Funil de reativação de clientes

Sequência automática de reativação para cliente inativo: lembrete, oferta especial e última chance, cada uma liberada só depois do intervalo certo, com link de WhatsApp pronto e parada automática assim que o cliente responde. Go puro, sem framework.

[Código](https://github.com/Luduranoficiall/funil-reativacao-clientes)

## Sistema

### Biblioteca de Filmes em C#

Catálogo de filmes em console, C# puro (.NET 8): cadastro, busca por título/gênero/diretor/ano, controle de assistido, avaliação pessoal e ranking por nota, 30 testes automatizados.

[Código](https://github.com/Luduranoficiall/Biblioteca-de-Filmes)

### Caixa Eletrônico (ATM) em C#

Simulação de caixa eletrônico em console, C# puro (.NET 8): autenticação por cartão + PIN com hash PBKDF2, saque com limite por transação e por dia, extrato, troca de PIN e telefone, 39 testes automatizados.

[Código](https://github.com/Luduranoficiall/caixa-eletr-nico-ATM-)

### E-commerce com Clean Architecture e DDD

API de produtos e pedidos em Clean Architecture (4 camadas) e DDD: agregados com invariante real, MediatR + FluentValidation, EF Core + SQLite, 62 testes automatizados sem nenhuma ressalva de ambiente.

[Código](https://github.com/Luduranoficiall/e-commerce-clean-architecture-ddd-xunit-fluentvalidation-mediatr-docker)

### E-commerce Web com Pagamento Assíncrono e Painel Admin em Tempo Real

Loja completa em ASP.NET Core MVC: autenticação real, carrinho persistido, checkout com cupom, pagamento assíncrono em background, concorrência otimista no estoque e painel admin com SignalR. 87 testes automatizados.

[Código](https://github.com/Luduranoficiall/-3-E-commerce-web)

### JavaTitan Engine — motor financeiro com criptografia ponta a ponta

Motor de cálculo financeiro em Java puro: API HTTP nativa, processamento assíncrono, JWT HS256, mTLS e payload cifrado com AES-GCM.

[Código](https://github.com/Luduranoficiall/JavaTitan-Engine)

### Lista de Tarefas em C#

CRUD completo de tarefas em C# puro (.NET 8, sem framework web), arquitetura em camadas, exceções de domínio e 16 testes automatizados cobrindo a lógica real.

[Código](https://github.com/Luduranoficiall/Lista-de-tarefas)

### Lyra — linguagem interpretada com compilador e VM em C#

Linguagem de programação do zero em C# puro: lexer, parser recursivo-descendente, compilador para bytecode e uma VM stack-based que executa esse bytecode. Suporta função recursiva, closures sobre global, curto-circuito real, 37 testes automatizados.

[Código](https://github.com/Luduranoficiall/lyra-lang)

### Microsserviços com CQRS e RabbitMQ

Dois microsserviços em .NET 8 com escrita e leitura separadas (CQRS), comunicação por eventos via RabbitMQ/MassTransit, EF Core + PostgreSQL e 29 testes automatizados.

[Código](https://github.com/Luduranoficiall/microsservi-os-cqrs-rabbitmq-kafka)

### NexusDB — motor de banco de dados LSM-tree em C#

Motor de banco de dados key-value embarcado, C# puro (.NET 8, zero dependências), estruturado como LSM-tree: write-ahead log com checksum, memtable concorrente, SSTables com bloom filter e compaction real. 26 testes automatizados, incluindo recuperação de crash de verdade.

[Código](https://github.com/Luduranoficiall/nexusdb)

### OmniQuote Core — microsserviços C# e Java integrados

Arquitetura de microsserviços poliglota: gateway em C# .NET 8 orquestrando um motor de cálculo financeiro em Java 17, com Strategy Pattern e JWT.

[Código](https://github.com/Luduranoficiall/OmniQuote-Core)

### Orbital — motor de jobs em background em C#

Motor de processamento de jobs em background em C# puro: fila com prioridade e backpressure real, retry com backoff exponencial e jitter, dead-letter queue e shutdown gracioso em duas fases. 18 testes automatizados.

[Código](https://github.com/Luduranoficiall/orbital)

### Painel de Métricas em Tempo Real (SignalR + Redis + gRPC)

API de alta performance: ingestão via gRPC, transmissão em tempo real via SignalR agrupada por loja, e backplane Redis pra escalar entre múltiplas instâncias sem perder mensagem.

[Código](https://github.com/Luduranoficiall/api-real-time-signalr-redis-grpc)

### Plataforma de Agendamentos

API .NET 8 pra prestador de serviço (barbearia, salão, clínica): choque de horário nunca é checagem em memória, é estrutural do banco (chave primária no par prestador+instante), cálculo proativo de horários livres por dia, 31 testes automatizados.

[Código](https://github.com/Luduranoficiall/Agendamentos.)

### Template white-label de app sob medida

Esqueleto reutilizável de app (Android, iOS e web) com reducer testado, config de marca única e guia de rebrand embutido. Ferramenta interna pra sair um app novo pra cliente mais rápido, não é produto de cliente.

[Ver online](https://luduran-app-base-demo.vercel.app) · [Código](https://github.com/Luduranoficiall/app-base-white-label)

### Votação Eletrônica com Cadeia de Auditoria

API de votação em .NET 8: voto anônimo separado do comprovante de participação, cada voto encadeia o hash do anterior (adulteração é detectável antes da apuração), identidade do eleitor pseudonimizada com HMAC-SHA256, SignalR pro total ao vivo, 44 testes automatizados.

[Código](https://github.com/Luduranoficiall/votacao-eletronica)

## Jogo

### Campo Minado

Campo Minado clássico: descubra as células seguras sem detonar mina, primeiro clique nunca é mina. Lógica em Python de verdade, testada com pytest, rodando o mesmo arquivo no navegador via Pyodide.

[Ver online](https://campo-minado-silk.vercel.app) · [Código](https://github.com/Luduranoficiall/Campo-Minado)

### Cartas da Masmorra

Rogue-lite de cartas minimalista, estilo Reigns: arraste a carta ou use o teclado pra decidir entre a escolha segura e a arriscada. Joga direto no navegador, sem download, no celular ou no desktop.

[Ver online](https://cartas-da-masmorra.vercel.app) · [Código](https://github.com/Luduranoficiall/cartas-da-masmorra)

### Cobra Desvio

Jogo da cobrinha clássico em tempo real: desvie das paredes e do próprio rabo, coma pra crescer. Jogo e interface 100% em Lua, rodando no navegador via fengari, sem música nem timing de batida.

[Ver online](https://cobra-desvio.vercel.app) · [Código](https://github.com/Luduranoficiall/Cobra-desvio-em-tempo-real)

### Depósito Lotado

Sokoban clássico: empurre as caixas até os alvos, com desfazer e 4 fases. Jogo e interface 100% em Lua, rodando no navegador via fengari, sem nenhuma linha de JavaScript própria.

[Ver online](https://deposito-lotado.vercel.app) · [Código](https://github.com/Luduranoficiall/Sokoban-empurrar-caixa-at-o-alvo-)

### Mala Arrumada

Puzzle cozy de encaixe: arraste cada item pra dentro da mala, girando quando precisar, até tudo caber sem sobrepor. Joga direto no navegador, sem download, no celular ou no desktop.

[Ver online](https://mala-arrumada.vercel.app) · [Código](https://github.com/Luduranoficiall/mala-arrumada)

### Mario Runner — projeto de estudo em JavaScript puro

Jogo estilo corredor infinito (tema Mario), HTML/CSS/JS puro, sem framework. Projeto de estudo/hobby, não é entrega de cliente — fica separado dos projetos de serviço por isso.

[Ver online](https://luduran-mario-game.vercel.app) · [Código](https://github.com/Luduranoficiall/mario)
