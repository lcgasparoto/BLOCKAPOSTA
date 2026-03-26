📱 BlockAposta

O BlockAposta é um aplicativo Android desenvolvido para bloquear completamente o acesso a conteúdos relacionados a apostas online, incluindo sites, aplicativos e downloads, funcionando tanto em redes Wi-Fi quanto em dados móveis.

🎯 Objetivo

Criar uma camada de proteção digital robusta para usuários que desejam eliminar o acesso a plataformas de apostas, reduzindo riscos de vício, prejuízos financeiros e distrações.

⚙️ Como o App Funciona

O BlockAposta atua como um firewall pessoal, interceptando e filtrando todo o tráfego de rede do dispositivo em tempo real.

🔐 1. VPN Local (Interceptação Total)

O aplicativo utiliza a API nativa de VPN do Android para criar uma VPN local (sem servidor externo).

Todo o tráfego de internet passa pelo app
Funciona em Wi-Fi e dados móveis
Não coleta nem envia dados para servidores externos
Atua localmente garantindo privacidade

👉 Isso permite controle total sobre conexões de entrada e saída.

🌐 2. Filtro de DNS Inteligente

O app implementa um sistema de bloqueio baseado em DNS:

Intercepta requisições de domínios
Bloqueia automaticamente domínios conhecidos de apostas
Suporta:
Sites brasileiros e internacionais
Domínios alternativos (espelhos)
Encurtadores de link

📵 3. Bloqueio de Sites de Apostas

Qualquer tentativa de acessar sites relacionados será:

Interrompida antes do carregamento
Redirecionada para uma tela de bloqueio (opcional)
Registrada no sistema de monitoramento

📱 4. Bloqueio de Aplicativos

O BlockAposta monitora apps instalados no dispositivo:

Identifica apps com palavras-chave como:
bet, casino, aposta, gambling
Impede a abertura desses aplicativos
Permite ao usuário:
Desinstalar manualmente
Receber alertas de risco

⬇️ 5. Bloqueio de Downloads

O sistema monitora downloads em tempo real:

Detecta arquivos APK suspeitos
Bloqueia downloads de apps de apostas
Impede instalação de fontes desconhecidas (opcional)

🛡️ 6. Proteção Contra Burlas

O app implementa mecanismos para evitar desativação:

Detecção de VPN externa ativa
Bloqueio de alteração manual de DNS
Monitoramento de proxies e redes anônimas
Opção de ativação como Administrador do Dispositivo

🔒 7. Modo Proteção Total

Modo avançado para controle máximo:

Impede desinstalação sem senha
Bloqueio contínuo (tempo mínimo configurável)
Ideal para momentos de vulnerabilidade

📊 8. Monitoramento e Estatísticas

Painel simples e objetivo:

Status da proteção (Ativo/Inativo)
Número de tentativas bloqueadas
Histórico de acessos bloqueados

🎨 Interface
Design minimalista e intuitivo
Foco em usabilidade rápida
Indicadores visuais claros:
🟢 Seguro
🔴 Bloqueado

🧠 Arquitetura Técnica

Linguagem: Kotlin
VPN: Android VpnService
Banco local: Room Database
Monitoramento: Services em background
Atualização de listas: API REST (opcional)

⚠️ Limitações Conhecidas
Não garante bloqueio contra usuários avançados com root
Pode haver necessidade de atualizações frequentes da blacklist
Consumo leve de bateria devido à VPN ativa

🚀 Visão do Projeto

O BlockAposta não é apenas um bloqueador — é uma ferramenta de disciplina digital.
A proposta é simples: tirar a tentação do caminho e devolver o controle ao usuário.
