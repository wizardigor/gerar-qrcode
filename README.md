# Gerar QR Code

Gerador de QR Codes gratuito, responsivo e em português. Funciona no navegador com a biblioteca [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) carregada por CDN.

## Recursos implementados

- Wi-Fi (SSID, WPA/WPA2, WEP, rede aberta, senha, rede oculta)
- Vídeo por URL
- Localização no Google Maps
- E-mail com destinatário, assunto e mensagem
- Feedback por link de formulário
- Link de aplicativo (destino principal)
- Multi-Link por URL de página pública
- SMS com número e texto
- Pagamento por Pix Copia e Cola ou link de pagamento
- Cores, estilos de pontos, tamanho, margem, nível de correção de erros e logotipo JPG/PNG
- Exportação PNG, JPG e SVG

## Executar

Abra `index.html` no navegador com acesso à internet ou publique a branch principal no GitHub Pages (Settings > Pages > Deploy from a branch > main / root).

## Limitações e próximos passos

- Multi-Link precisa de uma página pública hospedada para reunir os links. A edição dos links ainda não publica uma landing page automaticamente.
- Link de App não detecta automaticamente Android/iOS; isso exige uma página intermediária.
- Os formatos coração, flor, estrela e triângulo para o QR completo não estão implementados. A biblioteca suporta estilos de módulos, preservando a leitura.
- Imagens individuais, logos e redes sociais do Multi-Link ainda não são publicados em uma página.
- Não há gateway de pagamento nem validação bancária do payload Pix.
- Testar leitura em vários dispositivos antes de usar comercialmente.

## Privacidade

Os dados inseridos são processados no navegador. A biblioteca JavaScript é carregada por CDN; para funcionamento offline, hospede uma cópia local da dependência.

## Licença

Licença a definir pelo mantenedor.
