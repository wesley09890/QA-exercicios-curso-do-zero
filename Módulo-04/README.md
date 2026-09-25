## 🔍 Investigação com DevTools

Prática de investigação técnica usando o **DevTools** (Console e aba Network) em um site de prática, analisando as páginas **A/B Testing**, **Add/Remove Elements** e **Basic Auth**.

### O que foi observado
- Requisições com status **200 OK** indicando carregamento bem-sucedido dos recursos.
- Avisos de **layout forçado** antes do carregamento completo da página.
- Erros de **cookies rejeitados** por domínio inválido.
- Falhas de requisição **CORS** e erro `NS_ERROR_UNKNOWN_HOST` em chamadas externas (Optimizely).
- Requisição do `favicon.ico` retornando **404 (Not Found)**.
- Uso da aba **Network** para inspecionar método, status e tempo de cada requisição.

### Aprendizado
O Console e a aba Network ajudam a identificar a **causa raiz** de um problema, não apenas o sintoma visível na tela. Erros de cookie, CORS ou falhas de rede muitas vezes não aparecem na interface, mas ficam registrados nos logs do navegador — reforçando a importância de analisar essas ferramentas durante a investigação de bugs.
