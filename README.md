# 🦷 Consuldente | Odontologia e Estética

Website institucional e portal de serviços da clínica **Consuldente Odontologia**, localizada no Edifício Ana Müller Falcão, em Feira de Santana, Bahia. O projeto apresenta a equipe médica (Drs. Adilson Carneiro e Rodrigo Luna), os tratamentos oferecidos, formas de pagamento, convênios atendidos e canais diretos de agendamento via WhatsApp.

---

## 📌 Sobre a Aplicação
A aplicação atua como a vitrine digital da clínica Consuldente, proporcionando aos clientes e pacientes uma experiência visual sofisticada, transparente e de altíssimo nível. Projetada em tons luxuosos (*Navy & Gold*), a página oferece informações claras sobre os procedimentos odontológicos e facilita a marcação de consultas.

## ✨ Funcionalidades Principais
- 🩺 **Apresentação da Equipe Médica**: Perfil dos especialistas Dr. Adilson Carneiro (Clínico Geral) e Dr. Rodrigo Luna (Estética & Reabilitação).
- 💎 **Catálogo de Serviços**: Detalhamento em clínica geral, estética dental, periodontia e próteses.
- 💳 **Planos e Facilidades**: Informações sobre atendimento particular, convênio Odonto System e formas de pagamento (Pix e cartões).
- 🗺️ **Localização e Contato**: Endereço completo com mapa interativo do Google Maps e botões diretos para chamada e WhatsApp.
- 📱 **Responsividade Multi-Telas**: Interface 100% fluida e adaptada para celulares na vertical (portrait mode), tablets, laptops e PCs.
- 🖱️ **Cursor Personalizado Animado**: Animação de cursor dourado interativo para navegação desktop.

## 🛠️ Tecnologias Utilizadas
- **Frontend**: HTML5 Semântico, Vanilla CSS3 (Custom Properties), JavaScript (ES6+).
- **Recursos Nativos**: Intersection Observer API (efeitos de scroll reveal), Google Maps Embed API, FontAwesome 6.

## 📁 Estrutura do Projeto
- `index.html`: Código-fonte principal da landing page.
- `DrAdilson.jpg`: Fotografia oficial do Dr. Adilson Carneiro.
- `DrRodrigo.jpg`: Fotografia oficial do Dr. Rodrigo Luna.
- `README.md`: Documentação oficial e histórico de alterações do projeto.

---

## 📜 Log de Atualizações (Changelog)

### 📅 27/06/2026 - Otimização Ponytail & Auditoria de Responsividade
- ⚡ **Otimização Ponytail de Recursos**: Substituição de URLs externas brutas do GitHub pelas imagens locais (`DrAdilson.jpg` e `DrRodrigo.jpg`), garantindo carregamento instantâneo e funcionamento 100% offline.
- ⚡ **Desempenho JS**: Refatoração dos escutadores de eventos do cursor animado usando deleção global de eventos (`mouseover`/`mouseout`), reduzindo consumo de memória.
- 📱 **Verificação de Responsividade Multi-Telas**: Garantia de alinhamento perfeito para dispositivos móveis na vertical (smartphones), desativação automática inteligente de cursores desktop em touchscreens e ajuste de tipografia fluida (`clamp`).
- 📚 **Padronização da Documentação**: Reformulação completa do arquivo `README.md` com changelog detalhado.