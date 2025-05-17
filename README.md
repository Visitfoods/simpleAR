# Gelatomania SimpleAR

![Gelatomania Logo](Assets/Gelatomnia%20logo__2.png)

## Descrição do Projeto

Este projeto é um menu interativo em Realidade Aumentada para a Gelatomania, uma gelataria italiana. Permite aos utilizadores visualizarem os gelados em Realidade Aumentada diretamente a partir do navegador, sem necessidade de instalar aplicações nativas.

## Tecnologias Utilizadas

- HTML5 / CSS3 / JavaScript
- [Model-Viewer](https://modelviewer.dev/) para renderização 3D e AR
- Modelos 3D em formato glTF/GLB
- Compatível com ARKit (iOS) e ARCore (Android)

## Arquitetura AR

A solução implementa a arquitetura recomendada pela Apple para apps AR, com dois planos diferentes:

1. **Plano de Ecrã (2D / screen-space)**
   - Interface para controlo da experiência (botões, etiquetas, preços)
   - Segue sempre a câmara
   - Implementado como overlay por cima da ARView

2. **Plano do Mundo (3D / world-space)**
   - Painéis ou etiquetas que flutuam junto do produto
   - Ancorados no mundo virtual
   - Implementados como hotspots no modelo 3D

## Funcionalidades

- Visualização de modelos 3D de gelados
- Rotação automática do modelo
- Experiência em Realidade Aumentada
- Hotspots informativos ancorados ao modelo
- HUD (Heads-Up Display) com informações do produto
- Interface adaptativa para dispositivos móveis
- Animações e efeitos visuais

## Como Executar

1. Abra a página no Safari (iOS) ou Chrome (Android)
2. Toque no botão para ver em Realidade Aumentada
3. Permita o acesso à câmara
4. Mova o dispositivo para detetar uma superfície
5. Toque no ecrã para colocar o gelado no mundo real

## Requisitos

- iOS 12+ com ARKit (iPhones a partir do 6S)
- Android 8.0+ com ARCore
- Acesso via HTTPS (requisito para AR)

## Licença

Copyright © 2023 Gelatomania - Gelataria Italiana

## Créditos

Desenvolvido por Gelatomania 