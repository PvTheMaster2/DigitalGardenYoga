---
dg-publish: true
dg-home: false
title: Anahata - Visualizações Interativas
aliases:
  - Anahata Canvas
  - Visualizações Anahata
  - Mapas Anahata
tags:
  - source/yoga-tratado
  - type/visualization
  - type/interactive
  - theme/yoga/energy/chakra
  - theme/yoga/energy/anahata
  - theme/yoga/canvas
created: 2025-01-31
updated: 2025-06-28T14:22
---

# 🌸 Anahata - Visualizações Interativas

> **Chakra do Coração | Centro Energético da Compaixão**  
> Explore os mapas visuais e conexões do Anahata Chakra através de visualizações interativas.

---

## 📊 Visualizações Disponíveis

### 1. 🗺️ Mapa Completo do Anahata
**Visão geral completa do sistema energético do chakra do coração**

<div class="image-zoom-container">
  <img src="canvas_anahata_completo.png" alt="Mapa Completo do Anahata Chakra" class="zoomable-image" title="Clique para ampliar - Mapa Completo do Anahata">
  <div class="image-caption">
    <strong>Canvas Anahata Completo</strong><br>
    <em>Mapa detalhado do chakra do coração, suas conexões e práticas associadas</em>
  </div>
</div>

### 2. 🔄 Sistema dos Nadis
**Rede de canais energéticos conectados ao Anahata**

<div class="image-zoom-container">
  <img src="canvas_nadis.png" alt="Sistema dos Nadis" class="zoomable-image" title="Clique para ampliar - Sistema dos Nadis">
  <div class="image-caption">
    <strong>Canvas dos Nadis</strong><br>
    <em>Visualização da rede de canais energéticos (nadis) e suas interconexões</em>
  </div>
</div>

### 3. 🌟 Estrutura Energética (Versão Preliminar)
**Análise estrutural do sistema energético do Anahata**

<div class="image-zoom-container">
  <img src="anahata sem confirmação.png" alt="Estrutura Energética do Anahata" class="zoomable-image" title="Clique para ampliar - Estrutura Energética">
  <div class="image-caption">
    <strong>Anahata - Estrutura Energética</strong><br>
    <em>Mapa da estrutura energética e componentes do chakra (versão em desenvolvimento)</em>
  </div>
</div>

---

## 🎯 Como Usar

### 💡 Funcionalidades Interativas

1. **🔍 Zoom**: Clique em qualquer imagem para ampliá-la
2. **📱 Responsivo**: As imagens se adaptam ao seu dispositivo
3. **🎨 Visualização**: Explore detalhes específicos de cada mapa
4. **🔗 Navegação**: Use as legendas para entender cada visualização

### 📋 Guia de Navegação

| Visualização | Foco Principal | Melhor Para |
|-------------|---------------|-------------|
| **Mapa Completo** | Visão geral integrada | Estudo sistemático |
| **Sistema Nadis** | Canais energéticos | Práticas de pranayama |
| **Estrutura Energética** | Componentes internos | Análise detalhada |

---

## 🔗 Recursos Relacionados

### 📚 Conteúdo Complementar
- [[00 - INBOX/Anahata/Anahata Chakra\|Anahata Chakra]] - Base teórica completa
- [[00 - INBOX/Anahata/Nadis\|Nadis]] - Estudo detalhado dos canais energéticos
- [[Pranayama\|Pranayama]] - Técnicas de respiração

### 🧘 Práticas Recomendadas
- **Meditação Visual**: Use as imagens como foco meditativo
- **Estudo Dirigido**: Analise cada seção metodicamente
- **Prática Integrada**: Combine visualização com exercícios práticos

---

## 🎨 Estilos para Zoom Interativo

<style>
.image-zoom-container {
  margin: 20px 0;
  text-align: center;
  position: relative;
}

.zoomable-image {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  cursor: zoom-in;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.zoomable-image:hover {
  transform: scale(1.02);
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.image-caption {
  margin-top: 10px;
  padding: 10px;
  background: rgba(0,0,0,0.05);
  border-radius: 6px;
  font-size: 0.9em;
  color: #666;
}

.image-caption strong {
  color: #333;
}

/* Zoom Modal */
.image-modal {
  display: none;
  position: fixed;
  z-index: 1000;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0,0,0,0.9);
  cursor: zoom-out;
}

.image-modal img {
  margin: auto;
  display: block;
  max-width: 90%;
  max-height: 90%;
  margin-top: 5%;
}

@media (max-width: 768px) {
  .zoomable-image {
    max-width: 100%;
  }
  
  .image-modal img {
    max-width: 95%;
    max-height: 95%;
    margin-top: 2.5%;
  }
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // Adiciona funcionalidade de zoom às imagens
  const images = document.querySelectorAll('.zoomable-image');
  
  images.forEach(img => {
    img.addEventListener('click', function() {
      // Cria modal para zoom
      const modal = document.createElement('div');
      modal.className = 'image-modal';
      modal.style.display = 'block';
      
      const modalImg = document.createElement('img');
      modalImg.src = this.src;
      modalImg.alt = this.alt;
      
      modal.appendChild(modalImg);
      document.body.appendChild(modal);
      
      // Fecha modal ao clicar
      modal.addEventListener('click', function() {
        document.body.removeChild(modal);
      });
      
      // Fecha modal com ESC
      document.addEventListener('keydown', function(e) {
        if (e.key === 'Escape' && modal.parentNode) {
          document.body.removeChild(modal);
        }
      });
    });
  });
});
</script>

---

## 🌟 Próximos Passos

1. **📝 Análise Detalhada**: Estude cada visualização metodicamente
2. **🔄 Correlação**: Compare as diferentes perspectivas
3. **🧘 Prática**: Integre o conhecimento visual com exercícios práticos
4. **📚 Estudo**: Aprofunde-se nos conceitos através dos links relacionados

---

*Este documento é parte do sistema de estudos do **Tratado de Yoga**. Para mais informações, consulte os recursos complementares linkados acima.* 