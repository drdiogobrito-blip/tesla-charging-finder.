TESLA CHARGING FINDER — PACOTE PARA VERCEL

O QUE ESTA VERSÃO CONTÉM
- Site estático responsivo (index.html)
- Manifest e service worker para instalação PWA
- Ícones 192x192 e 512x512
- vercel.json com cabeçalhos para PWA

PUBLICAÇÃO NA VERCEL (GRATUITA)
1. Cria/entra em https://github.com/ e cria um repositório novo, por exemplo: tesla-charging-finder.
2. Carrega para a raiz do repositório TODOS os ficheiros desta pasta (index.html, manifest.webmanifest, sw.js, vercel.json, icon-192.png e icon-512.png).
3. Entra em https://vercel.com/new e escolhe "Continue with GitHub".
4. Importa o repositório tesla-charging-finder.
5. Em Framework Preset escolhe "Other". Deixa Build Command e Output Directory vazios (site estático na raiz).
6. Carrega em Deploy. A Vercel atribui um endereço HTTPS *.vercel.app.
7. Abre o endereço no Chrome Android, permite localização quando solicitado e usa Menu ⋮ > Instalar aplicação.

LIMITAÇÕES IMPORTANTES
- Esta é uma versão de demonstração: os postos, preços, distâncias e disponibilidades no ecrã são fictícios.
- O botão GPS obtém as coordenadas do telemóvel, mas ainda não consulta postos reais nem calcula distâncias a partir da posição.
- Ainda não existe integração operacional com MOBI.E, PRIO, Via Verde, miio ou tarifas Ad Hoc.
- Não utilizar os preços demonstrativos para decidir um carregamento real.

PRÓXIMA FASE DE DESENVOLVIMENTO
Antes de anunciar dados live, é necessário validar as fontes e condições de acesso aos dados MOBI.E, implementar um backend para normalizar postos/conectores/estado, e modelar as tarifas finais de cada CEME/OPC e do pagamento Ad Hoc. Não colocar chaves privadas no HTML público.
