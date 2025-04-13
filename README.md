💻 Computação em Nuvem — Conceitos Essenciais

Este documento tem como objetivo explicar de forma clara os conceitos de nuvem pública, privada e híbrida, além de abordar temas importantes como Bastions (Bastiões), CapEX & OpEX e SLA, com foco especial na Azure.
☁️ Tipos de Computação em Nuvem
🔹 Nuvem Pública

Na nuvem pública, os recursos de computação (servidores, armazenamento e redes) são gerenciados por provedores terceiros — como Microsoft Azure, AWS ou Google Cloud — e compartilhados entre vários clientes (multitenancy).
Vantagens:

    Escalabilidade instantânea.

    Menor custo inicial.

    Facilidade de acesso global.

🔹 Nuvem Privada

Aqui os recursos são dedicados exclusivamente a uma única organização. Ela pode estar hospedada localmente ou em data centers privados. Vantagens:

    Controle total sobre segurança e compliance.

    Personalização completa.

    Ideal para dados sensíveis ou regulados.

🔹 Nuvem Híbrida

Combina nuvem pública e privada, permitindo que dados e aplicações transitem entre ambientes conforme a necessidade. Vantagens:

    Flexibilidade e escalabilidade.

    Otimização de custos.

    Permite manter dados críticos em ambiente privado e o restante na nuvem pública.

🔐 Bastions (Bastião)

Um Bastion Host é uma máquina virtual (geralmente Linux ou Windows) usada como intermediária para acessar servidores internos que estão protegidos em uma rede privada.

Vantagens:

    Acesso seguro a máquinas internas via SSH ou RDP.

    Diminui exposição de IPs públicos.

    Aplicação comum em arquiteturas cloud para proteger bancos de dados e serviços críticos.

💸 CapEX vs OpEX
💡 CapEX (Capital Expenditure)

Investimentos de capital em bens duráveis. No contexto de TI, significa comprar servidores, licenças, roteadores e manter infraestrutura física.

Vantagem: O ativo é da empresa.
Desvantagem: Alto investimento inicial e manutenção constante.
💡 OpEX (Operational Expenditure)

Custos operacionais que ocorrem de forma recorrente, como pagamento de serviços cloud, licenças SaaS ou suporte técnico.

Vantagem: Menor investimento inicial e pagamento sob demanda.
Desvantagem: Dependência contínua do provedor.
📈 SLA — Service Level Agreement

O SLA é o Acordo de Nível de Serviço firmado entre cliente e fornecedor. Define métricas de qualidade como:

    Uptime (tempo de disponibilidade).

    Tempo de resposta.

    Suporte técnico.

🔹 SLA na Microsoft Azure

A Azure geralmente oferece SLAs robustos, por exemplo:

    99,9% para máquinas virtuais com disco único.

    99,99% para VMs em conjuntos de disponibilidade.

    Serviços de banco de dados, redes, storage e segurança também seguem SLAs definidos, garantindo confiabilidade e disponibilidade.
