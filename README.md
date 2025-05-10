# app-ticketing
Aplicativo proposto na disciplina de desenvolvimento para dispositivo móveis, UNESC.


CASE PARA DESENVOLVIMENTO DE SISTEMA: GESTÃO DE EVENTOS E INGRESSOS (TICKETING)
Contexto: Uma produtora de eventos culturais está em fase de expansão e deseja desenvolver uma plataforma digital para gerenciar a venda de ingressos, organização de eventos e controle de acesso. A ideia é oferecer um sistema robusto, tanto para o público final quanto para os organizadores de eventos, capaz de lidar com diferentes tipos de ingressos, pagamentos e validação no local.

Objetivo do Produto (MVP): Criar uma solução completa (mobile + web) para:
Gerenciar eventos (nome, data, local, categorias);
Vender e controlar ingressos por lote e tipo;
Permitir check-in seguro via QR Code nos eventos;
Disponibilizar relatórios e insights aos organizadores.

Funcionalidades do Sistema:
1. Painel Administrativo (Web):
Cadastro de eventos (nome, imagem, descrição, data, horário, local, mapa do local);
Definição de lotes de ingressos (ex: 1º lote com valor promocional);
Tipos de ingresso: meia, inteira, VIP, cortesia, etc.;
Visualização de vendas por lote e status de check-ins;
Exportação de relatórios por evento e público-alvo;
Cadastro de promotores (comissionamento por venda);
Integração com plataformas de pagamento (ex: Stripe, Mercado Pago).
2. Aplicativo para o Público (Mobile):
Listagem de eventos em destaque e por categoria;
Detalhes do evento com imagem, localização, artistas/palestrantes;
Compra de ingresso com opção de cupom de desconto;
Geração automática de ingresso com QR Code;
Histórico de ingressos comprados;
Notificações de alteração de evento ou promoções.
3. Aplicativo para Check-in no Evento (Mobile ou Web):
Acesso exclusivo para equipe de entrada;
Leitura de QR Code do ingresso via câmera;
Validação online e offline com marcação de check-in;
Informações do participante (nome, tipo de ingresso, lote);
Relatório de entradas em tempo real para a organização.

Funcionalidades Técnicas Relevantes:
Sistema de cupons promocionais configuráveis por evento ou data;
Operação offline para check-in em locais sem conexão;
Dashboard com estatísticas de vendas e presença;
Segurança na emissão de ingressos (criptografia de QR Codes);
Notificações push para engajamento do público.

Entregas Esperadas dos Alunos:
Documento de requisitos funcionais e não funcionais;
Protótipos navegáveis (telas para app e painel web);
Estrutura do banco de dados relacional ou NoSQL;
Implementação do MVP com módulos principais;
Apresentação técnica e comercial da solução desenvolvida.

Sugestão de Tecnologias:
Frontend Mobile: Java
Backend: Spring Boot Ou Local
Banco de Dados: SQLite
Pagamentos: Stripe / Mercado Pago / PayPal
QR Code: Biblioteca ZXing / QR Flutter / QR Scanner

Critérios de Avaliação:
Viabilidade técnica e escalabilidade do sistema;
Qualidade da experiência do usuário (UX);
Segurança na transação e validação de ingressos;
Clareza na arquitetura e nos artefatos entregues;
Demonstração funcional do MVP com fluxo completo.

Observação Final: Este projeto proporciona uma experiência rica em múltiplas camadas de desenvolvimento (administração, mobile, integração de terceiros e validação em tempo real), estimulando a visão de produto, as boas práticas de arquitetura e o trabalho em equipe dos alunos.
