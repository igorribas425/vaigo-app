# VaiGo 🚗

Projeto colaborativo de demonstração de aplicativo de corridas.

**Demo:** https://vaigo-gps-corridas.vercel.app

## Funcionalidades
- Mapa e localização do usuário com permissão do navegador
- Sugestões de destinos e pontos de interesse
- Estimativa de rotas, tarifas, comissão e custo de combustível (padrão R$ 6,50/L)
- Solicitação e aceite de corridas **simulados** (sem motoristas ou pagamentos reais)

## Executar
Interface local: `python -m http.server 8000` e acesse http://localhost:8000.
A pesquisa de endereços precisa do endpoint Node.js em `api/search.js`, disponível na implantação Vercel. Para desenvolver com funções locais, configure a Vercel CLI e execute `npx vercel dev`.

## Colaboração
Use branches e pull requests. Não inclua senhas, dados pessoais ou chaves de API no repositório.

**Nota:** não é um serviço de transporte operacional. Os provedores públicos de mapas/endereço têm limites e condições para utilização comercial.
