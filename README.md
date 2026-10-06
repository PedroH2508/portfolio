# Landing pages fictícias

Modelos de landing page estáticos (HTML, CSS e GSAP), feitos como estudo. Todos os nomes, registros, preços e contatos são fictícios.

| Página | Arquivo |
|---|---|
| Escritório de advocacia | [index.html](index.html) |
| Advocacia, versão neutra (sem foco em uma área, com cuidados do Provimento 205/2021 da OAB) | [modelo-neutro.html](modelo-neutro.html) |
| Barbearia | [barbearia.html](barbearia.html) |
| Clínica odontológica (com responsável técnica e CRO, sem preços) | [odontologia.html](odontologia.html) |

## Como abrir

Não há etapa de build. Abra os arquivos `.html` direto no navegador ou sirva a pasta com qualquer servidor estático, por exemplo:

```bash
python -m http.server 5510
```

## Dependências externas

- Fontes do Google Fonts
- GSAP 3.12.5 e ScrollTrigger (cdnjs). Sem eles, a página aparece normalmente, apenas sem animações.

## Imagens

As fotos de barbearia e odontologia são do Unsplash; veja [images/CREDITOS.md](images/CREDITOS.md).
