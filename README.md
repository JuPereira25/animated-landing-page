## Animated Landing Page

Estudo prático focado em CSS `transform` e @keyframes para criar uma landing page com microinterações suaves.

### Objetivos do estudo
- Explorar `transform` (translate, scale, rotate, skew)
- Combinar `transition` e `animation` com `@keyframes`
- Aplicar parallax/offsets sutis em elementos de herói e galeria
- Garantir desempenho com propriedades baratas de animar

### Tecnologias
- HTML5 estático
- CSS3 modular (arquivos em `styles/`)

### Conceitos-chave aplicados
- **transform**: uso de `transform: translate/scale/rotate` para mover e dar profundidade sem relayout
- **transition**: estados de hover/focus com easing e duração consistentes
- **animation/@keyframes**: loops leves para elementos decorativos (estrelas, elipses)
- **transform-origin** e **perspective**: ajustes finos de origem e sensação 3D quando necessário
- **will-change**: indicações pontuais para o navegador preparar composições

### Estrutura
- `index.html`: marcação base
- `styles/*.css`: estilos separados por seção (hero, banner, header, gallery, footer)
- `assets/`: imagens e ícones


### Notas de desempenho
- Prefira `transform` e `opacity` nas animações
- Evite animar `top/left/width/height`
- Use durações e easings consistentes para coesão visual



