## 📦 Repositórios DTIC-IFTM
Repositórios de sistemas, APIs e bibliotecas de componentes e funções do IFTM

> 🧙 Lembre-se de atualizar essa página sempre que adicionar novos repositórios

</br>

# <img src="https://virtualif.iftm.edu.br/VRTL/visao/img/identidade_visual/logotipo-virtualif-marca-medio.svg" width="200" alt="Virtual IF Logo" />
| Repositório | 🔖 | ▶️ | 📑 | ⚙️ | ➕ | 
| ----------- | ----------- |  ----------- |   ----------- |   ----------- | ----------- | 
| [Workflows](https://github.com/dtic-iftm/vrtl-workflows) | Template | [Actions](https://github.com/dtic-iftm/vrtl-workflows/tree/main/.github/workflows) |
| [Template de Módulo](https://github.com/dtic-iftm/vrtl-app-template) | Template |  |
| ⭐ [Template de API](https://github.com/dtic-iftm/vrtl-api-template) | Template |  |
| [Biblioteca de componentes de interface](https://github.com/dtic-iftm/vrtl-lib-core) | Lib  |  |
| [KeyCloak](https://github.com/dtic-iftm/srv-keycloak) | Docker | | |  [Configs via Terraform](https://github.com/dtic-iftm/trf-keycloak-config) | [SPI permissões](https://github.com/dtic-iftm/spi-keycloak-mapper-permissoes/tree/main) <br> [SPI realm attributes](https://github.com/dtic-iftm/spi-keycloak-custom-realm-attributes) <br> [SPI autocomplete authenticator](https://github.com/dtic-iftm/spi-keycloak-email-autocomplete-authenticator) <br>[Temas](https://github.com/dtic-iftm/srv-keycloak-themes) <br>    |
| [Módulo de Ingresso](https://github.com/dtic-iftm/vrtl-app-ingresso-iftm) | APP | [Actions](https://github.com/dtic-iftm/vrtl-app-ingresso-iftm/actions) |  | 
| ⭐ [VirtualIF PHP](https://github.com/dtic-iftm/vrtl-virtualif-php) | APP |  | 
| [Home do VirtualIF](https://github.com/dtic-iftm/vrtl-app-home) | APP |  | 
| [Site IFTM](https://github.com/dtic-iftm/site-iftm) | Site |  | 
| [Ambiente de desenvolvimento VirtualIF PHP](https://github.com/dtic-iftm/srv-virtualif-php) | Docker|  | 
| [API VRTL Core](https://github.com/dtic-iftm/vrtl-api-core) | API| [Actions](https://github.com/dtic-iftm/vrtl-api-core/tree/main/.github/workflows)
| [Exportação / Importação Moodle » VirtualIF](https://github.com/dtic-iftm/vrtl-api-ava) | API | [Actions](https://github.com/dtic-iftm/vrtl-api-ava/tree/master/.github/workflows) | [docs código](https://fuzzy-adventure-4k1kjwm.pages.github.io/)
| [Módulo BEEC](https://github.com/dtic-iftm/vrtl-api-beec) | API | [Actions](https://github.com/dtic-iftm/vrtl-api-beec/tree/main/.github/workflows) | 
</br>

# <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Docker_Logo.png" width="150" alt="Docker Logo">
- [VRTL](https://github.com/dtic-iftm/vrtl-virtualif-docker)
- [Keycloak HMG](https://github.com/dtic-iftm/srv-keycloak-hmg)
- [Moodle](https://github.com/dtic-iftm/ava-docker)
- [APIs Node](https://github.com/dtic-iftm/node-api-docker)

</br>

# <a href="https://ava.iftm.edu.br/" target="blank"><img src="https://moodle.org/theme/moodleorg/pix/moodle_logo_TM.svg" width="150" alt="Moodle Logo" />

| APIs e Plugins | 📑 Tipo | :link: Link |  
| ----------- | ----------- | ----------- |
| IFTM EduTemplate | Tema | [theme_iftm](https://github.com/dtic-iftm/ava-theme-iftm-eduTemplate) |
| API Integração | API | [local_integracao_virtualif](https://github.com/dtic-iftm/ava-integracao-virtuailf)  |
| Exportar Virtual IF | Bloco | [blocks_exportar_virtualif](https://github.com/dtic-iftm/ava-block-exportar-virtualif) |
| Ambiente de Desenvolvimento 4.4 | Docker | [ava-docker](https://github.com/dtic-iftm/ava-docker)|
| Coordenação de Idiomas | Bloco | [blocks_coordenacao_idiomas](https://github.com/dtic-iftm/ava-block-idiomas)
| SSO Keycloak | Local | [local_keycloaklogout](https://github.com/dtic-iftm/ava-keycloaklogout)
| Plano de Ensino | Recurso | [mod_planoensino](https://github.com/dtic-iftm/ava-mod-planoensino)


| Moodles locais |  |  
| ----------- | ----------- |
| Paracatu | https://github.com/dtic-iftm/ava-paracatu | 
| Patos de Minas | https://github.com/dtic-iftm/ava-patos-minas |
| Uberaba | https://github.com/dtic-iftm/ava-uberaba |
| Uberaba Parque Tecnológico | https://github.com/dtic-iftm/ava-parque-tecnologico |
| Uberlândia Centro | https://github.com/dtic-iftm/ava-uberlandia-centro |
| Uberlândia | https://github.com/dtic-iftm/ava-uberlandia |
| Campina Verde | https://github.com/dtic-iftm/ava-campina-verde |
| Ituiutaba | https://github.com/dtic-iftm/ava-ituiutaba |
| Patrocínio | https://github.com/dtic-iftm/ava-patrocinio |


</br>

# ⚙️ Outros

| Repositório             | ⚙️                                                           |
| ----------------------- | ------------------------------------------------------------ |
| API do Google Workspace | https://github.com/dtic-iftm/googleworkspace-controle-contas |

</br>

# 🔌 Portas dos serviços

Para garantir a organização e o gerenciamento adequado dos serviços em execução em cada ambiente, é fundamental manter um registro centralizado das portas utilizadas por cada aplicação. O servidor web Nginx atua como proxy reverso, direcionando as requisições para as aplicações correspondentes, enquanto o PM2 gerencia os processos Node.js em execução.

Esta seção documenta as portas definidas para cada serviço nos ambientes de homologação e produção, facilitando a comunicação entre as equipes de infraestrutura e desenvolvimento. As portas devem ser configuradas no arquivo `.env` ou em `/src/main.ts` de cada aplicação, mantendo a consistência com os valores documentados aqui.

Para mais detalhes sobre as configurações:

- [Configuração dos endereços no Nginx](https://iftm-edu.slite.com/app/docs/WN3J3gbWsimkj1)
- [Configuração dos serviços no PM2](https://iftm-edu.slite.com/app/docs/MLQJvC9Ri3XyuN)

## APIs

| Serviço                                                              | 🧪 Homologação | 🚀 Produção |
| -------------------------------------------------------------------- | :------------: | :---------: |
| [vrtl-api-core ](https://github.com/dtic-iftm/vrtl-api-core)         |      3001      |    3001     |
| [vrtl-api-ava ](https://github.com/dtic-iftm/vrtl-api-ava)           |      3002      |    3002     |
| [vrtl-api-beec ](https://github.com/dtic-iftm/vrtl-api-beec)         |      3003      |    3003     |
| [vrtl-api-academic ](https://github.com/dtic-iftm/vrtl-api-academic) |      3005      |    3005     |

## Apps

| Serviço                                        | 🧪 Homologação | 🚀 Produção |
| ---------------------------------------------- | :------------: | :---------: |
| [exemplo](https://github.com/dtic-iftm/sample) |     porta      |    porta    |

