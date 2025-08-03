# buildathon_dynexa
DYNEXA es una plataforma descentralizada y multichain que combina una stablecoin algorítmica anti-devaluación con un ecosistema gamificado de recompensas tokenizadas, asegurando transparencia, gobernanza e interoperabilidad para empresas y usuarios, con impacto real en economías emergentes
# DYNEXA

## Transformando la Fidelización Empresarial en Latinoamérica

---

### ¿Qué es DYNEXA?

DYNEXA es una plataforma B2B2C gamificada y tokenizada, basada en blockchain, que revoluciona los sistemas tradicionales de puntos y recompensas. Permite a empresas emitir **GiftTokens** y a usuarios ganar, transferir y redimir **Dynexas** (el token estable empresarial) en un ecosistema interoperable y multichain (Avalanche & Arbitrum).

---

## Problemática

Los sistemas tradicionales de fidelización presentan:
- **Baja tasa de redención**.
- **Poca percepción de valor**.
- **Cero liquidez e interoperabilidad**.
- **Premios que se devalúan por la inflación local**.
- **Falta de trazabilidad y transparencia**.

---

## Nuestra Solución

- **Dynexas**: Stablecoin empresarial, utilizable como medio de pago y para redimir premios.
- **GiftTokens**: NFT transferibles y programables, canjeables por productos y servicios de un catálogo abierto.
- **Interoperabilidad Multichain**: Arquitectura sobre Avalanche (infraestructura, CMI, bajo costo, escalabilidad) y Arbitrum (integración DeFi y expansión global).
- **API-first**: Integración sencilla para empresas.
- **Gamificación & Experiencia de Usuario**: Sistema de misiones, logros y recompensas que incentivan la participación.

---

## Casos de Uso

1. **Emisión de GiftToken** (empresa → cliente)
2. **Ganancia de Dynexas** (usuario → participación, compras)
3. **Redención de GiftToken** (usuario → marketplace abierto)
4. **Medio de Pago** (Dynexas aceptados por empresas afiliadas)
5. **Swap Dynexas por USDT** (empresa → liquidez real)

---

## Arquitectura Técnica

- **Frontend**: React/Next.js (usando [Scaffold-ETH](https://scaffoldeth.io/) como framework base - [Buidl Guidl](https://buidlguidl.com/))
- **Backend**: Node.js, Python (API RESTful & Gateway Web3)
- **Smart Contracts**: Solidity, Hardhat
    - **Avalanche**: CMI (Interchain Messaging), ICTT (Interchain Token Transfer), eERC
    - **Arbitrum**: contratos en Arbitrum One/Nova
- **Wallets**: Integración no-custodial y custodial
- **Bridges**: Token bridging Avalanche ↔ Arbitrum

---

## Tecnologías Clave

- Avalanche C-Chain & Subnets ([CMI](https://build.avax.network/academy/interchain-messaging), [ICTT](https://build.avax.network/academy/interchain-token-transfer), eERC)
- Arbitrum One ([Introducción](https://docs.arbitrum.io/welcome/arbitrum-gentle-introduction))
- Scaffold-ETH ([sitio oficial](https://scaffoldeth.io/)), Buidl Guidl ([sitio oficial](https://buidlguidl.com/))
- Solidity, Hardhat, React/Next.js, Node.js, Python, IPFS

---

## Roadmap

- [ ] MVP funcional (Avalanche Fuji)
- [x] Integración CMI (Interchain Messaging) y ICTT (Interchain Token Transfer)
- [x] Prueba de contratos en Arbitrum One (tx hash en este README y PDF entregable)
- [ ] Wallet propia para usuarios no-cripto
- [ ] Indexador y analítica avanzada
- [ ] Expansión LatAm y USA

---

## Premios y Elegibilidad (BUILDATHON)

### ⛓️ **Avalanche $400 USD — Mejor integración ICM - ICTT**

- Integramos **ICM** y **ICTT** de Avalanche para transferencias y automatización de tokens y mensajes **entre subredes dentro del ecosistema Avalanche**. Esto permite una interoperabilidad eficiente y segura entre redes privadas empresariales, disminuyendo costos operativos, acelerando las transacciones y brindando mayor control y privacidad para las empresas de nuestra plataforma DYNEXA.
- **Nota:** Actualmente, ICM/ICTT está diseñado para comunicación entre subredes de Avalanche, no para transferencias entre cadenas externas (Arbitrum/Ethereum). Esta solución habilita arquitecturas empresariales escalables, privadas y de bajo costo, ideales para grandes empresas que buscan eficiencia en sus sistemas de fidelización y pagos.
- Consulta documentación:  
    - [ICM: Interchain Messaging](https://build.avax.network/academy/interchain-messaging)  
    - [ICTT: Interchain Token Transfer](https://build.avax.network/academy/interchain-token-transfer)


### **Avalanche $100 USD — Mejor Caso de Uso Empresarial eERC**

- Proponemos y desarrollamos el caso de uso empresarial de mayor viabilidad y escalabilidad aplicando los estándares **eERC** de Avalanche.


### ⚡ **Buidl Guidl/Scaffold-ETH**

- Utilizamos [Scaffold-ETH](https://scaffoldeth.io/) como base para frontend y contratos.
- Mencionamos Buidl Guidl y Scaffold-ETH en README y pitch.
- _Aplicamos a los bounties de Scaffold-ETH y Buidl Guidl_.

###  **Arbitrum**

- Desplegamos al menos un contrato en Arbitrum 
- Prueba del despliegue (tx hash y dirección):  
    - **Contrato DynexaArbitrum.sol:**  
    
---


