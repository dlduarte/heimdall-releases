# Política de privacidade do Heimdall

Última atualização: 20 de outubro de 2026

O Heimdall é um app para acessar os seus próprios servidores: terminal SSH,
containers, avisos e rede. Esta política vale para o app do Android, o que a
Google Play distribui.

## O que o Heimdall coleta

**Nada.** O app não tem conta, não tem servidor próprio, não manda dados
para quem o desenvolve nem para terceiros, não tem anúncios, não tem
análise de uso e não tem relatório de erros.

## O que fica no aparelho

- **As conexões** (nome, endereço, porta, usuário) ficam nos arquivos do app,
  no armazenamento interno do aparelho.
- **As senhas e as chaves privadas** ficam cifradas no cofre do aparelho, com
  uma chave do Android Keystore que só abre com a sua biometria ou a senha do
  aparelho. Elas não saem do aparelho, a não ser quando você as usa para
  entrar num servidor seu.
- **O backup na nuvem e a transferência para outro aparelho estão
  desligados**: nada do app vai para o backup do Google. Desinstalar o app
  apaga tudo.

## Com quem o app conversa

- **Com os servidores que você cadastrou**, pelo SSH, que é cifrado de ponta a
  ponta entre o aparelho e o servidor. O que passa por ali (o que você digita
  no terminal, os arquivos, a lista de containers) só existe entre o aparelho
  e o servidor; quem desenvolve o Heimdall não vê nada disso.
- **Com o GitHub**, para as fotos da documentação embutida, que moram no
  repositório público `dlduarte/heimdall-releases`. O pedido é o de qualquer
  imagem da web: não leva nada seu além do que todo acesso leva (o endereço
  IP, que o GitHub recebe pelas regras dele).

## O que sai do app só quando você pede

- **Exportar ou compartilhar um arquivo** abre a folha de compartilhamento do
  Android, e o arquivo vai para o app que você escolher.
- **Entrar numa rede WireGuard** entrega o arquivo de configuração deste
  aparelho ao app oficial do WireGuard, que você escolhe no seletor.
- **Importar do desktop** lê o arquivo exportado que você escolher, cifrado
  com a sua senha mestre.

## Permissões

- **Internet**: para conectar aos seus servidores.
- **Biometria**: para abrir o cofre do aparelho. A digital ou o rosto ficam
  com o Android; o app só recebe "autenticado" ou "não".

## Crianças

O Heimdall é uma ferramenta de administração de servidores, feita para
adultos, e não se destina a crianças.

## Mudanças e contato

Uma mudança nesta política sai com a versão do app que a motivar, e a data no
topo muda junto.

Dúvidas: dlduarte.dev@gmail.com.
